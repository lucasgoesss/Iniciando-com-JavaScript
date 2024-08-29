# JavaScript Exercicio

Este repositório contém uma série de scripts JavaScript básicos que abordam conceitos fundamentais, como variáveis, operadores e tipos de dados. Cada script foi criado com o objetivo de ilustrar operações comuns em JavaScript, como soma, subtração, verificação de tipos de dados, e mais.

## Exercícios

### 1. Exibir uma Mensagem de Alerta
Crie um script que exiba a mensagem `"Hello World!"` em um alerta no navegador.
*/

alert('Hello World!');

/*
### 2. Soma de Duas Variáveis
Declare duas variáveis, some seus valores, e exiba o resultado em um alerta.
*/

const numberOne = 10;
const numberTwo = 15;
const sum = numberOne + numberTwo;
alert(sum);

/*
### 3. Verificar se o Valor é um Número
Declare uma variável e verifique se seu valor é um número. Exiba `"É um número"` ou `"Não é um número"` conforme o caso.
*/

const isNumber = 10;

if (typeof isNumber === 'number') {
    alert('É um número');
} else {
    alert('Não é um número');
}

/*
### 4. Verificar se o Valor é uma String
Declare uma variável e verifique se seu valor é uma string. Exiba `"É uma string"` ou `"Não é uma string"` conforme o caso.
*/

const isString = 'Isso é uma string';

if (typeof isString === 'string') {
    alert('É uma string');
} else {
    alert('Não é uma string');
}

/*
### 5. Verificar se o Valor é um Booleano
Declare uma variável e verifique se seu valor é um booleano. Exiba `"É um booleano"` ou `"Não é um booleano"` conforme o caso.
*/

const isBoolean = true;

if (typeof isBoolean === 'boolean') {
    alert('É um booleano');
} else {
    alert('Não é um booleano');
}

/*
### 6. Subtração de Duas Variáveis
Declare duas variáveis e exiba o resultado da subtração entre elas.
*/

const sub = numberOne - numberTwo;
alert(sub);

/*
### 7. Multiplicação de Duas Variáveis
Declare duas variáveis e exiba o resultado da multiplicação entre elas.
*/

const mult = numberOne * numberTwo;
alert(mult);

/*
### 8. Divisão de Duas Variáveis
Declare duas variáveis e exiba o resultado da divisão entre elas.
*/

const div = numberOne / numberTwo;
alert(div);

/*
### 9. Verificar se o Valor é um Número Par
Declare uma variável e verifique se seu valor é um número par. Exiba `"É um número par"` ou `"Não é um número par"` conforme o caso.
*/

const isEvenNumber = 4;

if (isEvenNumber % 2 === 0) {
    alert('É um número par');
} else {
    alert('Não é um número par');
}

/*
### 10. Verificar se o Valor é um Número Ímpar
Declare uma variável e verifique se seu valor é um número ímpar. Exiba `"É um número ímpar"` ou `"Não é um número ímpar"` conforme o caso.
*/

const isOddNumber = 5;

if (isOddNumber % 2 !== 0) {
    alert('É um número ímpar');
} else {
    alert('Não é um número ímpar');
}

## Licença

Este projeto está sob a licença MIT. Consulte o arquivo [LICENSE](./LICENSE) para obter mais informações.

## Contato

Caso tenha dúvidas ou sugestões, entre em contato:

- **LinkedIn**: [Lucas Goes](https://www.linkedin.com/in/lucasgoesss)
por [Lucas Goes](https://github.com/lucasgoesss)



