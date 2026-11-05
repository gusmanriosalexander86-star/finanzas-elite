# Finanzas Élite

Tu dinero personal (sueldo fijo de 500 Bs) y tu tienda como empresa, en una sola página.

- **Inicio:** cuánto te queda del sueldo, cuánto puedes gastar hoy y en la semana, y botones grandes de **+ Gasto mío** y **+ Gasto tienda** (monto con teclado, el tipo es opcional).
- **Tienda:** próximo pago, cierre del mes (subes la ganancia neta de tus ventas una vez al mes), reparto de la ganancia, pagos fijos con lo que te cobraron de verdad en bolivianos, y salud de la tienda.
- **Análisis:** proyección, gastos por semana, por día y por tipo, comparación con el mes anterior y todos los gastos.
- **Ahorro:** alcancía para los días hábiles, sobrante del día, redondeo, metas con foto y lista de deseos (regla de 24 h).
- **Asesor:** puntaje de salud financiera, lo más importante hoy, plan de la semana, diagnóstico, rutina del mes y consejos.
- **Deudores:** a quién le prestaste o fiaste, con botones de Pagó todo y Abono (por QR o efectivo), fecha límite o sin fecha, y botón para escribirle por WhatsApp. Va aparte de tus finanzas.
- **Ajustes** (engranaje en Inicio): sueldo, ahorro diario, pagos fijos, reparto y copia de seguridad.

## Subir a Netlify con GitHub

No necesitas Railway para esto: es una página estática y Netlify la publica gratis.

1. En GitHub crea un repositorio nuevo, por ejemplo `finanzas-elite`.
2. **Add file → Upload files**, arrastra estos 4 archivos (`index.html`, `manifest.webmanifest`, `icon.svg`, `README.md`) y dale **Commit changes**. Tienen que quedar en la raíz, no dentro de una carpeta.
3. En [app.netlify.com](https://app.netlify.com): **Add new site → Import an existing project → GitHub** y elige el repositorio.
4. Deja **Build command** vacío y **Publish directory** vacío (o `.`). Dale **Deploy**.
5. En un minuto tienes tu link. Puedes cambiarle el nombre en *Site configuration → Change site name*.

Cada vez que cambies un archivo en GitHub, Netlify actualiza la página solo.

## En el celular

Abre el link → menú del navegador → **Agregar a la pantalla de inicio**. Queda como una app.

## Importante

- Los datos se guardan en el navegador de tu celular. Usa siempre el mismo teléfono y el mismo navegador.
- Descarga una copia cada mes en **Ajustes → Descargar copia**.
- Trae cargados tus gastos de noviembre 2026 (129 Bs).
