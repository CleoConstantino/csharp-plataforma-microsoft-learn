## O que é uma linguagem de programação?

Linguagens de programação como o C# permitem que você escreva instruções que você deseja que sejam executadas pelo computador. Cada linguagem de programação tem uma sintaxe diferente, mas depois de aprender sua primeira linguagem de programação e, em seguida, tentar aprender uma segunda, você perceberá rapidamente que todas elas têm muitas ideias semelhantes. O trabalho de uma linguagem de programação é permitir que um humano escreva instruções de maneira compreensível e legível por humanos. As instruções que você escreve em uma linguagem de programação são chamadas de "código-fonte" ou apenas "código".

Neste ponto, o código pode ser atualizado e alterado por um desenvolvedor de software, mas o computador não pode entender o código. Primeiro, ele precisa ser  _compilado_  em um formato que o computador possa entender.

## O que é compilação?

Um programa especial chamado  **compilador**  converte o código-fonte em um formato diferente que é executável pela CPU do computador. Quando você usou o botão  **Executar**  verde na unidade anterior, o código escrito foi compilado pela primeira vez e executado.

Por que precisamos compilar nosso código? Embora a maioria das linguagens de programação pareça criptografada a princípio, elas podem ser compreendidas com mais facilidade pelos humanos do que pela linguagem  _preferencial_  do computador, que é expressa por meio da ativação ou da desativação de milhares ou milhões de pequenos comutadores. Os compiladores conectam esses dois mundos convertendo as instruções legíveis por humanos em um conjunto de instruções compreensível para o computador.


## O que é sintaxe?

A sintaxe de uma linguagem de programação inclui as palavras-chave, os operadores (caracteres especiais do teclado, como ponto e vírgula ou parênteses) e outras regras gramaticais impostas pelo compilador. As linhas de código digitadas seguiram dezenas de regras de sintaxe diferentes e usaram, pelo menos, quatro operadores diferentes. Há muito a aprender, mas felizmente cada conceito é simples. Não desista! Você aprenderá tudo isso.

Ao inserir o código no Editor do .NET, talvez você tenha observado alterações sutis na cor de diferentes palavras e símbolos. O realce de sintaxe é um recurso útil que você começará a usar para identificar com facilidade os erros no código que não estão em conformidade com as regras da sintaxe do C#. Na verdade, uma versão semelhante (e ainda mais robusta) desse recurso está disponível no Visual Studio Code e no IDE completo do Visual Studio.

## Como o código funcionou?

Vamos nos concentrar na linha de código a seguir que você escreveu.

C#Copiar

```
Console.WriteLine("Hello World!");

```

Quando você executou o código, viu que a mensagem  `Hello World!`  foi impressa no painel de saída. Quando a frase é colocada entre aspas duplas no código C#, ela é chamada de  **cadeia de caracteres literal**. Em outras palavras, literalmente, queríamos que os caracteres  `H`,  `e`,  `l`,  `l`,  `o`  e assim por diante fossem enviados para a saída. Você aprenderá mais sobre cadeias de caracteres literais no módulo intitulado "Armazenar e recuperar dados usando valores de literais e variáveis no C#".

A parte  `WriteLine()`  é chamada de  **método**. Você sempre pode identificar um método porque, após ele, há um conjunto de parênteses. Cada método tem um trabalho. O trabalho do método  `WriteLine()`  é gravar uma linha de dados na Janela de Saída. Os dados impressos são enviados entre os parênteses de abertura e de fechamento como um parâmetro de entrada. Alguns métodos precisam de parâmetros de entrada, outros não. Mas se você quiser invocar um método, sempre precisará usar os parênteses após o nome do método. Os parênteses são conhecidos como o  _operador de invocação de método_. Você aprenderá mais sobre como chamar métodos no módulo intitulado "Aproveitar bibliotecas de funcionalidade chamando métodos na biblioteca de classes .NET no C#".

A parte  `Console`  é chamada de  **classe**. As classes são "proprietárias" de métodos ou talvez uma maneira melhor de dizer isso é que os métodos residem em uma classe. Para visitar o método, é necessário saber em qual classe ele está. Por enquanto, considere uma classe como uma maneira de armazenar e organizar todos os métodos que fazem coisas semelhantes. Nesse caso, todos os métodos que operam no painel de Saída são definidos na classe Console.

Também há um ponto que separa o nome da classe  `Console`  e o nome do método  `WriteLine()`. O ponto é o  _operador de acesso a membro_. Em outras palavras, o ponto é a forma como você "navega" da classe para um dos métodos dela.

Por fim, o ponto e vírgula é o  _final do operador de instrução_. Uma  **instrução**  é uma instrução completa em C#. O ponto e vírgula informa ao compilador que terminamos de inserir o comando.

Não se preocupe se todas essas ideias e esses termos não fizerem sentido. Por enquanto, apenas lembre-se de que se desejar imprimir uma mensagem em uma Janela de Saída como um console:

-   Use  `Console.WriteLine("Your message here");`.
-   Coloque  `Console`,  `Write`  e  `Line`  em maiúsculas
-   Use a  _pontuação_  correta, pois ela tem uma função especial no C#
-   Se você cometer um erro, apenas identifique-o, corrija-o e execute novamente o aplicativo... não tem como dar errado
