# Constantes, Variáveis e comentários

### exintem formas diferentes de declarar variaveis no javascript
### O que é variáveis javascript ?
* As variasveis são parte essencial do código desenvolvido em javascript. E las armazenam valores qie são manipulados por nossos programas
### Formas de declarar variaveis
* let---let(nome da variavel = valor) let idade = 41, a forma correta de ler essa variavel e idade recebe 41 
* posso tamen alterar essa variavel (idade = 21) sem usar a palavar let novamente 
### variavel que n pode ser reatribuida: const
* const ---- uma costante é criada uma variavel que n pode ser alterada ou seja seu valor e permanete, não podendo ser alterada durante a execução do script 


<script>
    let idade = 23;
console.log(idade)
const ano = 2022;
console.log(ano);
idade = 25;
console.log(idade);
ano = 2023;
console.log(ano);
</script>
### forma antiga
* Em vez de usar let usar var 
var dia = 30
* motivo do var se diferente do let e q o var uasr, é que o var define uma variável globalmente
### Regras para nomer uma variavel
* o nome de uma variavel não pode começar com numero ex (3litros) 
* uma variavel deve ser uma unica palavra, não da para colocar ex let ano letivo = 20
* certos nomes não pode ser atribuidos ao nome da variavel por que eles são reservados para uma palavra chave da linguagem ex( let var cost... )