# Plantillas de video

`clip-95-5/` — clip de 30 s en 4:5 (dato → conteo → orden correcto → pregunta). Cambia textos en `compositions/` y la firma en `compositions/endcard.html`.

La música no se versiona (licencia de catálogo). Antes de renderizar, resuelve una pista propia:
`npx hyperframes media-use resolve --type bgm --intent "..." --project .` y colócala en `assets/music/bed.wav`, o elimina la línea `music-bed` de `index.html`.
