# Landing page — referência de design

Este é um protótipo de design criado em uma ferramenta de design visual e
exportado como uma página independente. Trate-o como um PROTÓTIPO DE
REFERÊNCIA, e não como código de produção: o HTML e os estilos inline
guardam os valores exatos do design — cores, tamanhos de fonte,
espaçamentos, arredondamentos, sombras e layout —, que uma implementação
deve reproduzir fielmente com seus próprios componentes e seu próprio
sistema de estilos, em vez de copiar tudo como está.

## Conteúdo

- `Main.dc.html` — a prancheta (um Design Component: um modelo `<x-dc>`
  mais uma pequena classe de lógica). Os valores a reproduzir estão nos
  atributos `style="…"` inline e no bloco `<helmet><style>`.
- `support.js`, `vendor/react*.js` — o código que monta o componente no
  navegador; não fazem parte do design.

## Como visualizar

Sirva a pasta por um servidor local (por exemplo, `python3 -m http.server`)
e abra `Main.dc.html`; alguns navegadores bloqueiam os scripts quando a
página é aberta direto pelo arquivo (file://).
