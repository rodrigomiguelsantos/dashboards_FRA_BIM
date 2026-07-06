# Fontes — Museo Sans (self-hosted)

Os dashboards usam **Museo Sans**, carregado a partir desta pasta via `@font-face`.
O Museo Sans é uma fonte comercial (exljbris/Adobe) — **não** está incluída no repositório.
Coloca aqui os teus ficheiros licenciados com **exatamente estes nomes**:

| Peso usado no site        | Ficheiro em uso            | Estado |
|---------------------------|----------------------------|--------|
| Corpo de texto (100)      | `MuseoSans-100.ttf`        | ✅ em uso |
| Títulos (300)             | `MuseoSans-300.ttf`        | ✅ em uso |
| Títulos grandes (500)     | `MuseoSans-500.otf`        | ✅ em uso (normal, não-itálico) |
| Ênfase forte (700)        | `MuseoSans-700.otf`        | ✅ em uso (normal, não-itálico) |

Notas:
- Os quatro pesos estão presentes em **normal** (upright). O CSS aponta diretamente
  para cada ficheiro (`.ttf` para 100/300, `.otf` para 500/700) — sem pedidos falhados.
- O GitHub Pages é sensível a maiúsculas/minúsculas: os nomes têm de ser exatamente
  `MuseoSans-100.ttf`, `MuseoSans-300.ttf`, `MuseoSans-500.otf`, `MuseoSans-700.otf`.
- Versões itálicas (500/700 Italic) e o duplicado do 300 foram removidos por não serem usados.
- Para otimizar (ficheiros mais leves), podes converter para `woff2` em https://transfonter.org
  e depois é só atualizar as extensões nos `@font-face` dos 3 HTML.
- `woff2` é o mais leve e recomendado. Se só tiveres `.otf`/`.ttf`, converte em
  https://cloudconvert.com ou https://transfonter.org (mantém os nomes acima).
- Enquanto os ficheiros não estiverem cá, o site usa o fallback: Inter → Segoe UI → sistema.
- Estes ficheiros são servidos publicamente pelo GitHub Pages — confirma que a tua
  licença permite web embedding/self-hosting antes de fazer commit.
