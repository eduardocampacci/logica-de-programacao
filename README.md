# Estudos em Lógica de Programação

![Lógica de Programação](https://github.com/davidallysson/davidallysson.github.io/blob/master/img/logica-de-programa%C3%A7%C3%A3o.png?raw=true)

## Sumário

> * [Introdução](#introdução)
> * [Como executar os códigos (no Windows)](#como-executar-os-códigos-no-windows)
>   * [1. Em C:](#1-em-c)
>   * [2. Em C#:](#2-em-c)
>   * [3. Em Java:](#3-em-java)
>   * [4. Em Ruby:](#4-em-ruby)
>   * [5. Em PHP:](#5-em-php)
>   * [6. Em Python:](#6-em-python)
> * [Questões Introdutórias](#questões-introdutórias)
>   * [1. Sequenciais:](#1-sequenciais)
>   * [2. Condicionais:](#2-condicionais)
>   * [3. Laços:](#3-laços)
>   * [4. Vetores:](#4-vetores)
>   * [5. Funções:](#5-funções)
>   * [6. Recursividade:](#6-recursividade)
> * [Problemas Contextualizados](#problemas-contextualizados)
>   * [URI - Categoria Iniciante](#uri---categoria-iniciante)
>   * [URI - Categoria Ad-hoc](#uri---categoria-ad-hoc)

## Introdução

Esse repositório foi criado com o objetivo de centralizar todos as questões de programação que eu estou estudando - e programando - no momento. Atualmente, o objetivo do repositório também foi expandido para contemplar questões de Maratonas de Programação. Estou participando de um curso de Programação Competitiva e lidamos com questões contextualizadas constantemente. Elas também podem ser encontradas neste repositório. Espero que, de alguma maneira, esse repositório possa colaborar com seus estudos.

## Como executar os códigos (no Windows):

### 1. Em C:

  - Baixe o gcc através deste link: (http://tdm-gcc.tdragon.net/download)
  - Instale o gcc normalmente no seu computador.
  - Caminhe, no terminal, até a pasta onde o arquivo .c está localizado.
  - Ao chegar na pasta, compile o código da questão:

    ```
    $ gcc -o teste arquivo.c
    ```

  - Feito isso é só executar:

    ```
    $ teste
    ```

  - ps: o nome "teste" pode ser alterado para qualquer nome.


### 2. Em C#:

  - Configure as variáveis de ambiente para que os código em C# possa ser compilado e executado no terminal:
  - Em Computador (ou Meu Computador), clique em "Configurações Avançadas do Sistema" e depois na aba "Avançado".
  - Clique no botão "Variáveis de Ambiente", procure pela variável PATH e clique em "Editar".
  - Adicione, no final da variável PATH, o diretório em que o compilador do C# se encontra.
    - ps: geralmente se encontra em:

        “C:\Windows\Microsoft.NET\Framework64\v4.0.30319″.

    - ps²: Não esqueça de colocar o caractere ponto-e-vírgula (;) para inserir uma nova entrada na variável “PATH”.
  - Pronto! Agora é só verificar se deu certo! Abra o terminal e execute:

      ```
      $ csc
      ```

  - Se tiver dado tudo certo aparecerá algo assim:

      ```
      $ Microsoft (R) Visual C# Compiler version 4.6.1087.0 for C# 5 Copyright (C) Microsoft Corporation. All rights reserved.
      ```

  - Navegue até chegar na pasta onde o seu código C# se encontra, e execute: (essa linha de código gerará o '.exe')

      ```
      $ csc nomedoarquivo.cs
      ```

  - Agora execute:

      ```
      $ nomedoarquivo.exe
      ```


### 3. Em Java:

  - Instale o JDK e o JRE no seu computador. (http://www.oracle.com/technetwork/java/javase/downloads/index.html)
  - Configure as variáveis de ambiente para que os comandos java possam ser utilizados no terminal:
    - Em Computador (ou Meu Computador), clique em "Configurações Avançadas do Sistema" e depois na aba "Avançado".
    - Clique no botão "Variáveis de Ambiente" e depois crie uma nova variável do sistema.
    - O nome da variável será "JAVA_HOME" e o seu valor será o caminho até o JDK instalado. Ex: “C:/Arquivos de programas/Java/jdk1.5.0_05”.
    - Clique em OK e crie novamente outra variável de ambiente.
    - Nomeei ela com "CLASSPATH" e adicione este valor: (se houver algo no CLASSPATH coloque ';' e adicione este conteúdo após o sinal).
    ```
    ;%JAVA_HOME%\lib;%JAVA_HOME%\lib\tools.jar;%JAVA_HOME%\lib\dt.jar;%JAVA_HOME%\lib\htmlconverter.jar;%JAVA_HOME%\jre\lib;%JAVA_HOME%\jre\lib\rt.jar;
    ```
    - Clique em OK e depois procure por "PATH" nas variáveis de ambiente e clique em "Editar".
    - Adicione este conteúdo à variável:
    ```
    $ ;%JAVA_HOME%\bin
    ```
    - Clique em OK e feche todas as janelas.
  - Abra o terminal e caminhe até a pasta onde o código se encontra.
  - Ao chegar na pasta digite:
    ```
    $ javac arquivo.java
    ```
  - Feito isso é só executar:
    ```
    $ java arquivo
    ```

### 4. Em Ruby:

  - Instale o Ruby no seu computador. (https://rubyinstaller.org/downloads/)
  - Abra o terminal e caminhe até a pasta onde o código se encontra.
  - Execute o seguinte comando:

        $ ruby arquivo.ruby

### 5. Em PHP:

  - Instale o XAMPP no seu computador. (https://www.apachefriends.org/pt_br/index.html)
  - Após instalado, vá até C://xampp//htdocs e ao chegar lá crie uma pasta para colocar os códigos PHP dentro.
  - Feito isso, abra o XAMPP e inicie o servidor Apache.
  - Após o servidor começar a funcionar vá até o navegador e acesse: http://localhost/nome_da_pasta_criada/nome_do_codigo.php

### 6. Em Python:

  - Instale o Python no seu computador. (https://www.python.org/downloads/)
  - Abra o terminal e caminhe até a pasta onde o código se encontra.
  - Execute o seguinte comando:

        $ python arquivo.py

## Questões Introdutórias:

### 1. Sequenciais

1 - Faça um programa que mostre a mensagem "Alo mundo" na tela.

[C](1%20-%20Sequenciais/sequenciais1.c) -
[C#](1%20-%20Sequenciais/sequenciais1.cs) -
[Java](1%20-%20Sequenciais/sequenciais1.java) -
[PHP](1%20-%20Sequenciais/sequenciais1.php) -
[Python](1%20-%20Sequenciais/sequenciais1.py) -
[Ruby](1%20-%20Sequenciais/sequenciais1.rb)

2 - Faça um programa que peça um número e então mostre a mensagem: "O número informado foi {numero}."

[C](1%20-%20Sequenciais/sequenciais2.c) -
[Java](1%20-%20Sequenciais/sequenciais2.java) -
[PHP](1%20-%20Sequenciais/sequenciais2.php) -
[Python](1%20-%20Sequenciais/sequenciais2.py) -
[Ruby](1%20-%20Sequenciais/sequenciais2.rb)

3 - Faça um programa que peça dois números e imprima a soma.

[C](1%20-%20Sequenciais/sequenciais3.c) -
[Java](1%20-%20Sequenciais/sequenciais3.java) -
[PHP](1%20-%20Sequenciais/sequenciais3.php) -
[Python](1%20-%20Sequenciais/sequenciais3.py) -
[Ruby](1%20-%20Sequenciais/sequenciais3.rb)

4 - Faça um programa que peça as 4 notas bimestrais e mostre a média.

[C](1%20-%20Sequenciais/sequenciais4.c) -
[Java](1%20-%20Sequenciais/sequenciais4.java) -
[PHP](1%20-%20Sequenciais/sequenciais4.php) -
[Python](1%20-%20Sequenciais/sequenciais4.py) -
[Ruby](1%20-%20Sequenciais/sequenciais4.rb)

5 - Faça um programa que converta metros para centímetros

[C](1%20-%20Sequenciais/sequenciais5.c) -
[Java](1%20-%20Sequenciais/sequenciais5.java) -
[PHP](1%20-%20Sequenciais/sequenciais5.php) -
[Python](1%20-%20Sequenciais/sequenciais5.py) -
[Ruby](1%20-%20Sequenciais/sequenciais5.rb)

6 - Faça um programa que peça o raio de um círculo, calcule e mostre sua área.

[C](1%20-%20Sequenciais/sequenciais6.c) -
[Java](1%20-%20Sequenciais/sequenciais6.java) -
[PHP](1%20-%20Sequenciais/sequenciais6.php) -
[Python](1%20-%20Sequenciais/sequenciais6.py) -
[Ruby](1%20-%20Sequenciais/sequenciais6.rb)

7 - Faça um programa que calcule a área de um quadrado, em seguida mostre o dobro desta área para o usuário.

[C](1%20-%20Sequenciais/sequenciais7.c) -
[Java](1%20-%20Sequenciais/sequenciais7.java) -
[PHP](1%20-%20Sequenciais/sequenciais7.php) -
[Python](1%20-%20Sequenciais/sequenciais7.py) -
[Ruby](1%20-%20Sequenciais/sequenciais7.rb)

8 - Faça um programa que pergunte quanto você ganha por hora e o número de horas trabalhadas no mês. Calcule e mostre o total do seu salário no referido mês.

[C](1%20-%20Sequenciais/sequenciais8.c) -
[Java](1%20-%20Sequenciais/sequenciais8.java) -
[PHP](1%20-%20Sequenciais/sequenciais8.php) -
[Python](1%20-%20Sequenciais/sequenciais8.py) -
[Ruby](1%20-%20Sequenciais/sequenciais8.rb)

9 - Faça um programa que peça a temperatura em graus Farenheit, transforme e mostre a temperatura em graus Celsius. C = (5 * (F-32) / 9)

[C](1%20-%20Sequenciais/sequenciais9.c) -
[Java](1%20-%20Sequenciais/sequenciais9.java) -
[PHP](1%20-%20Sequenciais/sequenciais9.php) -
[Python](1%20-%20Sequenciais/sequenciais9.py) -
[Ruby](1%20-%20Sequenciais/sequenciais9.rb)

10 - Faça um programa que peça a temperatura em graus Celsius, transforme e mostre em graus Farenheit.

[C](1%20-%20Sequenciais/sequenciais10.c) -
[Java](1%20-%20Sequenciais/sequenciais10.java) -
[PHP](1%20-%20Sequenciais/sequenciais10.php) -
[Python](1%20-%20Sequenciais/sequenciais10.py) -
[Ruby](1%20-%20Sequenciais/sequenciais10.rb)

11 - Faça um programa que peça 2 números inteiros e um número real. Calcule e mostre:
  - o produto do dobro do primeiro com metade do segundo
  - a soma do triplo do primeiro com o terceiro
  - o terceiro elevado ao cubo

[C](1%20-%20Sequenciais/sequenciais11.c) -
[Java](1%20-%20Sequenciais/sequenciais11.java) -
[PHP](1%20-%20Sequenciais/sequenciais11.php) -
[Python](1%20-%20Sequenciais/sequenciais11.py) -
[Ruby](1%20-%20Sequenciais/sequenciais11.rb)

12 - Tendo como dados de entrada a altura de uma pessoa, construa um algoritmo que calcule seu peso ideal, usando a seguinte fórmula: (72.7 * altura) - 58.

[C](1%20-%20Sequenciais/sequenciais12.c) -
[Java](1%20-%20Sequenciais/sequenciais12.java) -
[PHP](1%20-%20Sequenciais/sequenciais12.php) -
[Python](1%20-%20Sequenciais/sequenciais12.py) -
[Ruby](1%20-%20Sequenciais/sequenciais12.rb)

13 - Escreva um programa que leia um número real e faça o arredondamento para inteiro. Se a parte fracionária for maior do que 0.5 o arredondamento deve ser feito para o próximo inteiro.

[C](1%20-%20Sequenciais/sequenciais13.c) -
[Java](1%20-%20Sequenciais/sequenciais13.java) -
[PHP](1%20-%20Sequenciais/sequenciais13.php) -
[Python](1%20-%20Sequenciais/sequenciais13.py) -
[Ruby](1%20-%20Sequenciais/sequenciais13.rb)

### 2. Condicionais

1 - Escreva um programa que leia um número e mostre se ele é igual a 10.

[C](2%20-%20Condi%C3%A7%C3%B5es/condicoes1.c) -
[Java](2%20-%20Condi%C3%A7%C3%B5es/condicoes1.java) -
[PHP](2%20-%20Condi%C3%A7%C3%B5es/condicoes1.php) -
[Ruby](2%20-%20Condi%C3%A7%C3%B5es/condicoes1.rb)

2 - Escreva um programa que leia um número e mostre se ele é múltiplo de 7.

[C](2%20-%20Condi%C3%A7%C3%B5es/condicoes2.c) -
[Java](2%20-%20Condi%C3%A7%C3%B5es/condicoes2.java) -
[PHP](2%20-%20Condi%C3%A7%C3%B5es/condicoes2.php) -
[Ruby](2%20-%20Condi%C3%A7%C3%B5es/condicoes2.rb)

3 - Escreva um programa que leia um número e mostre se ele é positivo.

[C](2%20-%20Condi%C3%A7%C3%B5es/condicoes3.c) -
[Java](2%20-%20Condi%C3%A7%C3%B5es/condicoes3.java) -
[PHP](2%20-%20Condi%C3%A7%C3%B5es/condicoes3.php) -
[Ruby](2%20-%20Condi%C3%A7%C3%B5es/condicoes3.rb)

4 - Escreva um programa que leia dois números e informe se eles são iguais.

[C](2%20-%20Condi%C3%A7%C3%B5es/condicoes4.c) -
[Java](2%20-%20Condi%C3%A7%C3%B5es/condicoes4.java) -
[PHP](2%20-%20Condi%C3%A7%C3%B5es/condicoes4.php) -
[Ruby](2%20-%20Condi%C3%A7%C3%B5es/condicoes4.rb)

5 - Escreva um programa que leia dois números e mostre o maior.

[C](2%20-%20Condi%C3%A7%C3%B5es/condicoes5.c) -
[Java](2%20-%20Condi%C3%A7%C3%B5es/condicoes5.java) -
[PHP](2%20-%20Condi%C3%A7%C3%B5es/condicoes5.php) -
[Ruby](2%20-%20Condi%C3%A7%C3%B5es/condicoes5.rb)

6 - Escreva um programa que leia dois nomes e mostre o que contém maior quantidade de caracteres.

[C](2%20-%20Condi%C3%A7%C3%B5es/condicoes6.c) -
[Java](2%20-%20Condi%C3%A7%C3%B5es/condicoes6.java) -
[PHP](2%20-%20Condi%C3%A7%C3%B5es/condicoes6.php) -
[Ruby](2%20-%20Condi%C3%A7%C3%B5es/condicoes6.rb)

7 - Escreva um programa que leia um número e mostre se ele é positivo.

[C](2%20-%20Condi%C3%A7%C3%B5es/condicoes7.c) -
[Java](2%20-%20Condi%C3%A7%C3%B5es/condicoes7.java) -
[PHP](2%20-%20Condi%C3%A7%C3%B5es/condicoes7.php) -
[Ruby](2%20-%20Condi%C3%A7%C3%B5es/condicoes7.rb)

8 - Escreva um programa que leia um número inteiro que corresponde a um ângulo e informe em qual quadrante este ângulo se encontra.

[C](2%20-%20Condi%C3%A7%C3%B5es/condicoes8.c) -
[Java](2%20-%20Condi%C3%A7%C3%B5es/condicoes8.java) -
[PHP](2%20-%20Condi%C3%A7%C3%B5es/condicoes8.php) -
[Ruby](2%20-%20Condi%C3%A7%C3%B5es/condicoes8.rb)

9 - Escreva um programa que leia um número inteiro que corresponde a um ângulo e informe em qual quadrante este ângulo se encontra e quantas voltas ele dá. (360º = uma volta)

[C](2%20-%20Condi%C3%A7%C3%B5es/condicoes9.c) -
[Java](2%20-%20Condi%C3%A7%C3%B5es/condicoes9.java) -
[PHP](2%20-%20Condi%C3%A7%C3%B5es/condicoes9.php) -
[Ruby](2%20-%20Condi%C3%A7%C3%B5es/condicoes9.rb)

10 - Escreva um programa que leia dois números inteiros e informe se o maior é múltiplo do menor

[C](2%20-%20Condi%C3%A7%C3%B5es/condicoes10.c) -
[Java](2%20-%20Condi%C3%A7%C3%B5es/condicoes10.java) -
[PHP](2%20-%20Condi%C3%A7%C3%B5es/condicoes10.php) -
[Ruby](2%20-%20Condi%C3%A7%C3%B5es/condicoes10.rb)

11 - Escreva um programa que leia dois nomes de times de futebol, a quantidade de gols do primeiro time, a quantidade de gols do segundo time e mostre o nome do time vencedor da partida.

[C](2%20-%20Condi%C3%A7%C3%B5es/condicoes11.c) -
[Java](2%20-%20Condi%C3%A7%C3%B5es/condicoes11.java) -
[PHP](2%20-%20Condi%C3%A7%C3%B5es/condicoes11.php) -
[Ruby](2%20-%20Condi%C3%A7%C3%B5es/condicoes11.rb)

12 - Brincadeira do ímpar ou par: escreva um programa que leia dois nomes e dois valores inteiros, que correspondem ao que cada um colocou, e informe quem ganhou o "impar ou par".

[C](2%20-%20Condi%C3%A7%C3%B5es/condicoes12.c) -
[Java](2%20-%20Condi%C3%A7%C3%B5es/condicoes12.java) -
[PHP](2%20-%20Condi%C3%A7%C3%B5es/condicoes12.php) -
[Ruby](2%20-%20Condi%C3%A7%C3%B5es/condicoes12.rb)

13 - Escreva um programa que leia 4 números e mostre o maior.

[C](2%20-%20Condi%C3%A7%C3%B5es/condicoes13.c) -
[Java](2%20-%20Condi%C3%A7%C3%B5es/condicoes13.java) -
[PHP](2%20-%20Condi%C3%A7%C3%B5es/condicoes13.php) -
[Ruby](2%20-%20Condi%C3%A7%C3%B5es/condicoes13.rb)

### 3. Laços

1 - Faça um programa que peça uma nota, entre zero e dez. Mostre uma mensagem caso o valor seja inválido e continue pedindo até que o usuário informe um valor válido.

[PHP](3%20-%20Laços/lacos1.php) -
[Ruby](3%20-%20Laços/lacos1.rb)

2 - Faça um programa que leia um nome de usuário e a sua senha e não aceite a senha igual ao nome do usuário, mostrando uma mensagem de erro e voltando a pedir as informações.

[PHP](3%20-%20Laços/lacos2.php) -
[Ruby](3%20-%20Laços/lacos2.rb)

3 - Faça um programa que leia 5 números e informe o maior número.

[PHP](3%20-%20Laços/lacos3.php) -
[Ruby](3%20-%20Laços/lacos3.rb)

4 - Faça um programa que leia 5 números e informe a soma e a média dos números.

[PHP](3%20-%20Laços/lacos4.php) -
[Ruby](3%20-%20Laços/lacos4.rb)

5 - Faça um programa que imprima na tela apenas os números ímpares entre 1 e 50.

[PHP](3%20-%20Laços/lacos5.php) -
[Ruby](3%20-%20Laços/lacos5.rb)

6 - Desenvolva um gerador de tabuada, capaz de gerar a tabuada de qualquer número inteiro entre 1 a 10. O usuário deve informar de qual numero ele deseja ver a tabuada.

[PHP](3%20-%20Laços/lacos6.php) -
[Ruby](3%20-%20Laços/lacos6.rb)

### 4. Vetores

1 - Escreva um programa que leia 30 números e armazene-os em um array. Depois leia mais um número inteiro, que deve corresponder a um índice do array, e troque o primeiro elemento com o elemento do índice lido. Caso o índice não seja válido o programa deve trocar o primeiro com o último elemento. Ao final o programa deve mostrar os elementos do array, um elemento por linha.

[PHP](4%20-%20Vetores/vetores1.php) -
[Ruby](4%20-%20Vetores/vetores1.rb)

2 - Escreva um programa que leia uma matriz de inteiros 5 x 5, e mostre a linha cuja a soma dos números é a maior.

[PHP](4%20-%20Vetores/vetores2.php) -
[Ruby](4%20-%20Vetores/vetores2.rb)

3 - Escreva um programa que leia uma matriz N x M, e imprima a sua transposta.

[PHP](4%20-%20Vetores/vetores3.php) -
[Ruby](4%20-%20Vetores/vetores3.rb)

4 - Escreva um programa que leia uma matriz N x M de strings, e mostre a posição com a string de maior tamanho.

[PHP](4%20-%20Vetores/vetores4.php) -
[Ruby](4%20-%20Vetores/vetores4.rb)

5 - Dadas as matrizes:

     |  1  2  3  |     | -7 -8  9  |     |  2  3 -4  |
     | -4  5  6  |     | 12  6  5  |     |  6  7  1  |
     |  4  6  8  |     |  8  7  4  |     |  2  8  7  |
           A                 B                 C
determine a matriz D resultante da operação A + B – C.

[PHP](4%20-%20Vetores/vetores5.php) -
[Ruby](4%20-%20Vetores/vetores5.rb)

6 - São dadas as matrizes A = (aij) e B = (bij), quadradas de ordem 4, com aij = 3i + 4j e bij = – 4i – 3j. Considerando C = A + B, escreva um programa que calcule a matriz C.

[PHP](4%20-%20Vetores/vetores6.php) -
[Ruby](4%20-%20Vetores/vetores6.rb)

### 5. Funções

1 - Escreva uma função, chamada maior2, que retorna o maior de dois números

[PHP](5%20-%20Fun%C3%A7%C3%B5es/funcoes01.php) -
[Ruby](5%20-%20Fun%C3%A7%C3%B5es/funcoes01.rb)

2 - Escreva uma função, chamada maior3, que retorna o maior de três números.

[PHP](5%20-%20Fun%C3%A7%C3%B5es/funcoes02.php) -
[Ruby](5%20-%20Fun%C3%A7%C3%B5es/funcoes02.rb)

3 - Escreva uma função chamada eImpar que retorna true se o número for ímpar ou false se ele não for ímpar.

[PHP](5%20-%20Fun%C3%A7%C3%B5es/funcoes03.php) -
[Ruby](5%20-%20Fun%C3%A7%C3%B5es/funcoes03.rb)

4 - Escreva uma função chamada fat que retorna o fatorial de um número. A função deve verificar se o parâmetro passado é inteiro e maior do que zero, caso contrário deve retornar -1.

[PHP](5%20-%20Fun%C3%A7%C3%B5es/funcoes04.php) -
[Ruby](5%20-%20Fun%C3%A7%C3%B5es/funcoes04.rb)

5 - Escreva uma função chamada soma_array que retorna a soma dos elementos de um array.

[PHP](5%20-%20Fun%C3%A7%C3%B5es/funcoes05.php) -
[Ruby](5%20-%20Fun%C3%A7%C3%B5es/funcoes05.rb)

6 - Escreva uma função, chamada media_ifrn, que recebe dois parâmetros reais e calcule a média ponderada, considerando o cálculo da média dos cursos superiores do IFRN.

[PHP](5%20-%20Fun%C3%A7%C3%B5es/funcoes06.php) -
[Ruby](5%20-%20Fun%C3%A7%C3%B5es/funcoes06.rb)

7 - Escreva uma função, chamada transposta_matriz, que recebe uma matriz como parâmetro e retorna sua transposta.

[PHP](5%20-%20Fun%C3%A7%C3%B5es/funcoes07.php) -
[Ruby](5%20-%20Fun%C3%A7%C3%B5es/funcoes07.rb)

8 - Escreva uma função, chamada ordenarArray, que recebe um array como parâmetro e retorna o array ordenado.

[PHP](5%20-%20Fun%C3%A7%C3%B5es/funcoes08.php) -
[Ruby](5%20-%20Fun%C3%A7%C3%B5es/funcoes08.rb)

### 6. Recursividade

1 - Escreva uma função recursiva que realize a operação de divisão.

[PHP](6%20-%20Recursividade/div.php) -
[Ruby](6%20-%20Recursividade/div.rb)

2 - Escreva uma função recursiva que gere o fatorial de um número "x".

[PHP](6%20-%20Recursividade/fatorial.php) -
[Ruby](6%20-%20Recursividade/fatorial.rb)

3 - Escreva uma função recursiva que gere a sequência fibonnaci até uma determinada posição "n" vinda por parâmetro.

[PHP](6%20-%20Recursividade/fibonnaci.php) -
[Ruby](6%20-%20Recursividade/fibonnaci.rb)

4 - Escreva uma função recursiva que retorne o resto de uma divisão inteira.

[PHP](6%20-%20Recursividade/mod.php) -
[Ruby](6%20-%20Recursividade/mod.rb)

5 - Escreva uma função recursiva que realize a operação de exponenciação.

[PHP](6%20-%20Recursividade/potencia.php) -
[Ruby](6%20-%20Recursividade/potencia.rb)

## Problemas contextualizados:

Os problemas a seguir são retirados dos seguintes sites:

* [URI](https://www.urionlinejudge.com.br)
* [UVA](uva.onlinejudge.org)
* [SPOJ.BR](http://br.spoj.com/)

### URI - Categoria Iniciante

* [1001 - Extremamente Basico](URI/1%20-%20Iniciante/1001%20-%20Extremamente%20B%C3%A1sico.pdf) => [Código](URI/1%20-%20Iniciante/ExtremamenteBasico.c)
* [1002 - Área do Círculo](URI/1%20-%20Iniciante/1002%20-%20%C3%81rea%20do%20C%C3%ADrculo.pdf) => [Código](URI/1%20-%20Iniciante/AreaDoCirculo.c)
* [1003 - Soma Simples](URI/1%20-%20Iniciante/1003%20-%20Soma%20Simples.pdf) => [Código](URI/1%20-%20Iniciante/SomaSimples.c)
* [1004 - Produto Simples](URI/1%20-%20Iniciante/1004%20-%20Produto%20Simples.pdf) => [Código](URI/1%20-%20Iniciante/ProdutoSimples.c)
* [1005 - Média 1](URI/1%20-%20Iniciante/1005%20-%20M%C3%A9dia%201.pdf) => [Código](URI/1%20-%20Iniciante/Media1.c)
* [1006 - Média 2](URI/1%20-%20Iniciante/1006%20-%20M%C3%A9dia%202.pdf) => [Código](URI/1%20-%20Iniciante/Media2.c)
* [1007 - Diferença](URI/1%20-%20Iniciante/1007%20-%20Diferen%C3%A7a.pdf) => [Código](URI/1%20-%20Iniciante/Diferenca.c)
* [1008 - Salário](URI/1%20-%20Iniciante/1008%20-%20Sal%C3%A1rio.pdf) => [Código](URI/1%20-%20Iniciante/Salario.c)
* [1009 - Salário Com Bônus](URI/1%20-%20Iniciante/1009%20-%20Sal%C3%A1rio%20com%20B%C3%B4nus.pdf) => [Código](URI/1%20-%20Iniciante/SalarioComBonus.c)
* [1010 - Cálculo Simples](URI/1%20-%20Iniciante/1010%20-%20C%C3%A1lculo%20Simples.pdf) => [Código](URI/1%20-%20Iniciante/CalculoSimples.c)
* [1011 - Esfera](URI/1%20-%20Iniciante/1011%20-%20Esfera.pdf) => [Código](URI/1%20-%20Iniciante/Esfera.c)
* [1012 - Área](URI/1%20-%20Iniciante/1012%20-%20%C3%81rea.pdf) => [Código](URI/1%20-%20Iniciante/Area.c)
* [1013 - O Maior](URI/1%20-%20Iniciante/1013%20-%20O%20Maior.pdf) => [Código](URI/1%20-%20Iniciante/OMaior.c)
* [1014 - Consumo](URI/1%20-%20Iniciante/1014%20-%20Consumo.pdf) => [Código](URI/1%20-%20Iniciante/Consumo.c)
* [1015 - Distancia Entre Dois Pontos](URI/1%20-%20Iniciante/1015%20-%20Dist%C3%A2ncia%20Entre%20Dois%20Pontos.pdf) => [Código](URI/1%20-%20Iniciante/DistanciaEntreDoisPontos.c)
* [1016 - Distancia](URI/1%20-%20Iniciante/1016%20-%20Dist%C3%A2ncia.pdf) => [Código](URI/1%20-%20Iniciante/Distancia.c)
* [1017 - Gasto de Combustível](URI/1%20-%20Iniciante/1017%20-%20Gasto%20de%20Combust%C3%ADvel.pdf) => [Código](URI/1%20-%20Iniciante/GastoDeCombustivel.c)
* [1018 - Cédulas](URI/1%20-%20Iniciante/1018%20-%20C%C3%A9dulas.pdf) => [Código](URI/1%20-%20Iniciante/Cedulas.c)
* [1019 - Conversão de Tempo](URI/1%20-%20Iniciante/1019%20-%20Convers%C3%A3o%20de%20Tempo.pdf) => [Código](URI/1%20-%20Iniciante/ConversaoDeTempo.c)
* [1020 - Idade em Dias](URI/1%20-%20Iniciante/1020%20-%20Idade%20em%20Dias.pdf) => [Código](URI/1%20-%20Iniciante/IdadeEmDias.c)
* [1021 - Notas e Moedas](URI/1%20-%20Iniciante/1021%20-%20Notas%20e%20Moedas.pdf) => [Código](URI/1%20-%20Iniciante/NotasEMoedas.c)
* [1035 - Teste de Seleção 1](URI/1%20-%20Iniciante/1035%20-%20Teste%20de%20Seleção%201.pdf) => [Código](URI/1%20-%20Iniciante/TesteDeSelecao1.c)
* [1036 - Fórmula de Bhaskara](URI/1%20-%20Iniciante/1036%20-%20Fórmula%20de%20Bhaskara.pdf) => [Código](URI/1%20-%20Iniciante/Bhaskara.c)
* [1037 - Intervalo](URI/1%20-%20Iniciante/1037%20-%20Intervalo.pdf) => [Código](URI/1%20-%20Iniciante/Intervalo.c)
* [1038 - Lanche](URI/1%20-%20Iniciante/1038%20-%20Lanche.pdf) => [Código](URI/1%20-%20Iniciante/Lanche.c)
* [1040 - Média 3](URI/1%20-%20Iniciante/1040%20-%20Média%203.pdf) => [Código](URI/1%20-%20Iniciante/Media3.c)
* [1041 - Coordenadas de um Ponto](URI/1%20-%20Iniciante/1041%20-%20Coordenadas%20de%20um%20Ponto.pdf) => [Código](URI/1%20-%20Iniciante/CoordenadasDeUmPonto.c)
* [1042 - Sort Simples](URI/1%20-%20Iniciante/1042%20-%20Sort%20Simples.pdf) => [Código](URI/1%20-%20Iniciante/SortSimples.c)
* [1043 - Triangulo](URI/1%20-%20Iniciante/1043%20-%20Triângulo.pdf) => [Código](URI/1%20-%20Iniciante/Triangulo.c)
* [1044 - Múltiplos](URI/1%20-%20Iniciante/1044%20-%20Múltiplos.pdf) => [Código](URI/1%20-%20Iniciante/Multiplos.c)
* [1045 - Tipos de Triangulos](URI/1%20-%20Iniciante/1045%20-%20Tipos%20de%20Triângulos.pdf) => [Código](URI/1%20-%20Iniciante/TiposDeTriangulos.c)
* [1046 - Tempo de Jogo](URI/1%20-%20Iniciante/1046%20-%20Tempo%20de%20Jogo.pdf) => [Código](URI/1%20-%20Iniciante/TempoDeJogo.c)
* [1047 - Tempo de Jogo com Minutos](URI/1%20-%20Iniciante/1047%20-%20Tempo%20de%20Jogo%20com%20Minutos.pdf) => [Código](URI/1%20-%20Iniciante/TempoDeJogoComMinutos.c)
* [1048 - Aumento de Salário](URI/1%20-%20Iniciante/1048%20-%20Aumento%20de%20Salário.pdf) => [Código](URI/1%20-%20Iniciante/AumentoDeSalario.c)
* [1049 - Animal](URI/1%20-%20Iniciante/) => [Código](URI/1%20-%20Iniciante/Animal.c) @ wrong
* [1050 - DDD](URI/1%20-%20Iniciante/) => [Código](URI/1%20-%20Iniciante/DDD.c)
* [1051 - Imposto de Renda](URI/1%20-%20Iniciante/) => [Código](URI/1%20-%20Iniciante/ImpostoDeRenda.c)
* [1052 - Mês](URI/1%20-%20Iniciante/) => [Código](URI/1%20-%20Iniciante/Mes.c)
* [1059 - Números Pares](URI/1%20-%20Iniciante/) => [Código](URI/1%20-%20Iniciante/NumerosPares.c)
* [1060 - Números Positivos](URI/1%20-%20Iniciante/) => [Código](URI/1%20-%20Iniciante/NumerosPositivos.c)
<!--* [1000 - DDD](URI/1%20-%20Iniciante/) => [Código](URI/1%20-%20Iniciante/<codigo>.c)
<!--* [1000 - DDD](URI/1%20-%20Iniciante/) => [Código](URI/1%20-%20Iniciante/<codigo>.c)
<!--* [1000 - DDD](URI/1%20-%20Iniciante/) => [Código](URI/1%20-%20Iniciante/<codigo>.c)
<!--* [1000 - DDD](URI/1%20-%20Iniciante/) => [Código](URI/1%20-%20Iniciante/<codigo>.c)
<!--* [1000 - DDD](URI/1%20-%20Iniciante/) => [Código](URI/1%20-%20Iniciante/<codigo>.c)
<!--* [1000 - DDD](URI/1%20-%20Iniciante/) => [Código](URI/1%20-%20Iniciante/<codigo>.c)
<!--* [1000 - DDD](URI/1%20-%20Iniciante/) => [Código](URI/1%20-%20Iniciante/<codigo>.c)
<!--* [1000 - DDD](URI/1%20-%20Iniciante/) => [Código](URI/1%20-%20Iniciante/<codigo>.c)
<!--* [1000 - DDD](URI/1%20-%20Iniciante/) => [Código](URI/1%20-%20Iniciante/<codigo>.c)
<!--* [1000 - DDD](URI/1%20-%20Iniciante/) => [Código](URI/1%20-%20Iniciante/<codigo>.c)
<!--* [1000 - DDD](URI/1%20-%20Iniciante/) => [Código](URI/1%20-%20Iniciante/<codigo>.c)
<!--* [1000 - DDD](URI/1%20-%20Iniciante/) => [Código](URI/1%20-%20Iniciante/<codigo>.c)
<!--* [1000 - DDD](URI/1%20-%20Iniciante/) => [Código](URI/1%20-%20Iniciante/<codigo>.c)
<!--* [1000 - DDD](URI/1%20-%20Iniciante/) => [Código](URI/1%20-%20Iniciante/<codigo>.c)
-->

### URI - Categoria Ad-hoc

* [1026 - Carrega ou não Carrega](URI/2%20-%20Ad-hoc/1026%20-%20Carrega%20ou%20n%C3%A3o%20Carrega.pdf) => [Código](URI/2%20-%20Ad-hoc/CarregaOuNaoCarrega.c)

### UVA - Contest Volumes

* [11984 - A Change In A Thermal Unit](UVA/Contest%20Volumes/11984.pdf) => [Código](UVA/Contest%20Volumes/11984.c)
