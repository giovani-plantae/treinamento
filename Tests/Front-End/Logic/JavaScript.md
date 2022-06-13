# Desafio JavaScript
 
## Regras
- Cada solução deve ficar em um arquivo js nomeado com o nome da função;
- Coloque o enunciado da questão no início de cada arquivo js como um comentário;
- Nomeie corretamente o nome das funções e dos parâmetros de acordo com o enunciado;
- Tente reaproveitar funções quando for possível;
- Lembre de identar corretamente o código;
- Faça comentários linha a linha explicando o que cada linha do seu código está fazendo;
- A solução final deve ser entregue em um zip, contendo um html carregando todos os arquivos js;
 
 
## Questões
 
### NULL
 
#### isNull
Faça uma função chamada `isNull` que recebe um parâmetro chamado `val` e retorna um `boolean` indicando se é nulo;
```js
null    => true
0       => false
1       => false
''      => false
```
 
 
### BOOLEAN
 
#### isBoolean
Faça uma função chamada `isBoolean` que recebe um parâmetro chamado `val` e retorna um `boolean` indicando se o parâmetro é do tipo boolean;
```js
true    => true
false   => true
1       => false
null    => false
```
 
#### booleanResponse
Faça uma função chamada `booleanResponse` que recebe um parâmetro chamado `val` do tipo `boolean` e retorna uma `string` com valor `sim` para true e `não` para false;
```js
true    => 'sim'
false   => 'não'
```
 
#### invertBoolean
Faça uma função chamada `invertBoolean` que recebe um parâmetro chamado `val` do tipo `boolean` e retorna o boolean invertido;
```js
true    => false
false   => true
```
 
 
### NUMBER
#### isNumber
Faça uma função chamada `isNumber` que recebe um parâmetro chamado `val` e retorna um `boolean` indicando se o parâmetro é do tipo `number`;
```js
1       => true
0       => true
true    => false
null    => false
'1'     => false
```
 
#### isGreaterThan10
Faça uma função chamada `isGreaterThan10` que recebe um parâmetro chamado `val` do tipo `number` e retorna um `boolean` indicando se o número é maior que 10;
```js
15 => true
05 => false
10 => false
```
 
#### isLowerThan20
Faça uma função chamada `isLowerThan20` que recebe um parâmetro chamado `val` do tipo `number` e retorna um `boolean` indicando se o número é menor que 20;
```js
15 => true
25 => false
20 => false
```
 
#### isBetween10and20
Faça uma função chamada `isBetween10and20` que recebe um parâmetro chamado `val` do tipo `number` e retorna um `boolean` indicando se o número é maior que 10 e menor que 20;
```js
15 => true
05 => false
20 => false
25 => false
```
 
#### isMultipleOf2
Faça uma função chamada `isMultipleOf2` que recebe um parâmetro chamado `val` do tipo `number` e retorna um `boolean` indicando se o número é um multiplo de 2;
```js
02 => true
08 => true
03 => false
05 => false
```
 
#### isMultipleOf5
Faça uma função chamada `isMultipleOf5` que recebe um parâmetro chamado `val` do tipo `number` e retorna um `boolean` indicando se o número é um múltiplo de 5;
```js
05 => true
80 => true
47 => false
52 => false
```
 
#### isEven
Faça uma função chamada `isEven` que recebe um parâmetro chamado `val` do tipo `number` e retorna um `boolean` indicando se o parâmetro é par;
```js
5 => false
2 => true
```
 
#### isGreaterThan100AndMultipleOf3
Faça uma função chamada `isGreaterThan100AndMultipleOf3` que recebe um parâmetro chamado `val` do tipo `number` e retorna um `boolean` indicando se o numero é maior que 100 e também é um múltiplo de 3;
```js
300 => true
306 => true
030 => false
036 => false
```
 
#### invertSign
Faça uma função chamada `invertSign` que recebe um parâmetro chamado `val` do tipo `number` e retorna um `number` que é o próprio parâmetro com o sinal de positivo/negativo invertido;
```js
1   => -1
-2  => 2
0   => 0
```
 
#### isPositiveAndNegative
Faça uma função chamada `isPositiveAndNegative` que recebe dois parâmetros chamados `val1` e `val2` do tipo `number` e retorna um `boolean` true caso um número for negativo e o outro positivo, não importa a ordem;
```js
(-1, 2)     => true
(7, -5)     => true
(2, 5)      => false
(-5, -5)    => false
```
 
#### sumNumbers
Faça uma função chamada `sumNumbers` que recebe dois parâmetros chamados `val1` e `val2` do tipo `number` e retorna um `number` com a soma dos parâmetros;
```js
(2, 4)     => 6
(2, -2)    => 0
```
 
 
#### subNumbers
Faça uma função chamada `subNumbers` que recebe dois parâmetros chamados `val1` e `val2` do tipo `number` e retorna um `number` com a subtração dos parâmetros;
```js
(5, 2)     => 3
(2, -3)    => 5
```
 
#### mulNumbers
Faça uma função chamada `mulNumbers` que recebe dois parâmetros chamados `val1` e `val2` do tipo `number` e retorna um `number` com a multiplicação dos parâmetros;
```js
(2, 4)     => 8
```
 
#### divNumbers
Faça uma função chamada `divNumbers` que recebe dois parâmetros chamados `val1` e `val2` do tipo `number` e retorna um `number` com a divisão dos parâmetros;
```js
(10, 5)     => 2
```
 
#### powNumbers
Faça uma função chamada `powNumbers` que recebe dois parâmetros chamados `base` e `exp` do tipo `number` e retorna um `number` com a exponenciação dos parâmetros;
```js
(2, 2)     => 4
(2, 5)     => 32
```
 
#### halfNumber
Faça uma função chamada `halfNumber` que recebe um parâmetro chamado `val` do tipo `number` e retorna um `number` com a metade do valor do parâmetro;
```js
10  => 5
```
 
#### doubleNumber
Faça uma função chamada `doubleNumber` que recebe um parâmetro chamado `val` do tipo `number` e retorna um `number` com o dobro do valor do parâmetro;
```js
2   => 4
```
 
#### 50PctNumber
Faça uma função chamada `50PctNumber` que recebe um parâmetro chamado `val` do tipo `number` e retorna um `number` equivalente a 50% do valor do parâmetro;
```js
8   => 4
```
 
#### increaseNumberBy10Pct
Faça uma função chamada `increaseNumberBy10Pct` que recebe um parâmetro chamado `val` do tipo `number` e retorna um `number` equivalente ao valor do parâmetro + 10%;
```js
10  => 11
```
 
#### decreaseNumberBy10Pct
Faça uma função chamada `decreaseNumberBy10Pct` que recebe um parâmetro chamado `val` do tipo `number` e retorna um `number` equivalente ao valor do parâmetro - 10%;
```js
10  => 9
```
 
#### biggestNumber
Faça uma função chamada `biggestNumber` que recebe dois parâmetros chamados `val1` e `val2` do tipo `number` e retorna um `number` que é o parâmetro de maior valor;
```js
(10, 15)     => 15
```
 
#### smallestNumber
Faça uma função chamada `smallestNumber` que recebe dois parâmetros chamados `val1` e `val2` do tipo `number` e retorna um `number` que é o parâmetro de menor valor;
```js
(10, 15)     => 10
```
 
#### biggestNumberFrom3
Faça uma função chamada `biggestNumberFrom3` que recebe três parâmetros chamados `val1`, `val2` e `val3` do tipo `number` e retorna um `number` que é o parâmetro de maior valor;
```js
(10, 15, 20) => 20
```
 
#### isPrime
Faça uma função chamada `isPrime` que recebe um parâmetro chamado `val` do tipo `number` e retorna um `boolean` indicando se o parâmetro é um número primo;
```js
0       => false
1       => false
2       => true
5       => true
```
 
### STRING
#### isString
Faça uma função chamada `isString` que recebe um parâmetro chamado `val` e retorna um `boolean` indicando se o parâmetro é do tipo string;
```js
'teste'     => true
'1'         => true
1           => false
true        => false
null        => false
```
 
#### isLengthGreaterThan5
Faça uma função chamada `isLengthGreaterThan5` que recebe um parâmetro chamado `val` do tipo `string` e retorna um `boolean` indicando se o comprimento da string é maior que 5;
```js
'testes'     => true
'teste'      => false
'ok'         => false
```
 
#### isLengthLowerThan10
Faça uma função chamada `isLengthLowerThan10` que recebe um parâmetro chamado `val` do tipo `string` e retorna um `boolean` indicando se o comprimento da string é menor que 10;
```js
'test'         => true
'test-lower'   => false
'test-greater' => false
```
 
#### isLengthBetween10and20
Faça uma função chamada `isLengthBetween10and20` que recebe um parâmetro chamado `val` do tipo `string` e retorna um `boolean` indicando se o comprimento da string é maior que 10 e menor que 20;
```js
'testes'       => false
'test-lower'   => false
'test-greater' => true
```
 
#### concatString
Faça uma função chamada `concatString` que recebe dois parâmetros chamados `val1` e `val2` do tipo `string` e retorna uma `string` com a concatenação dos dois parâmetros separados por um espaço;
```js
('test', 'ok')  => 'test ok';
('test', ' ')   => 'test  ';
```
 
#### countVowels
Faça uma função chamada `countVowels` que recebe um parâmetro chamado `val` do tipo `string` e retorna um `number` com a contagem das vogais;
```js
'test'      => 1
'ok'        => 1
'Plantae'   => 3
```
 
#### repeatString
Faça uma função chamada `repeatString` que recebe um parâmetro chamado `text` do tipo `string` e uma chamada `n` do tipo `number` e retorna uma `string` que é o parâmetro `text` repetido `n` vezes;
```js
('ok', 4)       => 'okokokok'
('test', 2)     => 'testtest'
```
 
#### shuffleString
Faça uma função chamada `shuffleString` que recebe um parâmetro chamado `text` do tipo `string` e retorna uma `string` com o valor do parâmetro "embaralhado".
```js
'Plantae'   => 'aelatnP'
'ok'        => 'ko'
```
 
#### wordReverse
Faça uma função chamada `wordReverse` que recebe um parâmetro chamado `text` do tipo `string` contendo várias palavras separadas por espaço e retorne uma `string` com as palavras invertidas de trás para frente;
```js
'Hello World' => 'World Hello'
```
 
#### extractNumber
Faça uma função chamada `extractNumber` que recebe um parâmetro chamado `val` do tipo `string` e retorna um `number` extraindo/eliminando todos os caracteres que não forem numéricos;
```js
'oo'    => NaN
'57o'   => 57
```
 
#### cleanExtraSpaces
Faça uma função chamada `cleanExtraSpaces` que recebe um parâmetro chamado `val` do tipo `string` com várias palavras separadas por um ou mais espaços e retorna uma `string` removendo excessos de espaços;
```js
'Hello    World'                    => 'Hello World'
'Plantae  Gestão      Agrícola'     => 'Plantae Gestão Agrícola'
```
 
#### stringWrap
Faça uma função chamada `stringWrap` que recebe um parâmetro chamado `text` do tipo `string` e outro parâmetro chamado `wrapper` do tipo `string` e retorna uma `string` que é o parâmetro `text` "empacotado" no meio de dois parâmetros `wrapper`;
```js
('Teste', '*')      => '*Teste*';
('Teste', '<span>') => '<span>Teste<span>';
```
 
#### removeEdges
Faça uma função chamada `removeEdges` que recebe um parâmetro chamado `text` do tipo `string` e retorna a `string` sem o primeiro e último caractere;
```js
('*Teste*')      => 'Teste';
('Teste')        => 'est';
```
 
#### stringInitials
Faça uma função chamada `stringInitials` que recebe um parâmetro chamado `text` do tipo `string` contendo várias palavras e retorna uma `string` extraindo apenas o primeiro caractere de cada palavra em caixa alta;
```js
'Plantae gestão agrícola' => 'PGA';
```
 
### ARRAY
 
#### arrayResize
Faça uma função chamada `arrayResize` que recebe um parâmetro chamado `list` do tipo `array` e outro parâmetro chamado `size` do tipo `number` e retorna um `array` contendo os primeiros itens do parâmetro `list` limitados pelo tamanho do parâmetro `size`;
```js
([1, 10, 8, 15, 4, 3, 2], 5)   => [1, 10, 8, 15, 4]
([1, 10, 'ok', 8, 3, 2], 3)    => [1, 10, 'ok']
```
 
#### getArrayRange
Faça uma função chamada `getArrayRange` que recebe dois parâmetros chamados `begin` e `end` do tipo `number` e retorna um `array` com a sequência de números entre os dois parâmetros informados de forma inclusiva;
```js
(0, 4)  => [0, 1, 2, 3, 4]
(4, -2) => [4, 3, 2, 1, 0, -1, -2]
```
 
#### arraySum
Faça uma função chamada `arraySum` que recebe um parâmetro chamado `list` do tipo `array` e retorna um `number` que é a soma de todos os números do array, outros tipos além de números enviados junto com a lista devem ser ignorados e removidos do cálculo;
```js
[1, 3, 4]      => 8
[3, 'ok', 4]   => 7
```
 
#### arrayAvg
Faça uma função chamada `arrayAvg` que recebe um parâmetro chamado `list` do tipo `array` e retorna um `number` que é a média de todos os números do array, outros tipos além de números enviados junto com a lista devem ser ignorados e removidos do cálculo;
```js
[7, 5, 6, 8]    => 6.5
[18, 'ok', 4]   => 11
```
 
#### filterOddNumbers
Faça uma função chamada `filterOddNumbers` que recebe um parâmetro chamado `list` do tipo `array` e retorna um `array` apenas com os números ímpares do parâmetro `list`, outros tipos além de números enviados junto com a lista devem ser ignorados e removidos do cálculo;
```js
[1, 5, 6, 7, 8]    => [1, 5, 7]
```
 
#### groupByOddEven
Faça uma função chamada `groupByOddEven` que recebe um parâmetro chamado `list` do tipo `array` e retorna um `object` com duas chaves, uma chamada `odd` contendo um `array` com os números ímpares e outra chave chamada `even` com os números pares, outros tipos além de números enviados junto com a lista devem ser ignorados e removidos do cálculo;
```js
[1, 2, 3, 4, 5, 6, 7] =>
{
    odd: [1, 3, 5, 7],
    even: [2, 4, 6]
}
```
 
#### groupByInitials
Faça uma função chamada `groupByInitials` que recebe um parâmetro chamado `list` do tipo `array` e retorna um `object` com as `strings` agrupadas pela letra inicial, outros tipos além de strings enviados junto com a lista devem ser ignorados e removidos;
```js
['Plantae', 'Gestão', 'Agrícola', 'Análise', 'Solo', 'Plantas', 'Armazenagem'] =>
{
    a: ['Agrícola', 'Análise', 'Armazenagem'],
    g: ['Gestão'],
    p: ['Plantae', 'Plantas']
    s: ['Solo']
}
```
 
 
 
### OBJECT > DATE
 
#### currentDate
Faça uma função chamada `currentDate` que não recebe parâmetros e retorna a data atual no formato: `DD/MM/YYYY`;
```js
()  => `24/02/2022`
```
 
#### isLeapYear
Faça uma função chamada `isLeapYear` que recebe um parâmetro chamado `date` do tipo `Date` e retorna um `boolean` indicando se o ano for bisexto;
```js
2022    => false
2020    => true
1122    => true
400     => true
```