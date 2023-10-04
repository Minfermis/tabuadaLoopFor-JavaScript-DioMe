# Programa de Tabuada Com o Loop For em JavaScript

## Introdução

Este é um programa simples em JavaScript que calcula e imprime a tabuada de um número específico, neste caso, o número 5. O programa usa um loop `for` para gerar a tabuada de 1 a 10 e a formata em "i X num = resultado", onde `i` representa o multiplicador, `num` é o número da tabuada, e `resultado` é o resultado da multiplicação.

## Passo a Passo com Imagens

### Passo 1: Definição da Variável num

- Começamos definindo uma variável chamada `num` e atribuindo o valor 5 `(Mas pode ser qualquer valor)` a ela. Essa variável representa o número para o qual queremos calcular a tabuada.

~~~Javascript
const num = 5;
~~~

### Passo 2: Início do Loop For

- Usamos um loop `for` para percorrer os números de 1 a 10. `i` começa em 1 e continua enquanto `i` for menor ou igual a 10. A cada iteração, `i` é incrementado em 1.

~~~Javascript
for (let i = 1; i <= 10 ; i++){
~~~

### Passo 3: Cálculo do Resultado

- Dentro do loop, calculamos o resultado multiplicando o valor atual de `i` pelo número armazenado na variável `num`. Isso é armazenado na variável `resultado`.

~~~Javascript
const resultado = i * num;
~~~

### Passo 4: Impressão da Tabuada Formatada

- Utilizamos a função `console.log` para imprimir o resultado no formato desejado, com interpolação de strings `${}`. Isso gera uma saída como "i X num = resultado".

~~~Javascript
console.log(`${i} X ${num} = ${resultado}`);
~~~

### Passo 5: Próxima Iteração do Loop

- O loop continua executando enquanto `i` for menor ou igual a 10. A cada iteração, `i` é incrementado, o cálculo é atualizado e a tabuada é impressa.


### Passo 6: Fim do Programa

- Após a última iteração do loop, o programa é concluído.


## Resultado

A execução deste programa produzirá a tabuada do número 5 de 1 a 10 no formato **i**  X  **num** = **resultado**".
~~~Javascript
1 X 5 = 5
2 X 5 = 10
3 X 5 = 15
4 X 5 = 20
5 X 5 = 25
6 X 5 = 30
7 X 5 = 35
8 X 5 = 40
9 X 5 = 45
10 X 5 = 50
~~~
## Exemplo de Saída



Este programa é uma ferramenta simples para aprender e praticar matemática de forma interativa, além de demonstrar o uso de estruturas de repetição em JavaScript.
