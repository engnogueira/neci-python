# Lista de exercícios 1
Usando o conceito de função vamos assumir para nossos exercícios que existem as seguintes funções conhecidas:

* leiaArquivo(nome_do_arquivo) : 
  * abre o arquivo, lê seu texto e fecha o arquivo
  * retorna o texto lido como um string

* leiaHTML(url_dada):
  * acessa a url dada e baixa uma página html
  * retorna a pagina **HTML** lida (não é o texto)

* input() : 
  * lê input do usuário via teclado
  * retorna um string com as teclas digitadas pelo usuário

* print(texto):
  * escreve  texto no display

* escreveArquivo(nome, texto):
  * abre o arquivo nome, escreve nele o texto e fecha o arquivo

<hr/>

Nos problemas o objetivo é exercitar análise do problema a construção de procedimentos para sua solução. Use pseudo código e crie funções quando achar conveniente. Onde for necessário assuma uma função adequada, mesmo que não a tenha definido. Por exemplo, se você leu uma página da internet e quer obter o texto correspondente (não somente o HTML) assuma uma função adequada:

`html = leiaHTML(url) `

`texto = ConverteHTML(html)   # ConverteHTML() é uma função presumida`

<hr/>

Nos problemas abaixo use a função `input()` quando for necessário ler algum dado fornecido pelo usuário.

```
ex 1.1: Leia um número (use a função input). Calcule a soma dos quadrados de todos numeros inteiros de 1 até o numero lido. Imprima esta soma.

ex 1.2: Leia o nome de um arquivo. Leia o arquivo e procure ocorrências do caracter '@', contando-as. Imprima o valor da contagem.

ex 1.3: Dado um diretório contendo arquivos de diversos tipos conte o número de arquivos texto (.txt) e arquivos CSV (.csv). Imprima estas contagens.

ex 1.4: (avançado)  Leia um string entrado pelo usuário e procure sub strings formados por letras 'a' consecutivas. 

Por exemplo sub strings  como 'a', 'aa', 'aaa', e assim por diante. 

Conte o tamanho de cada sub string e imprima o tamanho do maior deles.
```
