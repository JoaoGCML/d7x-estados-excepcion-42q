# Estados de excepción · Américas

Registro de declaratorias de estado de excepción en las Américas (1976–2026): notificadas a organismos internacionales (OEA Art. 27 CADH · ONU Art. 4 PIDCP) y no notificadas reconstruidas de gacetas oficiales y fuentes validadas.

## 🌐 Sitio en vivo (público)

**https://jgcmlestadosexp.pages.dev**

El dashboard es de **acceso público** desde julio 2026 (no requiere login). Se sirve por Cloudflare Pages.

## Este repositorio

Copia dev/de emergencia del dashboard (`index.html`). El despliegue principal se hace por `wrangler pages deploy` (direct upload) — este repo **no** está conectado al deploy de Cloudflare, y su GitHub Pages está desactivado.

Los datos y el pipeline de construcción viven fuera del repo (carpeta local `estados_excepcion/`, ver `PIPELINE.md` allí; regenerar con `./refresh_all.sh`).
