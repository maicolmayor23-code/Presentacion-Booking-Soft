## Restricciones del Sistema – Hotel Facile

### RST-001: Módulo de Documentos Digitales
*Descripción:*  
El sistema debe almacenar todos los contratos y documentos administrativos en un módulo digital seguro y centralizado.

*Restricciones:*  
- Solo el personal autorizado puede consultar, modificar o eliminar informacion.  
- No se permite almacenamiento fuera del módulo digital ni en medios externos no autorizados.  

---

### RST-002: Capacidad de Apartamentos y Habitaciones
*Descripción:*  
El sistema debe respetar la capacidad física que tiene el hotel y no permitir que los registros excedan la disponibilidad.

*Restricciones:*  
- Máximo 27 apartamentos y 10 habitaciones.  
- No se pueden generar reservas que superen la disponibilidad.  
- Cada apartamento debe estar correctamente categorizado (dúplex, doble, familiar y habitaciones).  

---

### RST-003: Gestión de Servicios del Hotel
*Descripción:*  
Todos los servicios deben estar asignados a los apartamentos o habitaciones.

*Restricciones:*  
- Los servicios incluyen limpieza, recepción, mantenimiento y atención personalizada.  
- No se permiten nuevos servicios fuera del inventario a apartamentos.    

---

### RST-004: Notificaciones Automáticas
*Descripción:*  
El sistema debe generar notificaciones automáticas precisas y seguras.

*Restricciones:*  
- para los evento se debe dar confirmaciones de pago, avisos importantes y alertas críticas.  
- Usuarios no autorizados no recibirán esta información.    
---

### RST-005: Soporte Técnico
*Descripción:*  
El soporte técnico debe ofrecerse de manera controlada y consistente.

*Restricciones:*  
- Canales oficiales: WhatsApp y atención telefónica.  
- No se permite atender solicitudes por canales no controlados.  

---

### RST-006: Operación 24/7 y Mantenimiento
*Descripción:*  
El sistema debe permanecer operativo permanentemente, con mantenimiento mínimo e impactando lo menos posible al usuario.

*Restricciones:*  
- Sistema operativo 24/7.  
- Mantenimiento fuera de horario crítico, garantizando la disponibilidad de servicios esenciales.  

---

### RST-007: Tiempo de Respuesta
*Descripción:*  
El sistema debe responder rápidamente a las consultas y generación de reportes.

*Restricciones:*  
- Consultas rápidas (disponibilidad de habitaciones, reservas, eventos): ≤ 5 segundos.  
- Reportes complejos (ocupación, uso de salones, solicitudes de servicios): ≤ 1 minuto.  

---

### RST-008: Generación de Reportes
*Descripción:*  
Los reportes deben ser precisos y reflejar información real y actualizada.

*Restricciones:*  
- Solo usuarios autorizados pueden generar o exportar reportes.  
- Reportes incluyen: ocupación de habitaciones, uso de salones, solicitudes de servicios adicionales.  
- No se permiten reportes con datos duplicados o inconsistentes.  

---

### RST-009: Modelo de Negocio y Tarifas
*Descripción:*  
El sistema debe manejar exclusivamente las tarifas definidas por el hotel.

*Restricciones:*  
- Tarifas: diaria, semanal, quincenal, mensual.  
- No se permite registrar reservas con tarifas distintas a las definidas.  

---

### RST-010: Registro Histórico
*Descripción:*  
El sistema debe mantener un historial completo de todas las operaciones del hotel.

*Restricciones:*  
- Conservación de registros desde el inicio del hotel (9 años de operación).  
- Modificaciones históricas solo con autorización administrativa.

