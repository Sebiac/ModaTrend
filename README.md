## Plan de Pruebas para ModaTrend

Este plan de pruebas tiene como objetivo validar el correcto funcionamiento del sistema ModaTrend, asegurando que cumpla con los requisitos funcionales y no funcionales definidos. Se utilizarán diferentes tipos de pruebas para garantizar la calidad del software antes de su implementación.

### Objetivos del Plan de Pruebas

• Verificar que todas las funcionalidades del sistema operen según lo esperado.  
• Garantizar la sincronización en tiempo real del inventario.  
• Validar la seguridad y rendimiento del sistema.  
• Asegurar una experiencia de usuario fluida y sin errores.  

### Tipos de Pruebas a Realizar

#### Pruebas Funcionales

Validarán que cada función del sistema cumpla con los requisitos establecidos.

| Caso de Prueba                | Descripción                                                                 | Criterios de Aceptación                              |
|-------------------------------|-----------------------------------------------------------------------------|------------------------------------------------------|
| Registro de Usuario           | Verificar que un usuario pueda registrarse correctamente                    | Datos guardados y confirmación enviada               |
| Inicio de Sesión              | Validar acceso con credenciales correctas/incorrectas                       | Solo acceso con credenciales válidas                 |
| Consulta de Catálogo          | Verificar visualización de productos                                       | Productos cargados sin errores                       |
| Sincronización de Inventario  | Comprobar actualización en tiempo real del stock                           | Cambios reflejados inmediatamente                   |
| Recomendaciones Personalizadas| Validar sugerencias basadas en historial                                    | Recomendaciones coinciden con preferencias          |
| Agregar al Carrito            | Probar funcionalidad del carrito                                           | Productos añadidos y total calculado correctamente  |
| Reserva (Click & Collect)     | Verificar reserva de productos                                             | Reserva registrada y stock actualizado              |
| Proceso de Pago               | Validar integración con Stripe/Mercado Pago                                | Pago procesado sin errores                          |
| Generación de Reportes        | Verificar creación de reportes de ventas                                   | Datos mostrados son precisos                        |

#### Pruebas No Funcionales

Asegurar que el sistema cumpla con aspectos de rendimiento, seguridad y usabilidad.

| Tipo de Prueba       | Descripción                                      | Criterios de Aceptación                     |
|----------------------|--------------------------------------------------|---------------------------------------------|
| Rendimiento          | Evaluar tiempos de respuesta bajo carga          | Respuesta en <2 segundos                    |
| Escalabilidad        | Probar con múltiples usuarios concurrentes       | Soporta ≥1,000 usuarios                     |
| Disponibilidad       | Verificar uptime y resistencia a fallos          | 99.9% disponibilidad en pruebas             |
| Seguridad            | Validar protección de datos y autenticación      | Bloquea accesos no autorizados              |
| Compatibilidad       | Probar en navegadores y dispositivos             | Funciona en Chrome, Firefox, Edge, móviles  |


#### Pruebas de Usabilidad

• Navegación intuitiva: Evaluar si los usuarios encuentran fácilmente las funciones.  
• Diseño responsivo: Verificar que la interfaz se adapte a móviles y tablets.  
• Feedback visual: Confirmar que las acciones del usuario tengan retroalimentación clara.  

#### Pruebas de Integración

• Validar la comunicación entre módulos (ej: catálogo, carrito, pagos).  
• Verificar que los datos fluyan correctamente entre frontend y backend.  

#### Pruebas de Regresión

• Ejecutar pruebas después de cada actualización para asegurar que no se introdujeron errores.  

### Entorno de Pruebas

• Frontend: Navegadores (Chrome, Firefox, Safari, Edge).  
• Backend: Servidores de desarrollo y staging.  
• Base de datos: MySQL/PostgreSQL con datos de prueba.  
• Dispositivos: Móviles (iOS/Android), tablets y desktop.  

### Cronograma de Pruebas



### Criterios de Aprobación

• Funcional: Todas las pruebas pasan con éxito.  
• Rendimiento: Cumple con los tiempos de respuesta esperados.  
• Seguridad: No se encontraron vulnerabilidades críticas.  
• Usabilidad: Los usuarios finales aprueban la experiencia.  
  
