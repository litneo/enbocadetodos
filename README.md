# EN BOCA DE TODOS — versión 1.5

Abra `index.html` desde Chrome o Edge. Los datos se guardan localmente en el navegador con la misma clave de las versiones anteriores (`buen_almuerzo_v1`).

## Cambios de la 1.5
- Resumen de cobros: se muestran exclusivamente **Efectivo** y **QR**. Los registros con otros métodos permanecen en el historial y en el total general; no se reclasifican.
- Vista Comandas: área horizontal más amplia en escritorio, manteniendo la adaptación a celulares.
- Conserva los filtros de reporte por día, mes y año.
- Indicadores, desglose por categoría, detalle de comandas y exportación CSV obedecen al período seleccionado.
- Los reportes de ventas se basan en la **fecha de cobro**; las pendientes se basan en su fecha de creación. Comandas eliminadas no aparecen.

**Importante:** antes de reemplazar la versión, exporte un respaldo JSON desde la anterior. Ejecute desde el mismo navegador y origen para conservar datos; abrir archivos desde otra ruta puede crear un origen distinto según el navegador. No limpie los datos del sitio.

El reporte de efectivo suma los valores de las ventas cobradas, sin sumar el monto recibido antes de entregar cambio.
