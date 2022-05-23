# javascript.estudo
estudos sobre "Sintaxe Básica em JavaScript"
// aula 1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>meu primeiro</title>
</head>
<body>
  <h1>meu primeiro script</h1>

    <externar script></externar>
    <carregar o script ao final do body></carregar>
  <script src="script.js"></script>

   
</body>
</html>

// tipos primitivos

//boolean
var vOuF = false;
console.log (typeof(vOuF));

//number
var numeroQualquer = 1;
console.log(typeof(numeroQualquer))

// string
var nome = "Karen"
console.log(typeof(nome))
// como declarar essa variaveis
//var
var variavel;
console.log(variavel) // se mandar imprimir ele, volta como "undefined" pq n foi declarado nenhum valor (pode ter seu valor alterado)

var variavel = "Karen"; 
console.log(variavel); // dessa forma ele fica correto, alterando automaticamente ao valor (pode ter seu valor aletado)

var variavel = "Karen"; // ele já altera para outro valor.
variavel= "vitor"
console.log(variavel);
//let
let variavel2 = "1";
console.log(variavel2);
//const não pode ter seu valor alterado, precisa de uma incialização
const constante = '0';
console.log(constante);
//escopo 

var escopoGlobal = 'global';
console.log(escopoGlobal);


function escopoLocal() {
    let escopoLocalInterno = (local) ;
    console.log(escopoLocalInterno);
}
escopoLocal(); 
//atribuicao
var atribuicao = "karen";
//comparacao (deve retorar que é verdadeiro= true)
var comparacao = '0' == 0 ;
console.log(comparacao);
// *comparacao indetidica
var comparacaoidentica = '0' === 0;
console.log(comparacaoidentica);*/

//adicao 
ver adicao = '1 + 1';
console.log(adicao);
//subtracao
ver subtracao 
// potenciacao
var potenciacao = '2 ## 10';
console.log(potenciacao);
//operadores relacionais sempre utlizar:
//(> maior que) (< menor que) (>= maior igual a) (<= menor igual a)
