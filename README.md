# CasaDirecta

**Web + sistema de reservas todo-en-uno para casas rurales: reservas directas sin comisión de OTAs.**

🔗 **Demo en vivo:** https://asifer2005.github.io/casadirecta/

## Qué resuelve
Los alojamientos rurales que dependen de Booking/Airbnb pagan un 15-18 % de comisión por cada reserva. CasaDirecta les da una mini-web pública propia y un calendario de reservas directas, con un KPI de **comisión ahorrada**.

## Funciones
- Editor de la mini-web pública del alojamiento (galería, descripción, servicios, precios por temporada).
- Calendario de disponibilidad con estados por día y **anti doble-booking** (detección de solapamiento de fechas).
- Cálculo automático del precio de la estancia según noches y temporada.
- Gestión de reservas con estados (solicitada / confirmada / cancelada) y cobro de señal.
- Importación/exportación **iCal** para sincronizar con Booking/Airbnb.
- Muro de suscripción (Free / Pro / Business) con checkout simulado.

## Tecnología
Aplicación web de un solo archivo (`index.html`), HTML + CSS + JavaScript _vanilla_, sin build. Datos en `localStorage`. Lógica de fechas en hora local (rangos `[entrada, salida)` y detección de solapamiento).

---
Proyecto de **Asier Fernández** · [Más proyectos](https://asifer2005.github.io/sitio-web/)
