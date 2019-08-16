Mais uma vez a variável `musicas` aparece com a seguinte estrutura:

``` javascript
var musicas = [
	{
		id: 1,
		nome: "Believer",
		pontuacao: 8.5
	},
	{
		id: 2,
		nome: "Birds",
		pontuacao: 7.8
	}
]
```


O que nós queremos, como resultado é um novo array chamado `asMelhores`. Esse array tem apenas os elementos com pontuação maior que 8.

Embora existam muitas maneiras de resolvê-lo, é uma excelente momento para exercitar na função `filter` :wink: