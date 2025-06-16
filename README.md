Neste projeto, desenvolvi um jogo de perguntas e respostas sobre o campo utilizando a linguagem JavaScript com a biblioteca p5.js. O objetivo do jogo é testar os conhecimentos do jogador sobre temas relacionados à vida rural, agricultura, agropecuária e questões sociais ligadas ao campo.

O projeto começa com a criação de uma lista chamada questions, que armazena todas as perguntas do jogo. Cada pergunta é representada por um objeto contendo o enunciado, quatro alternativas e o número correspondente à resposta correta. Ao todo, o jogo contém 15 perguntas.

Em seguida, foram criadas variáveis de controle como currentQuestion, que indica o número da pergunta atual, score, que armazena os pontos do jogador, e showResult, que determina se o jogo chegou ao fim. Essas variáveis são fundamentais para controlar o fluxo do jogo.

Na função setup(), inicializei a área de desenho com createCanvas(800, 400) e ajustei o alinhamento e o tamanho do texto para garantir que as perguntas e respostas fiquem bem centralizadas na tela.

A lógica principal do jogo acontece na função draw(), que é executada continuamente. Nela, verifiquei se o jogo já terminou. Se sim, o programa exibe uma mensagem de encerramento e mostra quantas perguntas o jogador acertou. Se o jogo ainda estiver em andamento, ele exibe o número da pergunta atual, o enunciado e as quatro alternativas, desenhadas em forma de botões (retângulos) interativos.

Para que o jogador possa escolher uma resposta, utilizei a função mousePressed(). Nela, verifiquei se o clique do mouse ocorreu dentro da área de alguma das alternativas. Se a resposta escolhida for correta, a pontuação é aumentada. Depois disso, o jogo avança para a próxima pergunta. Quando todas as perguntas forem respondidas, o jogo exibe o resultado final com a pontuação total.

Esse projeto não só ajuda a reforçar conhecimentos sobre o campo de forma lúdica, como também permite o desenvolvimento de habilidades em lógica de programação, interação com o usuário e estruturação de dados em JavaScript com p5.js. O jogo pode ser facilmente adaptado para outros temas, acrescentando ou alterando as perguntas do array.

