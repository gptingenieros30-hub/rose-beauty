# Rose Beauty & Aesthetic

Sitio web de un centro de estética (peluquería, manicure y tratamientos) con catálogo de servicios y reserva de citas con fecha y hora.

- `index.html`: página completa, lista para GitHub Pages o cualquier hosting estático.
- La reserva genera un enlace **Añadir a Google Calendar** (evento prellenado que invita al correo del salón) y un mensaje de **WhatsApp** con el resumen.
- Los datos del salón (nombre, correo, WhatsApp, dirección, horario) y el catálogo de servicios se editan al inicio del `<script>` en `index.html`, en las constantes `SALON` y `SERVICIOS`.
- Publicada como artifact en claude.ai, la misma página agrega una sección **Agenda** visible solo para la dueña, que guarda las citas confirmadas y bloquea esos horarios para los clientes.
