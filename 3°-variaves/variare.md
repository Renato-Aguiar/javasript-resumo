# Constantes, Variáveis e comentários

### existem formas diferentes de declarar variáveis no javascript
### O que são variáveis javascript ?
* As variáveis são parte essencial do código desenvolvido em javascript. E las armazenam valores manipulados por nossos programas
### Formas de declarar variáveis
* let---let(nome da variável = valor) let idade = 41, a forma correta de ler essa variável e idade recebe 41 
* posso também alterar essa variável (idade = 21) sem usar a palavra let novamente 
### variável que n pode ser reatribuída: const
* const ---- uma constante é criada uma variável que não pode ser alterada, ou seja, seu valor e permanente, não podendo ser alterada durante a execução do script 


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
* motivo do var se diferente do let e q o var usar, é que o var define uma variável globalmente
### Regras para nomear uma variável
* o nome de uma variável não pode começar com número ex (3litros) 
* uma variável deve ser uma única palavra, não da para colocar ex let ano letivo = 20
* certos nomes não podem ser atribuídos ao nome da variável por que eles são reservados para uma palavra-chave da linguagem ex( let var cost... )