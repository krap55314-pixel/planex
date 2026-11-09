# Planetary Analog Explorer (PL.AN.EX)

Busca lugares de la Tierra parecidos a regiones de Marte y la Luna con un índice de similitud ponderado.

- **Tierra**: datos reales ERA5 2015–2024 y Copernicus DEM (vía Open-Meteo), contornos Natural Earth.
- **Marte / Luna**: valores de referencia aproximados de misiones (MOLA, REMS, MEDA, LRO Diviner/LOLA).
- **Globos 3D**: three.js con mosaicos de NASA (Viking MDIM 2.1 + MOLA, LRO WAC + LOLA, Blue Marble + Earth at Night).
- **Motor Python**: `motor_analogos.py` se ejecuta en el navegador con Pyodide 0.26.4 (sin servidor).

Sitio estático: abrí `index.html` desde un servidor web (GitHub Pages, Netlify o `python3 -m http.server`).
Abrirlo con doble clic (`file://`) no carga las texturas ni Python, por restricciones del navegador.

Índice educativo: no es un resultado científico validado.
