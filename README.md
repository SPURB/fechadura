Autenticação de apis do portal gestaourbanasp.

# importante
Solicite a `chave.js` e o valor de `tipo` com devspurbanismo ou smul/atic. 

# instalação
```bash
npm i @spurb/fechadura
```

# como usar
```javascript
var fechadura = require('@spurb/fechadura')
var chave = {
	3: "Valentina",
	6: "Arthur",
	9: "Helena",
	12: "Heitor",
	15: "Manuela",
	18: "Lorenzo",
	21: "Laura",
	24: "Luiza",
	27: "Gabriel",
	30: "Benjamin",
	33: "Lívia",
	36: "Maria",
	39: "Livia",
	42: "Giovanna",
	45: "Guilherme",
	48: "Nicolas",
	51: "Isadora",
	54: "Beatriz",
	57: "Samuel",
	60: "Henrique"
}
// ou
// var chave = require('chave.js')

console.log(fechadura(chave, 'nome'))

```