# Stable Roll

Stable Roll é um jogo desenvolvido em React Native no qual o jogador controla uma bola utilizando o acelerômetro do celular. O objetivo é percorrer um tabuleiro personalizado, desviando de paredes e buracos até alcançar o ponto de vitória.

Além de jogar, o aplicativo permite criar, salvar e excluir diferentes tabuleiros, possibilitando que o próprio usuário monte os desafios que deseja jogar.

Demonstração

Vídeo de demonstração no YouTube

Imagens

### Tela inicial

![Tela inicial do projeto](images/telainicial.jpeg)


### Criação de tabuleiro

![Durante criação de um tabuleiro](images/criatabuleiro.jpeg)


### Lista de tabuleiros

![Lista dos tabuleiros criados](images/tabuleiros.jpeg)


### Jogo

![Durante o jogo](images/jogo.jpeg)
![Vitória no jogo](images/vitoriajogo.jpeg)
![Derrota no jogo](images/derrotajogo.jpeg)
Sobre o projeto

O Stable Roll possui um sistema de criação de tabuleiros baseado em uma grade de 5 colunas por 9 linhas. Ao selecionar uma posição da grade durante a criação, o tipo daquele espaço é alterado, permitindo adicionar diferentes elementos ao cenário.

Os elementos disponíveis são:

Espaço vazio

Parede

Buraco

Ponto de vitória

Jogador

Para que um tabuleiro seja criado, é necessário informar um nome, adicionar exatamente um jogador e possuir pelo menos um ponto de vitória.

Os tabuleiros criados são armazenados localmente no dispositivo e podem posteriormente ser selecionados na tela de tabuleiros para iniciar uma partida ou serem excluídos.

Durante o jogo, a movimentação da bola é realizada utilizando o acelerômetro do dispositivo. A inclinação do celular determina a direção do jogador dentro do tabuleiro.

Ao colidir com uma parede, o movimento é bloqueado. Ao atingir um buraco, a partida é encerrada com derrota. Ao alcançar um ponto de vitória, a partida é encerrada com sucesso.

Execução

Após baixar o projeto, instale as dependências:

npm install

Em seguida, execute o projeto utilizando o Expo:

npx expo start

Como a jogabilidade utiliza o acelerômetro, recomenda-se executar o projeto em um dispositivo móvel compatível com o Expo.
