1. Hair Day 

Hair Day · Reservas en línea para salón de belleza

En producción: [reservapelu.com] · En uso real desde: mediados de 2026

El código fuente es privado porque maneja datos de clientas reales. Con gusto lo muestro en una entrevista.

El problema. El salón agendaba sus citas por WhatsApp y llamadas. Eso generaba citas cruzadas, mensajes a toda hora y tiempo perdido respondiendo lo mismo.

La solución. Una aplicación web donde las clientas eligen el servicio, el día y la hora, y reservan solas. La estilista administra todo desde un panel.

Qué hice. Todo el ciclo, solo: levanté los requerimientos con la dueña del negocio, diseñé la base de datos, programé frontend y backend, y lo desplegué en producción.
Stack. React · Node.js · Express · PostgreSQL · Vercel (frontend) · Railway (API y base de datos) · Hostinger (dominio)

Funcionalidades

• Reserva en línea sin llamar ni escribir.
• Autenticación y panel de administración para gestionar citas.
• [Agregar: cancelaciones, recordatorios, horarios bloqueados, etc.]

Retos técnicos

• Caídas de conexión en producción: la API perdía la conexión con PostgreSQL en Railway. Lo resolví con connection pooling.
• Dominio propio: configuré registros CNAME en Hostinger para servir la API en api.reservapelu.com.

Capturas ![Vista de reserva](docs/reserva.png) ![Panel de administración](docs/panel.png) [Enlace al video demo]
# hairdaycase-study
