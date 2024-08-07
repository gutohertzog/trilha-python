Índice Introdução à Lógica de Programação

1. [o que é lógica](#o-que-é-lógica)
1. [lógica no dia a dia](#lógica-no-dia-a-dia)
1. [e a lógica de programação](#e-a-lógica-de-programação)
1. [o que é um algoritmo](#o-que-é-um-algoritmo)
1. [algoritmizando a lógica](#algoritmizando-a-lógica)
1. [resumo](#resumo)
1. [atividades](#atividades)

# introdução à lógica de programação

## o que é lógica

O uso corriqueiro da palavra lógica está normalmente relacionado à coerência e à racionalidade. Frequentemente se associa lógica apenas à matemática, não se percebendo sua aplicabilidade e sua relação com as demais ciências, bem como seu emprego cotidiano nas ações do dia a dia, quando alguma decisão é tomada de forma racional.

A lógica pode ser relacionada com a *correção do pensamento*, pois uma de suas preocupações é determinar quais operações são válidas e quais não são. Como filosifia, ela procura saber porque pensamos assim e não de outro jeito. Com arte ou técnica, ela nos ensina a usar corretamente as leis do pensamento.

Pode-se dizer que a lógica é a *arte de bem pensar*, que é a *ciência das formas do pensamento*. Como a forma mais complexa de pensamento é o raciocínio, a lógica estuda a *correção do raciocínio*. Pode-se dizer ainda que a lógica tem em vista a *ordem da razão*. Isso dá a entender que a nossa razão pode funcionar desordenadamente. Por isso, a lógica estuda e ensina a colocar `ordem no pensamento`.

Exemplos :
- Todo mamífero é um animal. Todo cavalo é um mamífero. Portanto, todo cavalo é um animal;
- Kaiton é um país do planeta Stix. Todos os Xinpins são de Kaiton. Logo, todos os Xinpins são Stixianos;

Esses exemplos ilustram silogismos, que no estudo da Lógica Proposicional representam um argumento composto de duas premissas e uma conclusão; e está estabelecendo uma relação, que pode ser válida ou não. Esse é um dos objetivos da lógica, o estudo de técnicas de formalização, dedução e análise que permitam verificar a validade de argumentos. No caso dos exemplos, ambos são válidos.

Vale a pena ressaltar que, apesar da aparente coerência de um encadeamento lógico, ele pode ser válido ou nãp em sua estrutura. Nesse sentido, a lógica também objetiva a criação de uma representação mais formal, contrapondo-se à linguagem natural, que é suscetível a argumentações informais e problemas de interpretação.

Exemplos :
- Todo escorpião é um invertebrado. Algumas pessoas são de escorpião. Logo, algumas pessoas são invertebradas;

## lógica no dia a dia

Sempre que há um pensamento, a lógica ou a ilógica necessariamente acompanha. Quando se escreve ou fala, um pensamento está sendo expressado, logo é necessário usar lógica nessas atividades. Pode-se perceber a importância da lógica na vida, não só na teoria, como na prática. Quando se quer falar, pensar ou agir corretamente, é preciso colocar *ordem no pensamento*, isto é, usar a lógica.

Exemplos :
- A gaveta está fechada. A caneta está dentro da gaveta. É preciso primeiro abrir a gaveta para depois pegar a caneta;
- Anastácia é mais velha que Gioconda. Gioconda é mais velha que Lucineide. Portanto, Anastácia é mais velha que Lucineide;

## e a lógica de programação

Significa o uso correto s leis do pensamento, da *ordem da razão* e de processos de raciocínio e simbolização formais na programação de computadores, objetivando a racionalidade e o desenvolvimento de técnicas que cooperem para a produção de soluções logicamente válidas e coerentes, que resolvam os problemas que se deseja programar.

O raciocínio é algo abstrato. Os seres humanos têm a capacidade de expressá-lo através da palavra falada ou escrita, que por vez, se baseia em um determinado idioma, que segue uma série de padrões. Um mesmo racioncínio pode ser expresso em qualquer um dos idiomas existentes, mas continuará representando o mesmo raciocínio, usando apenas outra convenção.

Algo similar acontece com a Lógica de Programação, que pode ser criada pela mente treinada e pode ser representada em qualquer uma das inúmeras linguagens de programação existentes. Essas, por sua vez, são atreladas a uma grande diversidade de detalhes computacionais, que pouco têm a ver com o raciocínio original. Para escapar desse problema e, ao mesmo tempo, representar mais fielmente o racioncínio da Lógica de Programação, é utilizado os Algoritmos.

## o que é um algoritmo

Um algoritmo pode ser definido como uma sequência finita de passos que visam atingir um objetivo bem definido.

Na medida em que é preciso especificar uma sequência de passos, é necessário *pensar com ordem*, portanto precisa-se utilizar a lógica.

Apesar do nome pouco usual, algoritmos são comuns no cotidiano. Uma receita de bolo, por exemplo. Nela está descrita uma série de ingredientes necessários e uma sequência de passos (ações) que devem ser seguidos para que se consiga fazer o bolo pretendido.

Quando se faz um algoritmo, é ncessário especificar as ações clara e precisamente. A partir de um estado iniciale após um preríodo de tempo finito, será produzido um estado final previsível e bem definido. O algoritmo fixa um padrão de comportamento a ser seguido.

## algoritmizando a lógica

Uma importância da construção dos Algoritmos é que uma vez concebida uma solução algorítmica para um problema, esta pode ser traduzida para qualquer linguagem de programação.

### a lâmpada

Um primeiro algoritmo pode ser escrito utlizando o portuquês coloquial. Ele vai descrever o comportamento na resolução de uma determinada atividade, como trocar uma lâmpada. Mesmo sendo uma atividade óbvia, ela é realizada de maneira inconscientemente, sem se atentar aos detalhes, que são as ações que levam a alcançar o objetivo.

Vamos ao algoritmo.

Algoritmo Troca de Lâmpada v1.0 :
- pegar uma escada;
- colocar a escada embaixo da lâmpada;
- buscar uma lâmpada reserva;
- subir na escada;
- retirar a lâmpada velha;
- colocar a lâmpada reserva;
- jogar fora a lâmpada velha;
- guardar a escada;

Esses são os passos gerais para trocar uma lâmpada. Seguimos esses passos involuntariamente e pode ser usado por qualquer pessoa. Mas, e se a lâmpada não estivesse queimada? A execução dos passos levaria a uma troca, mesmo ela estando ou não queimada, já que essa possibilidade não foi prevista nos passos.

Então, para corrigir isso, será feito um teste para verificar se a lâmpada está ou não queimada. Veja como fica o novo algoritmo.

Algoritmo Troca de Lâmpada v1.1 :
- pegar uma escada;
- colocar a escada embaixo da lâmpada;
- buscar uma lâmpada reserva;
- ligar o interruptor;
- se a lâmpada não ligar, então :
    - subir na escada;
    - retirar a lâmpada velha;
    - colocar a lâmpada reserva;
    - jogar fora a lâmpada velha;
- guardar a escada;

Agora há ações relacionadas à condição da `lâmpada não ligar`, ou seja, se essa condição for verdadeira (a lâmpada estiver queimada) será feita a troca dela seguindo as ações :
- subir na escada;
- retirar a lâmpada velha;
- colocar a lâmpada reserva;
- jogar fora a lâmpada velha;

Se a condição `lâmpada não ligar` for falsa (se a lâmpada estiver funcionando), as ações relativas à troca dela não serão executadas e não será trocada.

Note, também, que a condição de *guardar da escada* só irá acontecer com ou sem a troca da lâmpada. Mas isso também tem um problema, o algoritmo não prevê guardar a lâmpada nova, caso a velha ainda funcione.

O que aconteceu em v1.1 foi a inclusão de um teste seletivo, usando uma condição que determina qual ou quais ações serão executadas se a condição resultar em verdadeiro. Diferente da v1.0, onde tudo era executado.

Apesar do algoritmo funcionar corretamente, ele pode ser melhorado. Qual é o objetivo de pegar a escada e uma nova lâmpada *antes* de verificar se a lâmpada em questão está queimada? Podemos executar as ações de pegar uma escada e lâmpada apenas se a lâmpada não ligar.

Algoritmo Troca de Lâmpada v1.2
- ligar o interruptor;
- se a lâmpada não ligar, então :
    - pegar uma escada;
    - colocar a escada embaixo da lâmpada;
    - buscar uma lâmpada reserva;
    - subir na escada;
    - retirar a lâmpada velha;
    - colocar a lâmpada reserva;
    - jogar fora a lâmpada velha;
    - guardar a escada;

Observer que, agora, a opção de `ligar o interruptor` é a primeira ação do algoritmo. Em seguida, a condição `lâmpada não ligar` já é testada. Agora, as opções de pegar uma lâmpada e a escada dependem da lâmpada estar queimada.

### repetição

Embora a solução de v1.2 seja adequada, ela não considera que a nova lâmpada também esteja queimada e, portanto, não atingir o objetivo do algoritmo. É possível fazer uma melhoria no algoritmo para que se troque a lâmpada diversas vezes, se necessário, até que funcione.

Algoritmo Troca de Lâmpada v1.3
- ligar o interruptor;
- se a lâmpada não ligar, então :
    - pegar uma escada;
    - colocar a escada embaixo da lâmpada;
    - buscar uma lâmpada reserva;
    - subir na escada;
    - retirar a lâmpada velha;
    - colocar a lâmpada reserva;
    - jogar fora a lâmpada velha;
    - se a lâmpada não ligar, então :
        - retirar a lâmpada velha;
        - colocar a lâmpada reserva;
        - jogar fora a lâmpada velha;
        - se a lâmpada não ligar, então :
            - retirar a lâmpada velha;
            - colocar a lâmpada reserva;
            - jogar fora a lâmpada velha;
            - se a lâmpada não ligar, então :
                - retirar a lâmpada velha;
                - colocar a lâmpada reserva;
                - .
                - .
                - ao infinito e além!
    - guardar a escada;

Pode-se ver que o algoritmo não tem fim. Não há como especificar até quando será feito o teste da lâmpada, quando termina. As ações são executadas até a lâmpada ligar, caso contrário ela será testada até o fim dos tempos. Embora essa solução eventualmente atinja o objetivo (colocar uma lâmpada que funcione), há o problema do número exato de testes da lâmpada.

Veja que o teste da lâmpada reserva é efetuado pelo mesmo conjunto de ações :
- se a lâmpada não ligar, então :
    - retirar a lâmpada velha;
    - colocar a lâmpada reserva;

Também, veja que a condição `guardar a escada` só acontecerá após todos os testes das lâmpada funcionar corretamente.

A condição da `lâmpada não ligar` permaneceu e é estabelecido um fluxo repetitivo que só é finalizado quando a condição de parada for falsa (a lâmpada não ligar). Pode-se ver que o número de repetições é *indefinido*, mas é *finito* e que depende apenas da condição estabelecida. Dessa forma, ocorre uma repetição de ações até alcançar o objetivo: trocar a lâmpada queimada por uma que funcione.d

Veja como fica o novo algoritmo :

Algoritmo Troca de Lâmpada v1.4
- ligar o interruptor;
- se a lâmpada não ligar, então :
    - pegar uma escada;
    - colocar a escada embaixo da lâmpada;
    - buscar uma lâmpada reserva;
    - subir na escada;
    - retirar a lâmpada velha;
    - colocar a lâmpada reserva;
    - jogar fora a lâmpada velha;
    - enquanto a lâmpada não ligar, faça :
        - retirar a lâmpada velha;
        - colocar a lâmpada reserva;
        - jogar fora a lâmpada velha;
    - guardar a escada;

Na versão v1.4, é feito um teste de troca de lâmpada e que, enquanto a condição não for verdadeira, ele será repetido indefinidamente.

Até o momento, está sendo testado apenas um ponto de luz, um soquete. E se fosse necessário trocar 10 pontos de luz?

Algoritmo Troca de Lâmpada v1.5
- ligar o `primeiro` interruptor;
- se a lâmpada não ligar, então :
    - pegar uma escada;
    - colocar a escada embaixo da lâmpada;
    - buscar uma lâmpada reserva;
    - subir na escada;
    - retirar a lâmpada velha;
    - colocar a lâmpada reserva;
    - jogar fora a lâmpada velha;
    - enquanto a lâmpada não ligar, faça :
        - retirar a lâmpada velha;
        - colocar a lâmpada reserva;
        - jogar fora a lâmpada velha;
    - guardar a escada;
- ligar o `segundo` interruptor;
- se a lâmpada não ligar, então :
    - pegar uma escada;
    - colocar a escada embaixo da lâmpada;
    - .
    - .
    - .
- ligar o `terceiro` interruptor;
- se a lâmpada não ligar, então :
    - .
    - .
    - .
- ligar o `quarto` interruptor;
    - .
    - .
    - .
- ligar o `quinto` interruptor;
- se a lâmpada não ligar, então :
    - .
    - .
    - .

Repare que o algoritmo v1.5 é apenas um conjunto de 10 repetições da versão v1.4. Como o conjunto de ações repetidas é igual, pode-se alterar o fluxo de sequencial de execução de modo a fazer com que ele voltasse a executar o conjunto de ações relativas a um único ponto de luz (v1.4) o tanto quanto for necessário.

Veja como ficará :

Algoritmo Troca de Lâmpada v1.6
- ir até o interruptor do `primeiro` soquete;
- enquanto a quantidade de soquetes testados for menor que dezesseis, faça :
    - ligar o interruptor;
    - se a lâmpada não ligar, então :
        - pegar uma escada;
        - colocar a escada embaixo da lâmpada;
        - buscar uma lâmpada reserva;
        - subir na escada;
        - retirar a lâmpada velha;
        - colocar a lâmpada reserva;
        - jogar fora a lâmpada velha;
        - enquanto a lâmpada não ligar, faça :
            - retirar a lâmpada velha;
            - colocar a lâmpada reserva;
            - jogar fora a lâmpada velha;
        - guardar a escada;

Quando a condição `quantidade de soquetes testados for menor que dez` for verdadeira, as ações responsáveis pela troca ou não de um único soquete são exexutadas. Caso a condição de parada seja falsa, ou seja, todos os 10 soquetes já tiverem sido testados, nada mais será executado.

## resumo

Todo o exemplo foi desenvolvido a partir do problema de descrever os passos necessários para efetuar a troca de uma lâmpada, ou seja, construir um *algoritmo* para esse fim. Inicialmente, havia um pequeno conjunto de ações que deveriam ser executadas, todas passo a passo, compondo uma ordem sequencial de execução.

Pode-se ver que nem todas as ações previstas deveriam ser executadas. Isso mostrou que um determinado conjunto de ações fosse evitado, selecionado conforme o resultado de uma determinada condição. Dessa forma, era necessário uma *estrutura condicional* através de um *teste condicional* que permitisse ou não que o fluxo de execução passasse por um deterinado conjunto de ações.

Depois, surgiu uma necessidade repetir diversos trechos de código do algoritmo. Para resolver isso, foi alterado o fluxo de execução para que ele passasse diversas vezes pelo mesmo trecho diversas vezes, enquanto a condição não fosse satisfeita. Resolução semelhante que foi usado quando foi necessário realizar a troca de dez pontos de luz. Para ambos os casos, foi usado uma *estrutrua de repetição*.

Vale a pena ressaltar que praticamente qualquer pessoa seria capaz de resolver o problema de trocar uma lâmpada, incluindo se adaptar a qualquer circunstância pitoresca que pudesse surgir. Mas um programa de computador tradicional não tem conhecimento prévio e nem tem a capacidade de raciocínio para encontrar soluções diante de uma situação imprevista. Isso implica que todos os detalhes devem ser determinados em todas as situações que ele deve executar, prevendo os obstáculos e a forma que superá-los, isto é, descrever uma sequência finitas de passos que garantam a solução do problema. Essa atividade é realizada pelos **programadores**.

## atividades

1. Três senhoras, dona Branca, dona Rosa e dona Violeta, passeavam pelo parque quando dona Rosa disse :
    - Não é curioso que estejamos usando vestidos de cores branca, rosa e violeta, embora nenhuma de nós esteja usando um vestido de cor igual ao seu próprio nome?
    - Uma simples coincidência, respondeu a senhora com o vestido violeta. Qual a cor do vestido de cada senhora?

    <details>
    <summary>Resposta</summary>

    Para resolver o problema, precisamos seguir as pistas fornecidas e usar um pouco de lógica dedutiva. Identificando as senhoras e suas cores de vestido. São 3 senhoras, a dona Branca, a dona Rosa e a dona Violeta. Identificando as cores dos vestidos disponíveis: branco, rosa e violeta. Entendendo as pistas, nenhuma das senhoras está usando um vestido da cor que corresponde ao seu nome, a dona Rosa não está usando um vestido rosa, a dona Branca não está usando um vestido branco e dona Violeta não está usando um vestido violeta. Deduções a partir da conversa, quando dona Rosa comenta sobre a coincidência, a senhora com o vestido violeta responde. Logo, a dona Rosa não pode estar usando o vestido rosa, a dona Branca não pode estar usando o vestido branco e a dona Violeta não pode estar usando o vestido violeta. Como a dona Branca é quem fez a primeira afirmação, as únicas que podem ter respondido eram a dona Violeta e a dona Rosa. Como a resposta veio da dona usando o vestido violeta, sabemos que a dona Violeta não pode ter respondido (nenhuma delas está usando o vestido da cor de seu nome). Logo, a resposta só pode ter vindo da dona Rosa usando o vestido violeta. Com isso, ainda falta descobrir quais vestidos a dona Branca e a dona Violeta estão usando entre os vestidos restantes, rosa e branco. Como a dona Branca não pode estar usando o vestido branco, então ela só pode usar o vestido rosa. Logo, a dona Violeta está usando o vestido branco, sendo a única combinação faltante.

    </details>

1. Um homem precisa atravessar um rio com um barco que possui capacidade para carregar apenas ele mesmo e mais uma de suas três cargas, que são : um lobo, um bode e um maço de alfafa. O que o homem deve fazer para conseguir atravessar o rio sem perder suas cargas? As regras são :
    - O bode não pode ficar sozinho com a alfafa;
    - O homem pode viajar sozinho;
    - O lobo não pode ficar sozinho com o bode;

    <details>
    <summary>Resposta</summary>

    Para resolver o problema de atravessar o rio com o lobo, o bode e a alfafa, sem deixar o bode sozinho com a alfafa ou o lobo sozinho com o bode, é preciso planejar cuidadosamente cada travessia. Vamos resolver isso passo a passo. Na primeira viagem, o homem leva o bode para o outro lado do rio e o deixa lá enquanto que o lobo e a alfafa ficam do lado inicial. Na segunda viagem o homem retorna sozinho ao lado inicial e o lobo e a alfafa ainda estão do lado inicial. Na terceira viagem o homem leva o lobo para o outro lado do rio e agora, o bode e o lobo estão juntos do outro lado, mas o homem não pode deixá-los juntos, então, o homem pega o bode e retorna com ele ao lado inicial. Na quarta viagem o homem deixa o bode no lado inicial e leva a alfafa para o outro lado do rio e agora, o lobo e a alfafa estão juntos do outro lado, e o bode está sozinho do lado inicial. Na quinta viagem o homem retorna sozinho ao lado inicial. Na sexta viagem o homem leva o bode para o outro lado do rio.

    </details>

1. Três jesuítas e três canibais precisam atravessar um rio. Para isso, eles têm um barco com capacidade para duas pessoas. Por medida de segurança, não se deve permitir que em alguma margem a quantidade de jesuítas seja inferior à de canibais. Qual a solução para efetuar a travessia com segurança?

    <details>
    <summary>Resposta</summary>

    Para resolver o problema dos três jesuítas e três canibais precisando atravessar o rio sem nunca permitir que os canibais sejam mais numerosos que os jesuítas em qualquer margem, precisamos planejar cuidadosamente cada travessia. Vamos representar os jesuítas como J e os canibais como C. Vamos usar o formato (J, C) para representar a quantidade de jesuítas e canibais em cada margem do rio. Inicialmente, todos estão na margem esquerda (3J, 3C) e (0J, 0C) na margem direita. Na primeira viagem vamos atravessar 2 canibais para a margem direita, ficando (3J, 1C) | (0J, 2C). Na segunda viagem vamos retornar 1 canibal para a margem esquerda, ficando (3J, 2C) | (0J, 1C). Na terceira viagem vamos atravessar 2 canibais para a margem direita novamente, ficando (3J, 0C) | (0J, 3C). Na quarta viagem vamos retornar 1 canibal para a margem esquerda, ficando (3J, 1C) | (0J, 2C). Na quinta viagem vamos atravessar 2 jesuítas para a margem direita, ficando (1J, 1C) | (2J, 2C). Na sexta viagem vamos retornar 1 jesuíta e 1 canibal para a margem esquerda, ficando (2J, 2C) | (1J, 1C). Na sétima viagem atravessam 2 jesuítas para a margem direita novamente, ficando (0J, 2C) | (3J, 1C). Na oitava viagem vamos retornar 1 canibal para a margem esquerda, ficando (0J, 3C) | (3J, 0C). Na nona viagem vamos atravessar 2 canibais para a margem direita, ficando (0J, 1C) | (3J, 2C). Na décima viagem retorna 1 canibal para a margem esquerda, ficando (0J, 2C) | (3J, 1C). Na décima primeira viagem atravessam 2 canibais para a margem direita, ficando (0J, 0C) | (3J, 3C).

    </details>

1. No torneio de atletismo, Carlos, José e Sérgio participaram das provas de 100 metros rasos, salto em distância e arremesso de dardo. Cada um deles conseguiu um primeiro lugar, um segundo e um terceiro. Descubra o que cada um conquistou, sabendo que :
    - José venceu Carlos no salto em distância;
    - Sérgio chegou atrás de José no arremesso de dardo;
    - Carlos não chegou em primeiro nos 100 metros rasos;

1. João tem três barris. No barril A, que está vazio, cabem 8 litros. No barril B cabem 5 litros. No varril C cabem 3 litros. O que deve fazer João para deixar os barris A e B com 4 litros cada e o C vazio?

    <details>
    <summary>Resposta</summary>

    Para resover esse problema, é necessário ficar atento ao portuguës também. O problema diz que o barril A está vazio, mas não diz o mesmo dos barris B e C, então pode-se implicar que estão cheios. Também, como não há outras medidas no barris, não há como dividir o conteúdo de qualquer barril parcialmente, como passar 1 litro do barril C para o barril A, por exemplo. Partindo desse princípio, temos que deixar os barris A e B com 4 litros cada. No começo, estamos com (A, 0L), (B, 5L) e (C, 3L). No primeiro passo, vamos transferir todo o conteúdo do barril C para o barril A, ficando (A, 3L), (B, 5L) e (C, 0L). No segundo passo, vamos passar o conteúdo do barril B para o C, ficando (A, 3L), (B, 2L) e (C, 3L). Agora, no terceiro passo, vamos passar o conteúdo do barril C para o barril A, ficando (A, 6L), (B, 2L) e (C, 0L). No quarto passo, vamos passar o conteúdo do barril B para o barril C, ficando (A, 6L), (B, 0L) e (C, 2L). No quinto passo, vamos passar o conteúdo do barril A para o barril B, ficando (A, 1L), (B, 5L) e (C, 2L). No sexto passo, vamos passar o conteúdo do barril B para o C, ficando (A, 1L), (B, 4L) e (C, 3L). Por fim, no sétimo passo, vamos colocar o líquido do barril C no A, ficando (A, 4L), (B, 4L) e (C, 0L).

    </details>
