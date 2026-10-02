# Decisiones arquitectónicas

Las decisiones arquitectónicas se definen a partir de los drivers identificados para el Marketplace.

| ID | Decisión arquitectónica | Driver relacionado | Justificación | Resultado |
|---|---|---|---|---|
| ADR-001 | Monolito modular | DA01 - Escalabilidad, DA08 - Mantenibilidad | Permite organizar las funcionalidades en módulos independientes dentro de una misma aplicación. | Módulos de Usuarios, Catálogo, Carrito, Pedidos y Pagos. |
| ADR-002 | Clean Architecture | DA08 - Mantenibilidad | Permite separar las reglas del negocio de los detalles tecnológicos. | Separación en Dominio, Aplicación, Infraestructura y Presentación. |
| ADR-003 | Estrategia de caché | DA02 - Rendimiento | Permite reducir consultas repetitivas y mejorar los tiempos de respuesta. | Caché para información de consulta frecuente. |
| ADR-004 | Integración de pagos mediante interfaces y adaptadores | DA04 - Pasarela de pago | Permite desacoplar la lógica del sistema del proveedor externo de pagos. | Interfaz de pagos y adaptador para la pasarela externa. |
