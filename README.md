# teste-logica

&nbsp;&nbsp;Esse é um teste básico de lógica de programação, com um exemplo básico de problema matemático. O objetivo do teste é compreender a maneira como funciona o seu raciocínio lógico, independente que esteja concorrendo a Back ou Front-End.
  
&nbsp;&nbsp;Como nosso Stack é basicamente em Javascript (do back-end ao front-end), faça a resolução do mesmo em Javascript.

&nbsp;&nbsp;Resolva o teste no seu GitHub (Fork, outro repositório, como preferir) ou no repositório de sua preferência e envie o link pra gente =)
  
  ## Vending Machine

&nbsp;&nbsp;Tenho uma vending machine (aquelas máquinas onde você compra doces e refrigerantes) e preciso automatizar o cálculo de troco em moeda para ela. Imagine a seguinte situação: o cliente coloca R$ 5,00 e compra um produto de R$ 1,45. De acordo com as moedas disponíveis na máquina, você precisa dizer quantas e quais moedas de cada valor a máquina precisa devolver ao cliente.

  ### Cenário exemplo:

  Troco: R$ 3,55

  Moedas disponíveis:
  * 1 centavo: 20
  * 5 centavos: 13
  * 10 centavos: 2
  * 25 centavos: 22
  * 50 centavos: 1
  * 1 real: 14
  
  Moedas a serem devolvidas:
  * 1 centavo: 0
  * 5 centavos: 1
  * 10 centavos: 0
  * 25 centavos: 0
  * 50 centavos: 1
  * 1 real: 3
 
  Escreva uma função que receba dois parâmetros: 

  - O valor do troco a ser devolvido para o cliente.
  - Um array contendo as moedas disponíveis na máquina.
  
  Como esses parâmetros serão recebidos fica ao seu critério, mas documente como podemos manipulá-lo para testar a função. Dica: Pense nos edge cases que esse problema pode apresentar. Por exemplo, se a máquina não tem troco nenhum, como a sua função irá indicar esse retorno?

  E retorne:

  - Um array contendo a quantidade de moedas a serem despejadas.

  É desejável que você, ao escrever a função:

  - Retorne sempre o menor número de moedas possível.
  - Crie e documente os testes unitários realizados que achar pertinentes.
  - Documente as decisões que você precisou tomar para o melhor funcionamento da função.
  
Boa sorte!
