# Introdução a Programação com Javascript

> Alguma vez na vida você já se perguntou como sites, aplicativos e outros programas são feitos?

Neste minicurso vamos responder essa pergunta e outras, além de aprender um pouco sobre programação com a linguagem de programação Javascript e suas aplicações.

Este Material Foi desenvolvido para o Laboratório de Avaliação de Desempenho Aquático (LADA) da Universidade do Estado do Rio Grande do Norte (UERN) como forma de agregar valor a comunidade.

___
## Por que Javascript?

Segundo  site da [Tiobi (Novembro de 2020)](https://www.tiobe.com/tiobe-index/), o Javascript é uma das 10 linguagens de programção mais utilizadas no mundo!

O Javascript é utilizado em diversas aplicações, a mais comum é no Navegador através da execução de *scripts* de páginas HTML e validações de formulários. Também é possível utilizar ele para o desenvolvimento de *scripts*, programas em Arduino, aplicativos *mobile*, aplicativos web, aplicações Desktop e até mesmo no desenvolvilmento de Jogos!

Vamos executar o nosso primeiro código!

```javascript
// tente no seu navegador
console.log("HELLO WORD")

// OU

alert("HELLO WORD")
```
___
## Lógica de programação: definições e conceitos
>Lógica de programação é o modo como se escreve um programa de computador, um algoritmo. Um algoritmo é uma sequência de passos para se executar uma função. Um exemplo de algoritmo, fora da computação, é uma receita de bolo.

>Na receita, devem-se seguir os passos para o bolo ficar pronto e sem nenhum problema. Na informática, os programadores escrevem as "receitas de bolo" (algoritmos) de modo que o computador leia e entenda o que deve ser feito, ao executar o algoritmo. Para isto é necessário uma linguagem de programação.

[InfoEscola (Novembro de 2020)](https://www.infoescola.com/informatica/logica-de-programacao/)

___
## Estrutura e fases de um algoritmo
* Declaração de variáveis
* Bloco de execução

e como fases temos:
* Execução
* Processamento
* Resultado
___
##  Variáveis, constantes e tipos de dados

```javascript
var x, y, z;       // Declaradas
x = 5; y = 6;      // Atribuídas
z = x + y;         // computadas

console.log(x,y,z)
```

#### Valores
* Valores fixos
* Valores variáveis

```javascript
const a = 1
a = 1      // irá gerar um erros

console.log(a)
```

#### Tipos
* Númericos
* *String*
* Objetos

#### Palavras reservadas
```Javascript
const a;
var b;
let c;
...
```

#### Comentários
```Javascript
var x = 5;   // será executado
// var x = 6;   não será executado
```

___
## Operadores

### Aritméticos

| Operador | Descrição                   |
|----------|-----------------------------|
| +        | Adição                      |
| -        | Subtração                   |
| *        | Multiplicação               |
| **       | Exponenciação (ES2016)      |
| /        | Divisão                     |
| %        | Módulo (Division Remainder) |
| ++       | Incremento                  |
| --       | Decremento                  |

### Relacionais

| Operador | Examplo | Equivale a |
|----------|---------|------------|
| =        | x = y   | x = y      |
| +=       | x += y  | x = x + y  |
| -=       | x -= y  | x = x - y  |
| *=       | x *= y  | x = x * y  |
| /=       | x /= y  | x = x / y  |
| %=       | x %= y  | x = x % y  |
| \**=      | x \**= y | x = x ** y |

### Comparação
| Operador | Descrição                         |
|----------|-----------------------------------|
| ==       | igual a                           |
| ===      | igual a E mesmo tipo              |
| !=       | diferente                         |
| !==      | valor diferente OU tipo diferente |
| >        | maior que                         |
| <        | menor que                         |
| >=       | maior que ou igual a              |
| <=       | menor que ou igual a              |
| ?        | operador ternário                 |

### Lógicos
| Operador | Descrição |
|----------|-----------|
| &&       | E         |
| \|\|     | OU        |
| !        | NEGAÇÃO   |

___
## Estruturas de decisão

```javascript
var idade = prompt("Qual a sua idade?");

if(idade >= 18){
  alert("Seu voto é obrigatório");
}else if(idade > 16){
  alert("Seu voto é optativo");
}else{
  alert("Não pode votar");
}
```

___
## Estruturas de repetição ou iteração


### For
```javascript
var i;
for(i = 1; i <= 10; i++){
  console.log(i * 10)
}
```

### While
```javascript
var i;
for(i = 1; i <= 10; i++){
  console.log(i * 10)
}
```
### Do while
```javascript
var i;
i = 1;
do {
  console.log(i*10);
  i++;
} while(i <= 10);
```
___
## Cursos e outros materiais
* http://code.org
* http://codecademy.com
* http://python.org.br
* http://cursoemvideo.com.br
* https://pt.khanacademy.org/computing/computer-programming
