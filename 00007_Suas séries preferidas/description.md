Antes de entrar no exercício, aprenderemos a função `split`, nativa do JS.

A função `split` opera com uma String e a separa de acordo com um delimitador.

Por exemplo:

``` javascript

var colorsString = "Azul,Vermelho,Amarelo"

var colorsArray = colorsString.split (",")

```

Este código irá dividir a string em cada ocorrência de uma vírgula e gerar um array com 3 elementos (Azul, Vermelho e Amarelo)

Por que te dizemos isso? Seu código deve fazer o seguinte:

> 1. Peça ao usuário através de `prompt` para escrever suas séries favoritas separadas por vírgulas.

> 2. Usando a função `split`, transforme esse texto em um array de séries

> 3. Para cada série inserida você deve **adicionar** ao elemento `<ul>` um novo `<li>` com o nome da série. Tenha cuidado com o conteúdo do `innerHTML`. Uma boa maneira de resolver isso é escrever:

``` javascript
element.innerHTML = element.innerHTML + novo conteúdo
```

Sucessos!