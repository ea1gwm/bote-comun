# Bote Común

App PWA para gestionar un **bote común de pareja**: cada persona aporta un % de su sueldo, se registran los gastos del mes y la app calcula cuánto queda y quién debe a quién (reparto proporcional a la aportación).

- **Un solo archivo** autocontenido: [`bote-comun.html`](bote-comun.html) (HTML + CSS + JS vanilla, sin build).
- **Local-first:** funciona 100% offline guardando en `localStorage`. Sincronización opcional en la nube (Firebase) compartiendo un código de pareja.
- **PWA instalable** ("Añadir a pantalla de inicio"), pensada para móvil.

## Funciones

- Aportación proporcional al sueldo y liquidación automática del mes.
- Gastos del mes y gastos fijos recurrentes.
- Sueldo por defecto y override por mes.
- Estadísticas de mes y año (gasto, ahorro, acumulado, por categoría).
- Categorías personalizables.
- Modo claro / oscuro / automático.
- Sincronización en tiempo real entre dos móviles y avisos a la pareja.

## Uso

Abre la app, configura los sueldos en **Ajustes** y empieza a añadir gastos.
Para sincronizar, pon el **mismo código de pareja** en los dos móviles (Ajustes › Sincronización).
