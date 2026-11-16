# VIGIA · La llama que no se ve
**Equipo TECH-UNJBG · Tacna, Perú** — NASA Space Apps Challenge 2026 · *Flame in Freefall*

VIGIA es un panel con inteligencia artificial que resume, clasifica e interpreta los experimentos de combustión de la NASA en microgravedad (base de datos PSI) y detecta un riesgo oculto: en el espacio una llama puede desaparecer a la vista y seguir ardiendo. Con datos reales de PSI-117, la llama visible de una gota de n-heptano se apaga a los 12.8 s, pero la combustión continúa hasta los 45.8 s.

| Página | Contenido |
|---|---|
| `index.html` | Presentación + simulación Tierra vs espacio con datos NASA |
| `dashboard.html` | Panel completo: ranking y catálogo de investigaciones, 674 ensayos, verificación de extinción, vacíos de datos |
| `simulador.html` | Simulador interactivo (gota 3D, propagación, cabina, atlas FLEX) |

## Publicar en GitHub Pages
1. Crea un repositorio público y sube **el contenido de esta carpeta**.
2. Settings → Pages → *Deploy from a branch* → `main` / `(root)` → Save.
3. El sitio queda en `https://<usuario>.github.io/<repositorio>/` con HTTPS.

## Seguridad y privacidad
- Sitio 100 % estático: sin formularios, sin cuentas, sin cookies, sin rastreadores y sin conexiones a servidores externos.
- `index.html` declara una política de seguridad de contenido (CSP) que solo permite recursos del propio sitio.
- No contiene datos personales. El video del mechero está recortado a la llama y sin audio.
- Usa el correo *noreply* de GitHub para tus commits (Settings → Emails → "Keep my email address private").

## Fuentes
NASA Physical Sciences Informatics (PSI): PSI-117, PSI-69 FLEX, PSI-39 CFI, PSI-159 ACME CFI-G, PSI-101 SAME-R, PSI-98 SAFFIRE-I. BASS-II: Zhao et al. 2015 (NTRS 20150008962). Imagen de fondo: NASA. Lo marcado como "simulación" o "estimado" no es dato medido.
