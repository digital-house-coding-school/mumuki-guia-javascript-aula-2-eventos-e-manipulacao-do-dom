Vamos construir um carrossel de fotos ... O que você acha?

Como você pode ver, nosso código HTML tem uma tag `<img>` que mostra imagens e duas tags `<button>` para passar as imagens. Cada um desses botões tem um **id** correspondente para ser facilmente identificado.

Não apenas isso, mas no código JS existe um array com 4 URLs com fotos e uma variável `index` que indica qual a foto está sendo exibida na posição 0.

Seu trabalho é completar os eventos que devem acontecer clicando no próximo e no anterior. Abaixo você tem um guia sobre como programar o o botão "próximo". Fica para você imaginar (e fazer) o comportamento do "anterior".

Ao clicar no botão "próximo" deve-se:

> 1. Aumentar o índice da foto mostrada por 1

> 2. Se o novo índice for maior que o número de fotos tiradas, retorne para o índice para 0

> 3. Tire a foto correspondente da matriz de fotos de acordo com o índice atual

> 4. Modifique o atributo `src` da tag` img` para exibir a imagem correta

Sucessos!