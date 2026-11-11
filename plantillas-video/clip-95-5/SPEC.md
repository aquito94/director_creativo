GOAL:    un decisor (CFO/COO) se detiene, entiende que el 95% de los pilotos de IA no mueve el P&L y comenta por dónde empezó su empresa.
OUTPUT:  HyperFrames, 1080 x 1350 (4:5, LinkedIn + feed Instagram), 30 fps
TIME:    30 s x 30 fps = 900 frames
LOOK:    ground #F3F2EE plano sin textura; ink #121212; off #D6D5CE; texto secundario #5A5A55;
         acento verde #0B8A5F SOLO en los 5 pilotos sobrevivientes y en "la IA" del claim.
         Display Inter 900, cifras 220 px tabular-nums, titulares 76-112 px tracking -3%; secundario Inter 700 34-48 px.
         Medio: tablero de 100 casillas de 52 px, gap 12 px. Sin sombras, sin grano, sin viñeta.
OBJECTS: los pilotos = casillas cuadradas ink que se "apagan" a gris; los 5 que quedan se vuelven bloques verdes de 110 px.
MOTION:  entrada de texto = wipe clip-path izquierda->derecha 0.35 s power3.out; movimiento = power3.inOut 0.9 s;
         apagado de casilla 0.12 s; pulsos scale 1->1.25->1 en 0.3 s.
SHOTS:
  0-2.4    grilla 100 encendida + "100 / pilotos de IA generativa" (thumbnail)
  2.4-7.6  95 casillas se apagan acelerando; el contador baja 100->5. riser
  7.7-10.6 "95% / sin impacto medible en el P&L" + fuente MIT NANDA 2025. impacto
  10.6-13.2 los 5 se vuelven verdes. "El problema no es el modelo". pop
  13.2-15  "Es el orden"; los 5 viajan a una columna y crecen. whoosh
  15-17.8  bloque superior "IA — Donde casi todos empiezan"
  17.8-18.7 IA cae al 4to lugar; los demás suben (movimiento héroe). whoosh
  18.9-22.9 Proceso / Costo / Métrica / IA / P&L con su pregunta, uno por segundo. ticks
  23.6-24.6 cascada de pulsos hasta P&L (payoff). pop
  24.6-27  claim "Primero el costo / Después, la IA"
  27-30    "¿Tu empresa empezó por la IA o por el proceso?" + Genesis Rios
BANNED:  fondo oscuro, glow, partículas, gradientes, serif + mono labels, todo centrado, fade+slide up, tres tarjetas, logo en esquina, texto moviéndose mientras se lee.
QA:      1.0 (thumbnail legible), 6.0 (conteo a mitad), 9.0 (dato + fuente), 12.0 (5 verdes), 16.5, 23.0 (columna completa), 26.0, 29.5.
