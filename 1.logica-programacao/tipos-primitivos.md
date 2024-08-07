Índice Tipos Primitivos

1. [informação](#informação)
1. [constantes](#constantes)
1. [variáveis](#variáveis)
1. [declarando variáveis](#declarando-variáveis)
1. [expressões aritméticas](#expressões-aritméticas)
1. [parênteses](#parênteses)
1. [prioridades](#prioridades)
1. [expressões lógicas](#expressões-lógicas)
1. [comandos de atribuição](#comandos-de-atribuição)

# tipos primitivos

## informação

Para entender os tipos primitivos, tem que estar atentos para um conceito muito importante, *a informação*.

Existe uma diferença sutil entre dado e informação. Ao citar uma data, por exemplo, 20 de setembro. Essa data sozinha, representa apenas um dado, mas ao dizer que é a data de início da Revolução Farroupilha, está sendo agregado um valor ao dado da data, apresentando uma informação.

Aproximando a maneira que o computador manipula as informações, pode-se dividir em quatro tipos primitivos, que são os tipos básicos que serão usados na construção de algoritmos.

- `inteiro` : é toda e qualquer informação numérica que pertença ao conjunto dos números inteiros (positivos, negativos e nulo). Exemplos :
    - ele tem 3 gatos;
    - eu tenho 10 dedos;
    - eu tinha 2 pulmões;
- `real` : é toda e qualquer informação numérica que pertença ao conjunto dos números reais (positivos, negativos e nulo). Exemplos :
    - o PI valor 3.1415926535;
    - o número de Euler vale 2.71828;
    - peguei 0.853 gramas de guisado;
- `caracter` : é toda e qualquer informação composta de um conjunto de caracteres numéricos  (0...9), alfabéticos (A...Z, a...z) e especiais (!@#$%,.). Esse tipo de dado está sempre entre aspas simples ou duplas. Exemplos :
    - minha senha é "s)Lf]\?[G8A$aQM:Fnr'/Orw;%qg$<*9";
    - o nome é "Arnold Schwarzenegger";
    - ela disse que "a resposta é 42";
- `lógico` : é toda e qualquer informação que pode assumir apenas duas situações. Exemplos :
    - a porta está **aberta** ou **fechada**;
    - a pessoa está **viva** ou **morta**;
    - a lâmpada está **ligada** ou **desligada**;

<details>
    <summary>Lista de Exercícios</summary>

Determine o tipo primitivo de cada uma das sentenças abaixo :

1. Eu vi 12 pássaros no parque.
    ```
    inteiro
    ```
1. A temperatura média do corpo humano é 36.5 graus Celsius.
    ```
    real
    ```
1. O nome do meu cachorro é "Buddy".
    ```
    caracter
    ```
1. A janela está aberta ou fechada?
    ```
    lógico
    ```
1. A altura da Torre Eiffel é 324 metros.
    ```
    inteiro
    ```
1. Minha senha é "A1b2C3d4!".
    ```
    caracter
    ```
1. Ele tem 4 filhos.
    ```
    inteiro
    ```
1. O número de Euler vale 2.71828.
    ```
    real
    ```
1. A porta está trancada ou destrancada?
    ```
    lógico
    ```
1. Eu tenho 5 irmãos.
    ```
    inteiro
    ```
1. A profundidade do oceano é 10.994 metros.
    ```
    real
    ```
1. O nome da cidade é "São Paulo".
    ```
    caracter
    ```
1. O computador está ligado ou desligado?
    ```
    lógico
    ```
1. O preço do litro de gasolina é 5.49 reais.
    ```
    real
    ```
1. Meu endereço de e-mail é "meuemail@exemplo.com".
    ```
    caracter
    ```
1. Quantos dedos há nas suas duas mãos?
    ```
    inteiro
    ```
1. O número de telefone é "123-456-7890".
    ```
    caracter
    ```
1. Você está feliz ou triste?
    ```
    lógico
    ```
1. A distância entre as duas cidades é 300 quilômetros.
    ```
    inteiro
    ```
1. Meu filme favorito é "O Senhor dos Anéis".
    ```
    caracter
    ```
1. O sinal está verde ou vermelho?
    ```
    lógico
    ```
1. A raiz quadrada de 64 é 8.
    ```
    inteiro
    ```
1. O nome da sua escola é "Escola Primária ABC".
    ```
    caracter
    ```
1. A lâmpada está ligada ou desligada?
    ```
    lógico
    ```
1. Eu bebi 1.5 litros de água hoje.
    ```
    real
    ```
1. A frase "Carpe Diem" é do latim.
    ```
    caracter
    ```
1. O céu está limpo ou nublado?
    ```
    lógico
    ```
1. Ele ganhou 15 pontos no jogo.
    ```
    inteiro
    ```
1. A área do círculo é 78.5 centímetros quadrados.
    ```
    real
    ```
1. A senha é "P@ssw0rd!".
    ```
    caracter
    ```
1. A música está tocando ou parada?
    ```
    lógico
    ```
1. Eu tenho 3 cachorros.
    ```
    inteiro
    ```
1. O valor de Pi é 3.1415926535.
    ```
    real
    ```
1. A janela está aberta ou fechada?
    ```
    lógico
    ```
1. O nome do autor é "J.K. Rowling".
    ```
    caracter
    ```
1. O carro está em movimento ou parado?
    ```
    lógico
    ```
1. A massa do objeto é 4.5 quilogramas.
    ```
    real
    ```
1. O número da sua conta bancária é "12345678".
    ```
    caracter
    ```
1. A comida está pronta ou crua?
    ```
    lógico
    ```
1. O dia está ensolarado ou chuvoso?
    ```
    lógico
    ```
1. O livro tem 350 páginas.
    ```
    inteiro
    ```
1. O peso do bebê é 3.2 quilogramas.
    ```
    real
    ```
1. O título do livro é "O Alquimista".
    ```
    caracter
    ```
1. O telefone está silencioso ou tocando?
    ```
    lógico
    ```
1. O preço do pão é 2.75 reais.
    ```
    real
    ```
1. A frase "Olá, mundo!" é comum na programação.
    ```
    caracter
    ```
1. A luz está acesa ou apagada?
    ```
    lógico
    ```
1. A soma de 5 e 3 é 8.
    ```
    inteiro
    ```
1. O nome do filme é "Matrix".
    ```
    caracter
    ```
1. Você está acordado ou dormindo?
    ```
    lógico
    ```
1. O comprimento do rio é 6.650 quilômetros.
    ```
    real
    ```
1. O endereço é "Rua das Flores, 123".
    ```
    caracter
    ```
1. O computador está ligado ou desligado?
    ```
    lógico
    ```
1. A profundidade do lago é 15 metros.
    ```
    inteiro
    ```
1. O valor da resistência é 10 ohms.
    ```
    inteiro
    ```
1. O nome do seu animal de estimação é "Fido".
    ```
    caracter
    ```
1. A janela está aberta ou fechada?
    ```
    lógico
    ```
1. O saldo da conta é 1023.75 reais.
    ```
    real
    ```
1. A frase "A prática leva à perfeição" é um provérbio.
    ```
    caracter
    ```
1. O céu está limpo ou nublado?
    ```
    lógico
    ```
1. O prédio tem 20 andares.
    ```
    inteiro
    ```
1. O peso do pacote é 2.3 quilogramas.
    ```
    real
    ```
1. O nome do jogo é "Minecraft".
    ```
    caracter
    ```
1. A luz está acesa ou apagada?
    ```
    lógico
    ```
1. A área da sala é 45 metros quadrados.
    ```
    inteiro
    ```
1. A sequência de caracteres é "!@#$%^&*()".
    ```
    caracter
    ```
1. O telefone está tocando ou silencioso?
    ```
    lógico
    ```
1. O número de páginas lidas é 200.
    ```
    inteiro
    ```
1. A densidade do material é 7.85 g/cm³.
    ```
    real
    ```
1. O nome da rua é "Avenida Paulista".
    ```
    caracter
    ```
1. A porta está aberta ou fechada?
    ```
    lógico
    ```
1. O valor da pressão é 101.3 kPa.
    ```
    real
    ```
1. O título da música é "Bohemian Rhapsody".
    ```
    caracter
    ```
1. A comida está quente ou fria?
    ```
    lógico
    ```
1. O comprimento do campo é 100 metros.
    ```
    inteiro
    ```
1. A palavra "Python" é uma linguagem de programação.
    ```
    caracter
    ```
1. O carro está em movimento ou parado?
    ```
    lógico
    ```
1. O valor da nota é 9.5.
    ```
    real
    ```
1. O nome da banda é "The Beatles".
    ```
    caracter
    ```
1. A janela está aberta ou fechada?
    ```
    lógico
    ```
1. A quantidade de açúcar é 250 gramas.
    ```
    inteiro
    ```
1. O número do apartamento é "302".
    ```
    caracter
    ```
1. A luz está acesa ou apagada?
    ```
    lógico
    ```
1. O tempo de corrida foi 2.5 horas.
    ```
    real
    ```
1. O nome do software é "Microsoft Word".
    ```
    caracter
    ```
1. O carro está ligado ou desligado?
    ```
    lógico
    ```
1. A distância até a lua é 384400 quilômetros.
    ```
    inteiro
    ```
1. O nome do livro é "1984".
    ```
    caracter
    ```
1. A temperatura da água é 25 graus Celsius.
    ```
    inteiro
    ```
1. O peso do peixe é 1.7 quilogramas.
    ```
    real
    ```
1. A frase "A resposta é 42" é do livro "Guia do Mochileiro das Galáxias".
    ```
    caracter
    ```
1. O computador está ligado ou desligado?
    ```
    lógico
    ```
1. O número de folhas é 100.
    ```
    inteiro
    ```
1. A massa do planeta é 5.97 x 10^24 quilogramas.
    ```
    real
    ```
1. O nome da cor é "Azul".
    ```
    caracter
    ```
1. A porta está trancada ou destrancada?
    ```
    lógico
    ```
1. O valor da corrente é 0.5 amperes.
    ```
    real
    ```
1. O título do artigo é "Impacto das Mudanças Climáticas".
    ```
    caracter
    ```
1. A lâmpada está ligada ou desligada?
    ```
    lógico
    ```
1. O número de série é "SN12345678".
    ```
    caracter
    ```

</details>

## constantes

Entende-se um dado como constante quando seu valor não sofre qualquer variação no decorrer do tempo, ou seja, o valor é constante do início ao fim da execução do algoritmo. Ele pode ser usado para representar um valor conhecidamente imutável, como o valor 3.14159265 do PI, ou quando não se quer que ele seja alterado durante a execução do algoritmo, como especificar o nome de um autor (J. R. R. Tolkien) de um livro (O Hobbit).

## variáveis

Um dado é classificado como variável quando tem a possibilidade de ser alterado a qualquer momento durante a execução do algoritmo. Por exemplo, calcular a média de uma turma somando todas as notas e depois dividindo pela quantidade de alunos, ou usar um contador para contar quantas vezes é realizada uma repetição de alguma coisa, como o quicar de uma bola no chão.

Um exemplo prático de ambos os casos (variáveis e constantes) seria o uso de uma fórmula matemática. O cálculo da área do círculo é dado por pi vezes o raio ao quadrado. O pi é o valor constante da fórmula, ele jamais vai mudar. Enquanto que o raio é a variável, onde a cada execução ele poderá ter um valor diferente.

## declarando variáveis

No ambiente computacional, as informações variáveis são guardadas em dispositivos eletrônicos chamados de **memória**. Pode-se imaginar que essa memória é como um armário repleto de gavetas, que são usadas para armazenar objetos.

Esse armário tem diversas gavetas, então é necessário diferenciar uma da outra. Isso é feito com indentificadores, etiquetas, rótulos. Cada gaveta (variável) pode guardar apenas um dado, um objeto de cada vez.

> [!NOTE]
> o Python, diferente de outras linguagens como C, C++, Java, não possui variáveis restritas a um tipo primitivo; uma variável pode ser hora inteiro, hora uma lista, hora uma string;

Portanto, é preciso definir nomes para determinadas gavetas especificando qual o material dos objetos que lá estão armazenados. Declarar variáveis é usado para identificar dados.

Por exemplo :
- nome = "Arnold"
- idade = 76
- altura = 1.88

### nomes

Para declarar uma variável, é necessário seguir algumas regras :
- elas devem começar por um caractere alfabético;
- podem ser seguidos por mais caracteres alfanuméricos e sublinhado;
- não podem ser usados caracteres especias;
- não pode haver espaço entre as palavras de identificação das variáveis;
- exemplo :
    - nomes válidos : nome, idade, id4d3, nome_completo, imc;
    - nomes inválidos : 1nome, 4_altura, !passagem, nome completo;

Também há algumas boas práticas para serem seguidas :
- não usar acentuação nos nomes de variáveis;
- usar o padrão de nomenclatura [*snake_case*](https://www.alura.com.br/artigos/convencoes-nomenclatura-camel-pascal-kebab-snake-case#snake-case) para as variáveis, constantes, funções;
- usar o padrão SCREAMING_SNAKE_CASE para constantes;

O Python usa essas convenções de boas práticas para facilitar a legibilidade dos códigos e padronizar. Também é necessário que se faça um nome para as variáveis que faça sentido com o dado que ela armazenará.

- usar `x = "Schwarzenegger` não é claro quanto a que a variável armazena;
- usar `sobrenome = "Schwarzenegger` torna muito mais claro que tipo de dado aquela variável guarda;

<details>
    <summary>Lista de Exercícios</summary>

Identifique quais são e o porquê dos nomes de variáveis serem válidos ou inválidos :

1. variavel1
1. 2variavel
1. var_iavel
1. var-iavel
1. variavel nome
1. #variavel
1. variavel_
1. var@iavel
1. variavel!
1. variavel#
1. variavel
1. variável
1. vari_avel
1. var*
1. var&
1. variavel.
1. variavel,
1. variavel;
1. variavel:
1. variavel?
1. variavel<
1. variavel>
1. variavel=
1. variavel+
1. variavel-
1. variavel/
1. variavel\\
1. variavel|
1. variavel~
1. variavel$
1. variavel%
1. variavel^
1. variavel(
1. variavel)
1. variavel[
1. variavel]
1. variavel{
1. variavel}
1. variavel"1
1. variavel'1
1. variavel1'
1. variavel 1
1. variavel
1. variavel
1. var__iavel
1. (variavel)
1. -var_iavel
1. variavel___
1. variavel__
1. variavel_1_

</details>

## expressões aritméticas

É denominado expressão aritmética aquela cujos operadores são aritméticos e cujos operandos são constantes ou variáveis do tipo inteiro ou real.

Os operadores, por sua vez, são o conjunto de símbolos que representa as operações básicas da matemática.

| Operador | Função | Exemplo |
| ---- | ---- | ---- |
| `+` | Adição | `30 + 12`, `X + 12` |
| `-` | Subtração | `2 - 3`, `Y - 12` |
| `*` | Multiplicação | `7 * 3`, `A * Z` |
| `/` | Divisão | `10 / 5`, `n1 / n2` |
| `**` | Potenciação | `2 / 10`, `n2 ** n2` |

> [!TIP]
> Lembre que, uma operação de radiciação (tirar a raiz), nada mais é do que uma operação de potência.
>
> Exemplo : a raiz quadrada de 5 pode ser escreta como `5 ** (1/2)`;

<details>
  <summary>Lista de Exercícios</summary>

Para os exercícios abaixo, use variáveis e constantes quando achar necessário.

1. Exercícios Simples
    1. Calcule a soma de 5 e 3.
        ```
        5 + 3
        ```
    1. Subtraia 8 de 15.
        ```
        15 - 8
        ```
    1. Multiplique 4 por 6.
        ```
        4 * 6
        ```
    1. Divida 20 por 4.
        ```
        20 / 4
        ```
    1. Calcule 2 elevado à potência de 3.
        ```
        2 ** 3
        2 ^ 3
        ```
    1. Calcule a soma de 7, 3 e 2.
        ```
        7 + 3 + 2
        ```
    1. Subtraia 5 de 10 e depois subtraia 3.
        ```
        (10 - 5) - 3
        ```
    1. Multiplique 3, 2 e 4.
        ```
        3 * 2 * 4
        ```
    1. Divida 25 por 5 e depois por 2.
        ```
        (25 / 5) / 2
        ```
    1. Calcule 5 elevado à potência de 2 e subtraia 3.
        ```
        (5 ** 2) - 3
        ```
1. Exercícios de Nível Intermediário
    1. Calcule a soma de 4, 5 e 6 e depois multiplique o resultado por 2.
        ```
        (4 + 5 + 6) * 2
        ```
    1. Subtraia 10 de 25, depois divida o resultado por 3.
        ```
        (25 - 10) / 3
        ```
    1. Calcule 3 elevado à potência de 2 e depois adicione 7.
        ```
        (3 ** 2) + 7
        ```
    1. Multiplique 8 por 3, depois subtraia 10.
        ```
        (8 * 3) - 10
        ```
    1. Divida 36 por 6, depois adicione 2 e multiplique por 3.
        ```
        ((36 / 6) + 2) * 3
        ```
    1. Calcule 2 elevado à potência de 4 e depois subtraia 5.
        ```
        (2 ** 4) - 5
        ```
    1. Calcule a soma de 6 e 7, depois divida o resultado por 2.
        ```
        (6 + 7) / 2
        ```
    1. Subtraia 14 de 28, depois multiplique o resultado por 3.
        ```
        (28 - 14) * 3
        ```
    1. Calcule 4 elevado à potência de 3 e depois adicione 5.
        ```
        (4 ** 3) + 5
        ```
    1. Multiplique 9 por 4, depois subtraia 15 e divida o resultado por 3.
        ```
        ((9 * 4) - 15) / 3
        ```
1. Exercícios Avançados
    1. Calcule a soma de 5, 8 e 12, depois multiplique o resultado por 2 e subtraia 10.
        ```
        ((5 + 8 + 12) * 2) - 10
        ```
    1. Subtraia 15 de 45, depois divida o resultado por 5 e adicione 7.
        ```
        ((45 - 12) / 5) + 7
        ```
    1. Calcule 2 elevado à potência de 5 e depois subtraia 9 e multiplique por 2.
        ```
        ((2 ** 5) - 9) * 2
        ```
    1. Multiplique 7 por 6, depois adicione 10 e divida por 4.
        ```
        ((7 * 6) + 10) / 4
        ```
    1. Divida 72 por 8, depois adicione 5 e multiplique por 3.
        ```
        ((72 / 8) + 5) * 3
        ```
    1. Calcule 3 elevado à potência de 3 e depois subtraia 8 e divida por 2.
        ```
        ((3 ** 3) - 8) / 2
        ```
    1. Calcule a soma de 9 e 14, depois multiplique por 3 e subtraia 5.
        ```
        ((9 + 14) * 3) - 5
        ```
    1. Subtraia 20 de 60, depois divida por 4 e adicione 7.
        ```
        ((60 - 20) / 4) + 7
        ```
    1. Calcule 4 elevado à potência de 4 e depois subtraia 20 e multiplique por 2.
        ```
        ((4 ** 4) - 20) * 2
        ```
    1. Multiplique 10 por 5, depois adicione 8 e divida por 6.
        ```
        ((10 * 5) + 8) / 6
        ```
1. Exercícios Complexos
    1. Calcule a soma de 12, 8 e 5, depois multiplique o resultado por 3, subtraia 15 e divida por 2.
        ```
        (((12 + 8 + 5) * 3) - 15) / 2
        ```
    1. Subtraia 18 de 50, depois divida por 4, adicione 7 e multiplique por 3.
        ```
        (((50 - 18) / 4) + 7) * 3
        ```
    1. Calcule 5 elevado à potência de 3, depois subtraia 10, multiplique por 2 e adicione 8.
        ```
        (((5 ** 3) - 10) * 2) + 8
        ```
    1. Multiplique 6 por 7, depois adicione 12, divida por 3 e subtraia 4.
        ```
        (((6 * 7) + 12) / 3) - 4
        ```
    1. Divida 81 por 9, depois adicione 5, multiplique por 4 e subtraia 10.
        ```
        (((81 / 9) + 5) * 4) - 10
        ```
    1. Calcule 2 elevado à potência de 6, depois subtraia 20, divida por 2 e multiplique por 3.
        ```
        (((2 ** 6) - 20) / 2) * 3
        ```
    1. Calcule a soma de 7, 13 e 18, depois multiplique por 4, subtraia 25 e divida por 5.
        ```
        (((7 + 13 + 18) * 4) - 25) / 5
        ```
    1. Subtraia 30 de 90, depois divida por 5, adicione 9 e multiplique por 2.
        ```
        (((90 - 30) / 5) + 9) * 2
        ```
    1. Calcule 3 elevado à potência de 4, depois subtraia 50, multiplique por 3 e adicione 20.
        ```
        (((3 ** 4) - 50) * 3) + 20
        ```
    1. Multiplique 8 por 9, depois adicione 20, divida por 7 e subtraia 3.
        ```
        (((8 * 9) + 20) / 7) - 3
        ```
1. Exercícios Muito Complexos
    1. Calcule a soma de 15, 9 e 7, depois multiplique por 2, subtraia 10, divida por 3 e adicione 5.
        ```
        ((((15 + 9 + 7) * 2) - 10) / 3) + 5
        ```
    1. Subtraia 25 de 100, depois divida por 5, adicione 8, multiplique por 3 e subtraia 7.
        ```
        ((((100 - 25) / 5) + 8) * 3) - 7
        ```
    1. Calcule 4 elevado à potência de 3, depois subtraia 15, multiplique por 2, adicione 10 e divida por 5.
        ```
        ((((4 ** 3) - 15) * 2) + 10) / 5
        ```
    1. Multiplique 11 por 6, depois adicione 30, divida por 4, subtraia 8 e multiplique por 2.
        ```
        ((((11 * 6) + 30) / 4) - 8) * 2
        ```
    1. Divida 144 por 12, depois adicione 7, multiplique por 3, subtraia 20 e divida por 2.
        ```
        ((((144 / 12) + 7) * 3) - 20) / 3
        ```
    1. Calcule 5 elevado à potência de 4, depois subtraia 30, divida por 2, multiplique por 3 e adicione 10.
        ```
        ((((5 ** 4) - 30) / 2) * 3) + 10
        ```
    1. Calcule a soma de 8, 14 e 22, depois multiplique por 5, subtraia 40, divida por 4 e adicione 6.
        ```
        ((((8 + 14 + 22) * 5) - 40) / 4) + 6
        ```
    1. Subtraia 50 de 200, depois divida por 10, adicione 15, multiplique por 2 e subtraia 5.
        ```
        ((((200 - 50) / 10)/ + 15) * 2) - 5
        ```
    1. Calcule 6 elevado à potência de 3, depois subtraia 40, multiplique por 4, adicione 25 e divida por 3.
        ```
        ((((6 ** 3) - 40) * 4) + 25) / 3
        ```
    1. Multiplique 9 por 7, depois adicione 50, divida por 5, subtraia 10, multiplique por 3 e adicione 15.
        ```
        (((((9 * 7) + 50) / 5) - 10) * 3) + 15
        ```

</details>

Ainda há alguns operadores aritméticos não usuais, mas que são muito úteis na construção de algoritmos. São eles o `resto` da divisão inteira e o `quociente` da divisão inteira. Cada um traz como resultado o que é especificado.

| Operador | Função | Exemplo |
| ---- | ---- | ---- |
| `%` | Resto | `12 % 3`, `X % 11` |
| `//` | Quociente | `10 // 3`, `X // 20` |

Por exemplo :
- `11 % 3` irá retornar o resto da divisão, que será `2`;
- `11 // 3` irá retornar o quociente da divisão, que será `3`;

Os operadores de resto e quociente inteiros são úteis em diversos cenários, entre os quais categorizar números ou separar seus algarismos.

Por exemplo, para verificar se um número é par ou ímpar, basta verificar o resto da divisão por 2. Os restos possíveis para essa divisão são apenas 2, `1` ou `0`. Números pares sempre irão gerar resto igual a zero, enquanto que números ímpares sempre irão gerar um resto igual a um.

- `12 % 2` terá como resto 0;
- `11 % 2` terá como resto 1;

Ele também pode ser usado para separar um número inteiro. Para isso, basta realizar divisões sucessivas por 10 para obter seus algarismos.

Por exemplo :
- `1947 % 10` terá como resto 7 (unidade);
- `194 % 10` terá como resto 4 (dezena);
- `19 % 10` terá como resto 9 (centena);
- `1 % 10` terá como resto 1 (milhas);

## parênteses

Diferente da matemática, onde se usam parênteses `()`, colchetes `[]` e chaves `{}` para representar diferentes níveis de uma equação, na programação usa-se apenas parênteses `()`, em todos os níveis. Veja uma comparação abaixo :
- na `matemática` : 7 * {4 - [2 / (1 + 2)] * 10}
- na `programação` : 7 * (4 - (2 / (1 + 2)) * 10)

Isso permite criar níveis muito profundos de uso de parênteses :
- 7 + (4 * 1 + (3 / (2 - (9 * 4) - (1 * 1) / 3) + (2 * 21)) + 10)

## prioridades

Na resolução das expressões aritméticas, as operações guardam uma hierarquia entre si

| prioridade | operadores |
| :----: | :----: |
| 1 | parênteses mais internos |
| 2 | ** |
| 3 | * / % // |
| 4 | + - |

Em caso de empate (operadores de mesma prioridade), deve-se resolver da esquerda para a direita, conforme a sequência da própria expressão. Se for necessário alterar essa prioridade, usa-se parênteses. Veja alguns exemplos :
```
5 + 9 + 3 / 2
5 + 9 + 1.5
14 + 1.5
15.5
```

```
5 + (9 + 3) / 2
5 + 12 / 2
5 + 6
11
```

<details>
  <summary>Mais Exercícios</summary>

1. Exercícios Simples
    1. Calcule o resto da divisão de 15 por 4.
        ```
        15 % 4 = 3
        ```
    1. Encontre o quociente da divisão inteira de 20 por 3.
        ```
        20 // 3 = 6
        ```
    1. Calcule 25 % 6 + 8.
        ```
        25 % 6 + 8
        1 + 8 = 9
        ```
    1. Encontre o quociente da divisão de 45 por 7 e adicione 3.
        ```
        45 // 7 + 3
        6 + 3 = 9
        ```
    1. Calcule o resto da divisão de 30 por 5 e multiplique por 4.
        ```
        30 % 5 * 4
        0 * 4 = 0
        ```
1. Exercícios de Nível Intermediário
    1. Encontre o quociente da divisão de 50 por 8 e subtraia 2.
        ```
        (50 // 8) - 2
        6 - 2 = 4
        ```
    1. Calcule 18 % 5 + 3 * 2.
        ```
        (18 % 5) + (3 * 2)
        3 + 6 = 9
        ```
    1. Encontre o quociente da divisão de 35 por 4 e multiplique por 2.
        ```
        35 // 4 * 2
        8 * 2 = 16
        ```
    1. Calcule o resto da divisão de 40 por 9 e adicione 7.
        ```
        40 % 9 + 7
        4 + 7 = 11
        ```
    1. Encontre o quociente da divisão de 60 por 11 e adicione o resto da divisão de 27 por 4.
        ```
        60 // 11 + 27 % 4
        5 + 3 = 8
        ```
1. Exercícios Avançados
    1. Calcule 48 % 10 + 6 // 3.
        ```
        48 % 10 + 6 // 3
        8 + 2 = 10
        ```
    1. Encontre o quociente da divisão de 81 por 9 e subtraia 5 % 2.
        ```
        81 // 9 - 5 % 2
        9 - 1 = 8
        ```
    1. Calcule 9 ** 2 % 7 + 4.
        ```
        81 % 7 + 4
        4 + 4 = 8
        ```
    1. Encontre o quociente da divisão de 100 por 15 e multiplique por 3 % 4.
        ```
        100 // 15 * 3 % 4
        6 * 3 % 4
        18 % 4 = 2
        ```
    1. Calcule o resto da divisão de 64 por 8 e adicione 36 // 6.
        ```
        64 % 8 + 36 // 6
        0 + 6 = 6
        ```
1. Exercícios Complexos
    1. Encontre o quociente da divisão de 49 por 6 e subtraia 14 % 5.
        ```
        49 // 6 - 14 % 5
        8 - 4 = 4
        ```
    1. Calcule 72 % 10 + 7 // 2 * 3.
        ```
        2 + 3 * 3
        2 + 9 = 11
        ```
    1. Encontre o quociente da divisão de 95 por 8 e adicione 25 % 6.
        ```
        95 // 8 + 25 % 6
        11 + 1 = 12
        ```
    1. Calcule 3 ** 3 % 4 + 20 // 3.
        ```
        27 % 4 + 6
        3 + 6 = 9
        ```
    1. Encontre o quociente da divisão de 120 por 11 e subtraia 44 % 7.
        ```
        120 // 11 - 44 % 7
        10 - 2 = 8
        ```
1. Exercícios Muito Complexos
    1. Calcule 150 % 11 + 18 // 4 * 2.
        ```
        7 + 4 * 2
        7 + 8 = 15
        ```
    1. Calcule 6 ** 2 % 5 + 88 // 9.
        ```
        36 % 5 + 9
        1 + 9 = 10
        ```
    1. Calcule o resto da divisão de 220 por 15 e adicione 100 // 7.
        ```
        220 % 15 + 100 // 7
        10 + 14 = 24
        ```
    1. Encontre o quociente da divisão de 140 por 12 e multiplique por 50 % 8.
        ```
        140 // 12 * 50 % 8
        11 * 50 % 8
        550 % 8 = 6
        ```
    1. Encontre o quociente da divisão de 200 por 17 e adicione 60 % 9.
        ```
        200 // 17 + 60 % 9
        11 + 6 = 17
        ```

</details>

## expressões lógicas

É entendido como expressão lógica aquela cujos operadores são lógicos ou relacionais e cujos operadores são relações ou variáveis ou constantes do tipo lógico.

### operadores relacionais

Usa-se `operadores relacionais` para realizar comparações entre dois valores de mesmo tipo primitivo, que podem ser representados como constantes, ou variáveis ou expressões aritméticas. Eles são usados para construir equações.

| Operador | Função | Exemplo |
| :----: | :----: | :----: |
| `==` | igual a | `3 == 2`, `"a" == "a"` |
| `>` | maior que | `5 > 4`, `X > Y` |
| `<` | menor que | `5 < 4`, `A < Z` |
| `>=` | maior ou igual a | `12 >= 5`, `C >= A` |
| `<=` | menor ou igual a | `12 <= 5`, `C <= A` |
| `!=` | diferente de | `2 != 10`, `n2 != n2` |

O resultado obetido de uma relação é sempre um valor **lógico**. Por exemplo, analisando a relação numérica `X + Y == Z`, o resultado será verdade ou falso à medida que o valor da expressão aritmética `X + Y` seja igual ou diferente do conteúdo da variável `C`.

### operadores lógicos

Existem três `operadores lógicos` básicos que são usados para a formação de novas proposições lógicas compostas a partir de outras proposições lógicas simples.

| Operador | Função |
| :----: | :----: |
| `not` | negação |
| `and` | conjunção |
| `or` | disjunção |

### tabelas-verdade

Tabela-verdade é o conjunto de todas as possibilidades combinatórias entre os valores de diversas variáveis lógicas, as quais se encontram em apenas duas situações (True para verdadeiro ou False para falso), e um conjunto de operadores lógicos.

Veja as tabelas verdades :

- Operação de negação

| A | not A |
| :----: | :----: |
| `True` | `False` |
| `False` | `True` |

- Operação de conjunção

| A | B | A and B |
| :----: | :----: | :----: |
| `True` | `True` | `True` |
| `True` | `False` | `False` |
| `False` | `True` | `False` |
| `False` | `False` | `False` |

- Operação de disjunção

| A | B | A or B |
| :----: | :----: | :----: |
| `True` | `True` | `True` |
| `True` | `False` | `True` |
| `False` | `True` | `True` |
| `False` | `False` | `False` |

Alguns exemplos práticos :
- Se chover `e` trovejar, eu fico em casa.
    - Como é possível ver, usou-se o conectivo `e` (que no Python é usado como `and`) para verificar se a proposição *ficar em casa* será satisfeita. A pessoa ficará em casa apenas se chover **E** trovejar, se ambas forem verdade ao mesmo tempo.<br><br>
- Se chover `ou` trovejar, eu fico em casa.
    - Agora, usando o operadore `ou` (que no Python é usado como `or`) indica que a pessoa ficará vem casa se chover **OU** se trovejar, aumentando as chaves de não sair de casa.<br><br>
```python
2 < 5 and 15/3 == 6
 True and 5 == 6
 True and False
     False
```
```python
2 < 5 or 15/3 == 6
 True or 5 == 6
 True or False
     True
```
```python
False or 20 // (18 / 3) != (21 / 3) // 2
False or 20 // 6 != 7 // 2
False or 3 != 3
False or False
    False
```
```python
not True or (3 ** 2) / 3 < 15 - 35 % 7
not True or 9 / 3 < 15 - 0
not True or 3 < 15
not True or True
   False or True
        True
```

### prioridades

Vaja na tabela abaixo a prioridade entre os operadores lógicos :

| prioridade | operadores |
| :----: | :----: |
| 1 | not |
| 2 | and |
| 3 | or |

E por fim, veja a prioridade entre todos os operadores :

| prioridade | operadores |
| :----: | :----: |
| 1 | parênteses mais internos |
| 2 | operadores aritméticos |
| 3 | operadores relacionais |
| 4 | operadores lógicos |

<details>
  <summary>Lista de Exercícios</summary>

1. Exercícios Simples
    1. Verifique se 5 + 3 é igual a 8.
        ```
        5 + 3 == 8
        True
        ```
    1. Verifique se 10 - 4 é diferente de 5.
        ```
        10 - 4 != 5
        True
        ```
    1. Verifique se 7 * 2 é maior que 13.
        ```
        7 * 2 > 13
        True
        ```
    1. Verifique se 16 / 4 é menor ou igual a 4.
        ```
        16 / 4 <= 4
        True
        ```
    1. Verifique se 3 ** 2 é maior ou igual a 9.
        ```
        3 ** 2 >= 9
             9 >= 9
              True
        ```
1. Exercícios de Nível Intermediário
    1. Verifique se 12 % 5 é igual a 2 e 3 * 4 é maior que 11.
        ```
        12 % 5 == 2 and 3 * 4 > 11
             2 == 2 and 12 > 11
               True and True
                   True
        ```
    1. Verifique se 15 // 2 é diferente de 7 ou 8 + 2 é menor que 11.
        ```
        15 // 2 != 7 or 8 + 2 < 11
        True
        ```
    1. Verifique se 18 % 4 é igual a 2 e 9 / 3 é igual a 3.
        ```
        18 % 4 == 2 and 9 / 3 == 3
        True
        ```
    1. Verifique se 5 ** 2 é menor que 30 ou 6 - 1 é maior que 4.
        ```
        5 ** 2 < 30 or 6 - 1 > 4
        True
        ```
    1. Verifique se 20 // 3 é maior ou igual a 6 e 7 + 8 é igual a 15.
        ```
        20 // 3 >= 6 and 7 + 8 == 15
        True
        ```
1. Exercícios Avançados
    1. Verifique se 25 % 7 é menor que 4 e 3 ** 2 é igual a 9.
        ```
        25 % 7 < 4 and 3 ** 2 == 9
             4 < 4 and 9 == 9
             False and True
                  False
        ```
    1. Verifique se 14 // 5 é maior que 2 ou 10 / 2 é diferente de 5.
        ```
        14 // 5 > 2 or 10 / 2 != 5
        False
        ```
    1. Verifique se 30 % 8 é igual a 6 e 5 * 2 é menor ou igual a 10.
        ```
        30 % 8 == 6 and 5 * 2 <= 10
        True
        ```
    1. Verifique se 27 // 4 é menor que 7 ou 4 ** 2 é igual a 16.
        ```
        27 // 4 < 7 or 4 ** 2 == 16
        True
        ```
    1. Verifique se 21 % 6 é diferente de 3 e 12 / 4 é maior ou igual a 3.
        ```
        21 % 6 != 3 and 12 / 4 >= 3
        False
        ```
1. Exercícios Complexos
    1. Verifique se 35 % 9 é menor que 8 e 6 // 2 é igual a 3.
        ```
        35 % 9 < 8 and 6 // 2 == 3
        False
        ```
    1. Verifique se 40 // 7 é maior que 5 ou 9 ** 2 é diferente de 81.
        ```
        40 // 7 > 5 or 9 ** 2 != 81
        True
        ```
    1. Verifique se 48 % 11 é igual a 4 e 10 * 2 é maior que 19.
        ```
        48 % 11 ==F 4 and 10 * 2 > 19
              4 == 4 and 20 > 19
                True and True
                    True
        ```
    1. Verifique se 50 // 6 é menor ou igual a 8 ou 12 / 3 é igual a 4.
        ```
        50 // 6 <= 8 or 12 / 3 == 4
        True
        ```
    1. Verifique se 33 % 7 é maior que 3 e 14 - 6 é menor ou igual a 8.
        ```
        33 % 7 > 3 and 14 - 6 <= 8
        True
        ```
1. Exercícios Muito Complexos
    1. Verifique se 100 % 12 é diferente de 4 e 11 * 3 é menor que 34.
    1. Verifique se 12 * 5 é maior que 59 and 20 // 5 é igual a 4.
    1. Verifique se 15 % 4 é igual a 3 and 9 ** 2 é maior que 80.
    1. Verifique se 18 % 7 é igual a 4 or 32 / 4 é maior que 8.
    1. Verifique se 18 / 3 é diferente de 6 and 12 * 2 é maior que 22.
    1. Verifique se 20 + 10 é igual a 30 or 15 // 3 é menor ou igual a 5.
    1. Verifique se 24 / 4 é maior que 5 and 11 - 6 é diferente de 5.
    1. Verifique se 25 - 5 é igual a 20 or 14 + 6 é menor que 21.
    1. Verifique se 27 % 4 é igual a 3 or 7 ** 2 é menor ou igual a 49.
    1. Verifique se 28 + 7 é diferente de 35 or 21 // 7 é menor que 4.
    1. Verifique se 30 + 15 é maior que 44 or 27 // 9 é igual a 3.
    1. Verifique se 30 // 5 é maior que 5 and 9 + 6 é igual a 15.
    1. Verifique se 33 // 5 é maior ou igual a 6 and 18 - 9 é igual a 9.
    1. Verifique se 35 - 7 é diferente de 28 or 16 / 4 é igual a 4.
    1. Verifique se 36 / 6 é igual a 6 and 7 ** 2 é diferente de 50.
    1. Verifique se 40 % 7 é menor que 6 or 12 * 2 é igual a 24.
    1. Verifique se 40 // 5 é maior que 7 and 8 ** 2 é igual a 64.
        ```
        40 // 5 > 7 and 8 ** 2 == 64
              8 > 7 and 64 == 64
               True and True
                   True
        ```
    1. Verifique se 45 % 8 é menor que 6 and 14 * 2 é igual a 28.
    1. Verifique se 50 - 20 é maior que 29 or 25 + 6 é igual a 31.
    1. Verifique se 55 // 6 é maior que 9 and 22 + 8 é igual a 30.
    1. Verifique se 60 % 13 é igual a 8 e 15 // 4 é diferente de 3.
    1. Verifique se 60 - 25 é diferente de 34 or 10 ** 2 é igual a 100.
    1. Verifique se 70 // 8 é menor que 9 ou 8 ** 2 é igual a 64.
    1. Verifique se 75 + 25 é igual a 100 or 45 % 6 é menor que 4.
    1. Verifique se 8 ** 2 é maior que 63 and 14 % 3 é igual a 2.
    1. Verifique se 80 - 30 é maior ou igual a 50 and 6 ** 3 é diferente de 216.
    1. Verifique se 81 % 10 é menor ou igual a 1 e 18 / 2 é maior que 8.
    1. Verifique se 9 + 3 é maior que 11 and 15 - 7 é igual a 8.
    1. Verifique se 90 // 11 é maior que 8 ou 20 - 5 é igual a 15.
    1. Verifique se 99 - 11 é diferente de 88 or 18 / 3 é igual a 6.

</details>

## comando de atribuição

Um comando de atribuição permite armazenar um valor em uma variável (ainda usando a analogia do armário, equivalente a guardar na gaveta). Para o comando de atribuição funcionar, é usado o sinal de igual `=`.

Veja exemplos :
- `numero = 10`
- `nome_completo = 'Arnold Schwarzenegger'`

A ordem de atribuição será sempre da direita para a esquerda, isto é, a variável `nome` está recebendo a string `'Arnold Schwarzenegger'` para ser armazenada dentro dela. Tenha em mente que, se outro nome for atribuído à variáve, o valor antigo será perdido para todo sempre.

Sempre use nome de variáveis que sejam compatíveis com o que ela vai armazenar, isso facilita a ligibilidade do código.
