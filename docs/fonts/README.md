# Fontes — Museo Sans (self-hosted)

Os dashboards usam **Museo Sans**, carregado a partir desta pasta via `@font-face`.
O Museo Sans é uma fonte comercial (exljbris/Adobe) — **não** está incluída no repositório.
Coloca aqui os teus ficheiros licenciados com **exatamente estes nomes**:

| Peso usado no site        | Ficheiro esperado (qualquer um dos formatos) | Estado |
|---------------------------|----------------------------------------------|--------|
| Corpo de texto (100)      | `MuseoSans-100.woff2` · `.ttf`               | ✅ presente (`.ttf`) |
| Títulos (300)             | `MuseoSans-300.woff2` · `.ttf`               | ✅ presente (`.ttf`) |
| Títulos grandes (500)     | `MuseoSans-500.woff2` · `.ttf`               | ⚠️ em falta — cai para o peso 300 |
| Ênfase forte (700, opc.)  | `MuseoSans-700.woff2` · `.ttf`               | ⚠️ em falta (opcional) |

Notas:
- O browser escolhe automaticamente o primeiro formato disponível (`woff2` > `ttf`).
  Basta colocar **um** formato por peso, desde que o nome esteja **exatamente** correto
  (o GitHub Pages é sensível a maiúsculas/minúsculas: `MuseoSans-500.ttf`, não `MUSEOSANS-500.TTF`).
- Falta o peso **500** (títulos grandes / números-chave / valores): enquanto não existir,
  esse texto é renderizado no peso 300. Adiciona `MuseoSans-500.ttf` para o efeito pretendido.
- `woff2` é o mais leve e recomendado. Se só tiveres `.otf`/`.ttf`, converte em
  https://cloudconvert.com ou https://transfonter.org (mantém os nomes acima).
- Enquanto os ficheiros não estiverem cá, o site usa o fallback: Inter → Segoe UI → sistema.
- Estes ficheiros são servidos publicamente pelo GitHub Pages — confirma que a tua
  licença permite web embedding/self-hosting antes de fazer commit.
