## CU-001: Gestión de Estado de Habitaciones del hotel

### CU-001.1: Registro de Estado de Habitaciones

**Descripción:**  
El sistema permite registrar en tiempo real el estado de las habitaciones (limpia, ocupada, en mantenimiento) para que ventas y comercial puedan visualizar la disponibilidad.

**Actor:**  
Responsable de limpieza / Housekeeping

**Precondiciones:**  
- El usuario debe estar registrado.
- La habitación debe estar activa en el inventario.

**Flujo Principal:**  
1. El empleado accede al módulo de habitaciones.  
2. El sistema muestra la lista de habitaciones con estado actual.  
3. El empleado selecciona una habitación.  
4. Cambia el estado de la habitación (limpia, ocupada, mantenimiento).  
5. El sistema actualiza la disponibilidad en tiempo real.  
6. Ventas y comercial pueden visualizar la nueva disponibilidad.

**Poscondiciones:**  
- El estado de la habitación queda actualizado y registrado.  
- Historial de cambios disponible para auditoría.

---

## CU-002: Vinculación Financiera de Reservas

### CU-002.1: Generación Automática de Reportes Financieros

**Descripción:**  
El sistema vincula reservas y servicios con el módulo financiero para generar reportes automáticos de ingresos, egresos y ocupación.

**Actor:**  
CEO

**Precondiciones:**  
- El módulo financiero debe estar activo.  
- Reservas y servicios registrados.

**Flujo Principal:**  
1. El sistema captura las reservas y servicios registrados.  
2. Se calculan automáticamente ingresos, egresos y ocupación.  
3. Se genera el reporte financiero.  
4. El gerente financiero visualiza o exporta el reporte.

**Poscondiciones:**  
- Reportes actualizados automáticamente.  
- Información financiera consistente y confiable.

---

## CU-003: Gestión de Inventario y Alertas

### CU-003.1: Control de Stock de Insumos

**Descripción:**  
Permite gestionar el stock de insumos hoteleros y generar alertas automáticas cuando los niveles sean bajos.

**Actor:**  
Recepción

**Precondiciones:**  
- Inventario de insumos cargado en el sistema.

**Flujo Principal:**  
1. El sistema monitorea niveles de inventario en tiempo real.  
2. Genera alerta automática si el stock está a bajo nivel.  
3. El administrador recibe notificación para reposición.

**Poscondiciones:**  
- Alertas enviadas lo más eficiente y rápido posible.  
- Inventario actualizado.

---

## CU-004: Centralización de Canales de Comunicación

### CU-004.1: Gestión Unificada de Reservas y Mensajes

**Descripción:**  
Centraliza todas las comunicaciones del hotel (Despegar, Booking, Expedia, WhatsApp, correo y llamadas) en un módulo único.

**Actor:**  
Coordinador de reservas (recepción)

**Precondiciones:**  
- Conexión activa y efectiva con los canales de comunicación.  

**Flujo Principal:**  
1. El sistema recibe información de todos los canales.  
2. Centraliza reservas, disponibilidad y mensajes pendientes según los datos que se reciben.  
3. El coordinador visualiza la información en tiempo real.  
4. Gestiona respuestas rápidas y acciones necesarias.

**Poscondiciones:**  
- Información de todos los canales sincronizada.  
- Mensajes y reservas actualizados en tiempo real.

---

## CU-005: Acceso 24/7 al Sistema

### CU-005.1: Consulta y Gestión de Reservas en Tiempo Real

**Descripción:**  
Permite acceso continuo a clientes y empleados para consultar reservas y realizar solicitudes.

**Actor:**  
Clientes y empleados del hotel

**Precondiciones:**  
- Usuario registrado.  
- Sistema operativo disponible.

**Flujo Principal:**  
1. El usuario accede al sistema desde cualquier dispositivo.  
2. Consulta estado de reservas o realiza nuevas solicitudes.  
3. Recibe confirmaciones automáticas en tiempo real.

**Poscondiciones:**  
- Reservas y solicitudes actualizadas.  
- Usuario y empleado informados al instante.

---

## CU-006: Gestión de Mantenimiento de Habitaciones

### CU-006.1: Registro y Asignación de Incidencias

**Descripción:**  
Registra incidentes de habitaciones y notifica al área técnica para resolución oportuna.

**Actor:**  
Recepción

**Precondiciones:**  
- Habitaciones registradas en el sistema.

**Flujo Principal:**  
1. El sistema detecta o registra incidencia.  
2. Notifica al área técnica automáticamente.  
3. Se asignan tareas al personal de mantenimiento.  
4. Se realiza seguimiento del estado de la incidencia.

**Poscondiciones:**  
- Incidencias resueltas y registradas.  
- Historial de mantenimiento disponible.

---

## CU-007: Gestión de Contratos y Documentos Digitales

### CU-007.1: Almacenamiento y Consulta de Contratos

**Descripción:**  
Permite almacenar, organizar y consultar contratos de arrendamiento, reservas y documentos administrativos.

**Actor:**  
Recepción

**Precondiciones:**  
- Contratos y documentos cargados en el sistema.

**Flujo Principal:**  
1. Usuario accede al módulo de contratos.  
2. Busca o consulta documentos.  
3. Puede agregar, actualizar o eliminar documentos según permisos.

**Poscondiciones:**  
- Documentos disponibles y centralizados.  
- Historial de cambios registrado.

---

## CU-008: Registro y Gestión de Clientes Frecuentes

### CU-008.1: Identificación y Preferencias de Clientes

**Descripción:**  
Permite identificar clientes frecuentes y mostrar su historial de reservas y preferencias.

**Actor:**  
Recepción

**Precondiciones:**  
- Base de datos de clientes actualizada.

**Flujo Principal:**  
1. Usuario consulta base de clientes.  
2. El sistema muestra historial y preferencias.  
3. Administrador puede gestionar beneficios especiales.

**Poscondiciones:**  
- Información de clientes organizada y disponible.  
- Beneficios aplicados correctamente.

---

## CU-009: Check-in y Check-out Digital

### CU-009.1: Registro de Entrada y Salida Digital

**Descripción:**  
Permite realizar el proceso de check-in y check-out de forma digital.

**Actor:**  
Recepción y clientes

**Precondiciones:**  
- Reserva confirmada.  
- Cliente autenticado.

**Flujo Principal:**  
1. Cliente inicia sesión en el sistema.  
2. Completa check-in o check-out digital.  
3. El sistema actualiza estado de ocupación.

**Poscondiciones:**  
- Estado de la habitación actualizado.  
- Registro de entrada/salida digitalizado.

---

## CU-011: Reporte de Disponibilidad en Línea

### CU-011.1: Consultas Rápidas de Disponibilidad

**Descripción:**  
Muestra disponibilidad de habitaciones, reservas y eventos en máximo 5 segundos.

**Actor:**  
Cliente del hotel y recepción

**Precondiciones:**  
- Sistema disponible.  
- Datos de reservas actualizados.

**Flujo Principal:**  
1. Cliente consulta disponibilidad online.  
2. Sistema procesa información.  
3. Muestra resultados al cliente en tiempo real.

**Poscondiciones:**  
- Disponibilidad mostrada correctamente.  
- Experiencia del usuario optimizada.

---

## CU-012: Accesibilidad Multiplataforma

### CU-012.1: Acceso desde Diferentes Dispositivos y Navegadores

**Descripción:**  
Permite acceder al portal desde móviles, tabletas, computadoras y navegadores comunes.

**Actor:**  
Clientes

**Precondiciones:**  
- Conexión a internet estable.

**Flujo Principal:**  
1. Usuario accede desde su dispositivo.  
2. El sistema se adapta a la resolución y navegador.  
3. Usuario puede consultar, reservar o administrar información.

**Poscondiciones:**  
- Interfaz funcional y accesible en todos los dispositivos.  
- Experiencia de usuario consistente.

---

## CU-013: Reporte de Servicios Adicionales

### CU-013.1: Generación de Informes de Uso de Servicios

**Descripción:**  
Genera informes sobre solicitudes de servicios adicionales (restaurante, transporte, etc.) para optimizar recursos.

**Actor:**  
Recepción

**Precondiciones:**  
- Registro de solicitudes de servicios adicionales.

**Flujo Principal:**  
1. Usuario solicita informe.  
2. El sistema compila datos de servicios adicionales.  
3. Genera reporte detallado.

**Poscondiciones:**  
- Reporte disponible para análisis.  
- Recursos planificados según demanda.

---

## CU-014: Reporte de Ocupación de Habitaciones

### CU-014.1: Generación de Informe de Ocupación

**Descripción:**  
Genera informe sobre estado de habitaciones (disponibles, reservadas o en mantenimiento).

**Actor:**  
Recepción

**Precondiciones:**  
- Registro actualizado de habitaciones.

**Flujo Principal:**  
1. Usuario solicita informe.  
2. Sistema procesa datos de ocupación.  
3. Muestra o exporta informe de ocupación.

**Poscondiciones:**  
- Informe actualizado y preciso.  
- Gestión de reservas optimizada.

---

## CU-015: Reporte de Uso de Zonas de Eventos y Oficinas

### CU-015.1: Generación de Informe de Uso de Salones

**Descripción:**  
Genera informes sobre uso de salones de eventos y oficinas para planificación de eventos.

**Actor:**  
Recepción

**Precondiciones:**  
- Salones y oficinas registrados.  
- Reservas cargadas.

**Flujo Principal:**  
1. Usuario solicita informe.  
2. El sistema recopila datos de uso.  
3. Genera informe detallado de ocupación y uso.

**Poscondiciones:**  
- Informe disponible para planificación.  
- Datos de uso documentados para gestión futura.