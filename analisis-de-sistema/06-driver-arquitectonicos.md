# Drivers arquitectónicos

| ID | Driver arquitectónico | Origen | ¿Por qué influye en la arquitectura? |
|---|---|---|---|
| DA01 | Soportar un incremento de usuarios durante campañas comerciales. | AC03 - Escalabilidad | Influye en cómo se dimensiona y despliega el sistema. |
| DA02 | Mantener tiempos de respuesta adecuados con alta concurrencia. | AC01 - Rendimiento | Influye en la comunicación entre módulos y en el acceso a los datos. |
| DA03 | Proteger los datos de usuarios y las operaciones de compra. | AC04 - Seguridad | Requiere definir mecanismos de autenticación, autorización y protección de datos. |
| DA04 | Integrarse con una pasarela de pago externa. | RC04 - Pasarela de pago | Requiere definir cómo el sistema se comunica con el proveedor de pagos. |
| DA05 | Utilizar una API REST entre la aplicación web y el backend. | RC03 - API REST | Define la forma de comunicación entre la interfaz y la lógica de negocio. |
| DA06 | Integrarse con un servicio de envío externo. | RC05 - Servicio de envío | Requiere definir cómo se intercambia la información de entrega. |
| DA07 | Organizar la propuesta inicial en tres capas. | RC06 - Arquitectura en tres capas | Determina la separación de responsabilidades entre presentación, negocio y datos. |
