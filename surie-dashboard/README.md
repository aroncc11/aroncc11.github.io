# Surie y el juguete robado: dashboard de validación de diseño

Página estática con las métricas de validación de diseño del prototipo *Surie y el juguete robado*.
Agrupa 19 métricas en 4 preguntas de diseño y muestra la lectura y la decisión de diseño de cada una.

- Juego: https://aroncc.itch.io/surie-y-el-jugete-robado
- Datos en vivo: al abrirse y cada minuto, la página llama a la función `surie_dashboard()` de Supabase, que devuelve solo totales agregados y sin nombres de jugador.
- Respaldo: si la base no responde, muestra el corte del 8 de noviembre de 2026 incrustado en `index.html`.
- Sin dependencias: HTML, CSS y JavaScript. Solo carga dos fuentes de Google Fonts.
