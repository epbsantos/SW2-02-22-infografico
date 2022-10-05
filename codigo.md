# Códigos em sala

Depois de carregar o candidatos.json, segue o acesso dos dois candidados do segundo turno:
```js
cand.candidatos[3]; // Bolsonaro
cand.candidatos[5]; // Lula

// img
'https://divulgacandcontas.tse.jus.br/candidaturas/oficial/2022/BR/BR/544/candidatos/908966/foto.jpeg' // Bolsonaro
'https://divulgacandcontas.tse.jus.br/candidaturas/oficial/2022/BR/BR/544/candidatos/893498/foto.jpg'  // Lula
```

Sugestão de informações no arquivo candidados.json:
```js
cand.candidatos[x].id
cand.candidatos[x].numero
cand.candidatos[x].nomeUrna
cand.candidatos[x].nomeCompleto
cand.candidatos[x].nomeColigacao
```
