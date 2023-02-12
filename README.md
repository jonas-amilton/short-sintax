# Estudo-short-sintax

###

````
condição ? valor se verdadeiro : valor se falso
````

<p>
A condição seria o que vamos comparar para o if determinar se é falso ou verdadeiro

No if normal, esta parte fica entre parentes, no ternário não há esta necessidade

Depois o ponto de interrogação funciona como uma pergunta “é verdadeiro?” e caso for, entre na condição seguinte dele executando aquela lógica

Já os dois pontos (:) representa um ‘se for falso’, e caso seja, executa aquela lógica em seguida dele

Então vamos fazer uma comparação:
</p>

````
// if comum
if(1 == 2) {
    console.log('verdadeiro');
} else {
    console.log('falso');
}

// if ternário
1 == 2 ? console.log('veradeiro') : console.log('falso');
````

<p>
A mesma comparação escrita das duas formas, perceba que a execução de ‘falso’ será dada nas duas estruturas

Uma vez que a primeira parte do if ternário representa a condição 1 do if comum, já a segunda parte representa o else

Perceba também que conforme a lógica vai ficando mais complicada, devemos escolher a abordagem comum

Pois o if ternário pode se tornar muito confuso, e em vez de facilitar nossa vida para escrever menos código

Deixar confuso ele, e nos gerar um problema de manutenibilidade

Uma boa ideia seria sempre utilizar a forma comum do if, caso você fique em duvida em qual utilizar

E nunca utilizar apenas para parecer que você sabe muito JavaScript ou deixar mais moderno seu código 😀

Utilize o if ternário em situações simples, a do exemplo é perfeita

Uma comparação bem pequena com respostas direta no código, sem muito mais lógica envolvida
</p>