# Movimiento Inteligente · Nahuel Cornu

Demo de un sistema de gestión para gimnasios y entrenadores personales. Es un único archivo, `index.html`,
que se abre directo en el navegador, sin instalar nada. Los datos quedan en el navegador (localStorage).

## Qué incluye

- **Dos modos:** entrenador personal (planes de 1, 2 y 3 sesiones semanales, presencial y virtual) y gimnasio completo.
- **Acceso:** validación por QR, NFC, huella o documento, con resultado verde, amarillo o rojo, bitácora y modo tótem.
- **Socios y cuotas:** estados al día, por vencer y vencidos, alertas, deuda de buffet y declaración de salud.
- **Club y WhatsApp:** sellos y premios, tarjeta con QR, cola de mensajes (vencimientos, cumpleaños, reactivación) y pedido de reseña.
- **Agenda y clases:** cupos, reservas y asistencia; sesiones personalizadas y programas de entrenamiento.
- **Buffet:** punto de venta, stock, vencimientos, cuenta corriente.
- **Cobros y facturas:** pagos mixtos, comprobantes internos y libro de ventas para llevar a ARCA.
- **Personal:** fichaje con PIN o NFC (rechaza repetidos en menos de 60 s), turnos, horas y liquidación estimada.
- **Administración:** caja del día, gastos, resultado del mes e informes, con exportación a CSV.
- **Roles:** administrador, supervisor y recepción ven distintas secciones.

## Importante

- Los comprobantes son internos y no tienen validez fiscal. La factura electrónica se emite en ARCA.
- Huella y NFC se simulan en la demo. En producción necesitan un lector conectado y un programa que lo conecte.
- Los datos, teléfonos y precios que trae son de demostración.
