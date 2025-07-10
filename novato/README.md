🏅 Nível Novato

A equipe de testes da MateCheck recebeu uma solicitação para determinar os limites de utilização do código dentro do jogo. Para isso, a equipe de programação solicitou o envio de blocos de código contendo loops (estruturas de repetição) para avaliação de desempenho e possibilidades de aplicação.

Movimentação das Peças:

    Bispo: 5 casas na diagonal superior direita
    Torre: 5 casas para a direita
    Rainha: 8 casas para a esquerda

No jogo, apenas possuímos movimentação para quatro direções, mas o Bispo se mexe na diagonal. Com isso, foi adicionada uma condição para movimentação dessa peça, em que, para movê-lo, utilizamos o comando printf e, em seu valor, colocamos a direção usando a combinação de direções básicas.

Requisitos Funcionais:

    Entrada de Dados:
        Os valores necessários devem ser inseridos manualmente a partir de variáveis dentro do código.
        Será permitido o uso de constantes para facilitar a escrita do código e evitar repetição de valores.
    Estruturas de Repetição:
        Os códigos precisam ser desenvolvidos utilizando estruturas de repetição.
    Saída de Dados:
        O sistema deve exibir os resultados de cada procedimento de forma clara e legível.

Requisitos Não Funcionais:

    Performance:
        O sistema deve executar os cálculos e apresentar os resultados sem atrasos perceptíveis.
    Documentação:
        O código deve ser bem documentado, incluindo comentários detalhados sobre a função de cada parte do código.
    Manutenibilidade:
        O código deve ser escrito de forma clara, empregando nomes de variáveis que permitam o fácil entendimento.

Instruções Detalhadas:

    Entrada de Dados:
        Inclua a biblioteca padrão de entrada e saída no início do seu programa.
        Declare variáveis constantes para definir os valores a serem comparados dentro das estruturas condicionais.
    Estruturas de Repetição:
        Utilize cada uma das diferentes estruturas de repetição apresentadas.
    Saída:
        As saídas deverão ser mostradas de forma clara e organizada, com a direção da peça.

Nomenclatura:

printf("Cima\n"); printf("Baixo\n"); printf("Esquerda\n"); printf("Direita\n");