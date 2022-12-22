## display: block vs display: inline

- Como as caixxas se comportam em relação às outras caixas
- Comportamento externo das caixas

**block**
Ocupa toda a linha, colocando o próximo elemento abaixo desse

width e height são respeitados                 

padding, margin, border irão funcionar normalmente.

**inline**

Elemento ao lado do outro

width e height não funcionam 

Somente valores horizontas de margin, paddind e border

Exemplos

block: `<p> <div <section>`, todos os headings `<h1><h2>...` // a maioria é block
inline: `<a> <strong> <span> <em>`