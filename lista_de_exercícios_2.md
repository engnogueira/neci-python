# Lista de exercícios 2

O objetivo destes exercícios usando pseudo código é o aprendizado de heuristicas e a prática de criar procedimentos para resolver problemas. Alguns exercícios podem parecer muito distantes da experiência cotidiana, mas fazendo-os você vai adquirindo prática valiosa na criação de procedimentos. 

Para estes exercícios pode ser útil relembrar listas. Listas podem ter outras listas concatenadas ao seu final (posição de maior índice) usando o operador '+'. Por exemplo:

```lst = [1, 5, 2, 9] + [10]                            # lst == [1, 5, 2, 9, 10]```

Portanto para adicionar um dado objeto (numero) numa lista basta coloca-lo entre chaves quadradas e usar o operador '+'.

Podemos tambem usar o comando enquanto ao processar itens sem ter limite de repetições. Por exemplo:

Leia números digitados até entrar uma letra. Para cada número imprima "é primo" se for um numero primo. Imprima "Feito." quando for digitada uma letra.

Vejamos como proceder. Assuma que temos uma função letra(L) que retorna "verdadeiro" se L for letra e "falso" caso contrario. 

Assuma ainda uma função `numero_primo(N)` que retorna "verdadeiro" se N for numero primo e "falso" caso contrario. Então poderia ser assim:

```
n = input()	                       # lê entrada via teclado na variável n

enquanto não for letra(n):

   se numero_primo(n):

           imprime("é primo")

   n = input()                         # le entrada seguinte 

```

Dito isto, vejamos os exercícios.

```ex 2.1: Leia números digitados pelo usuário até êle digitar uma letra. Imprima os mesmos números mas em ordem reversa de sua entrada.```

Para o exercício seguinte assuma que existe uma função `separador(L)` que recebe um caracter L qualquer e retorna  "verdadeiro" se L for pontuação ou whitespace e "falso" caso contrario. Lembre que whitespace é o conjunto que inclui espaço em branco, tabulação, etc.

```ex 2.2: Leia um arquivo dado e percorra seu texto contando o numero de palavras. Imprima esta contagem.```

Vejamos alguns exercícios com strings.

```ex 2.3: Leia um string de digitos dado pelo usuario. Imprima uma lista das letras do string sem repetição de letras.```

```ex 2.4: Adapte o procedimento de ex 2.3 para ser uma função que recebe um string e devolve a lista de caracteres sem repetição. ```

O exercíco seguinte usa a função definida em ex 2.4. Recordemos o conceito de conjunto: um conjunto A é uma coleção de elementos sem repetição. Podemos simular este conceito (só parcialmente, veremos futuramente implementações completas) usando listas onde nenhum elemento é repetido. Os elementos da lista representarão elementos do conjunto.

```ex 2.5: Leia dois strings dados pelo usuário (leia um string e depois leia o outro string). Imprima "conjuntos iguais" se os strings contem as mesmas letras, ignorando repetição. Imprima "conjuntos diferentes" se um dos strings tem letra(s) que não ocorre no outro.```

Para o proximo exercicio vamos relembrar o conceito de subconjunto: um conjunto A é dito ser subconjunto de um conjunto B se e somente se cada elemento do conjunto A também é um elemento do conjunto B. 


```ex 2.6: Leia um string dado pelo usuário. Chame-o de A. Leia outro string dado pelo usuário e chame-o de B. Usando as idéias do exercicio ex 2.5 imprima "A é subconjunto de B" caso isto seja verdadeiro, ou vice-versa.```

Por hoje é só isto. Outros virão depois.
