# Demo interactivo: resonancia de próstata con IA (vista previa)

Página de proyecto de un **prototipo de investigación** de la Universidad de Valparaíso (Proyecto VIU 2026). Contiene un demo que muestra, sobre cuatro estudios públicos, la salida de modelos de segmentación de glándula, zonas y focos sospechosos.

> **Aviso.** Prototipo de investigación sin certificar. No es un dispositivo médico y no debe usarse para diagnóstico ni decisiones clínicas. Los resultados del demo son ilustrativos.

## Qué hay aquí
- `index.html` y `assets/`: sitio estático (sin servidor). Funciona también abriendo `index.html` en el navegador.
- Los resultados del demo están **precalculados**; los modelos no se ejecutan en el navegador.

## Datos y licencias
- **Imágenes:** recortes de estudios del *PI-CAI Public Training and Development Dataset* (Saha et al., Zenodo, doi:10.5281/zenodo.6624726), licencia **CC BY-NC 4.0** (uso no comercial, con atribución). Las superposiciones son salidas de los modelos del proyecto. Estos estudios forman parte de los datos de entrenamiento de los modelos, por lo que el demo no estima desempeño.
- **Tipografías:** Fraunces, Source Sans 3 y JetBrains Mono, licencia SIL OFL 1.1 (ver `assets/fonts/LICENSE-*.txt`).
- **Código y marca de la página:** licencia por definir por los autores.
