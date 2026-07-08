# Assets — Logo Fragmentos

A top bar da home usa o logo em `fragmentos-logo.svg`.

**O ficheiro atual é um placeholder** (recriação simples do wordmark). Substitui-o pelo
**logo oficial** do Fragmentos, mantendo o mesmo nome e caminho:

```
docs/assets/fragmentos-logo.svg
```

Notas:
- Preferir **SVG** (escala sem perder qualidade). Se só tiveres PNG de alta resolução,
  coloca-o como `fragmentos-logo.png` e avisa — troco o `src` no index.html
  (ou muda tu a extensão em `<img class="nav-logo" src="assets/fragmentos-logo.svg">`).
- O logo é apresentado a `height:48px` (largura automática). Um SVG com fundo transparente
  fica perfeito sobre a barra branca.
- Só o index (home) usa este logo. As top bars dentro dos dashboards não foram alteradas.
