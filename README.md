![Pokemage](https://user-images.githubusercontent.com/120816306/231327614-10fb7d10-c57a-4db4-934d-43a2c6e7cb25.png)

<div align="center">

</div>

Este é um jogo de RPG desenvolvido na pseudolinguagem portugol através da ferramenta Portugol Studio. Tal jogo foi desenvolvido pela equipe de estagiários da Sponte.

 ### :video_game: **Sobre o jogo:** 

O jogo Pokemage é um RPG singleplayer de mágica. O jogador pode escolher qual mago preferir e a magia que o ajudará a enfrentar um inimigo poderoso.

### Entrada de Dados no Jogo:

Na entrada de dados, o usuário pode inserir:

● As coordenadas da localização de spawn — devem ser de no mínimo 1 e no máximo 1000 casas;

● Tipo de classe desejada: Mago de fogo, Mago de água, Mago de terra ou Mago de ar;

● Tipo de magia desejada — Meteoro, Tsunami, Terremoto ou Furacão;

● Nível — 1, 2 ou 3;

● A localização do centro de onde a magia será lançada — sendo o mínimo 1 e no máximo 1000 casas do tabuleiro.

### Atributos:

O mago possui atributos específicos que podem ser modificados:
<div align="center"> 
<img width="327" alt="Captura_de_tela_2023-04-11_104810-removebg-preview" src="https://user-images.githubusercontent.com/120816306/231192697-4a5c9586-1e95-4100-b2a0-2ffca2a5388b.png">

</div>

● Vida: Quantidade limite de pontos de dano que podem ser levados;

● Dano: Quantidade de vida que será retirada do oponente a cada acerto;

● Sorte: Chance de acerto da magia no oponente.

### Cálculo do dano e tamanho da magia:

● O dano da magia é calculado baseado no tipo de classe, no tipo da magia, no
nível da magia, na tabela de fraquezas e nos atributos do oponente;

● O tamanho da magia é calculado com base no nível da magia e no seu tipo.

### :dart: Cálculo de acerto:

O cálculo de acerto é feito da seguinte forma:

● Obtém-se as coordenadas iniciais do oponente em X e Y;

● Obtém-se a largura e a altura do oponente;

● Calcula se a magia acerta utilizando a distância entre o ponto mais próximo
do oponente e o raio da magia;

● Calcula a chance de acerto baseado em RNG (Random Number Generator)

— Se o número aleatório gerado não estiver no intervalo de acerto, a magia erra, caso contrário, ela acerta. 

### Boss:
Existem quatro tipos de Boss possíveis, sendo eles Fogo, Água, Terra e Ar. A diferença entre as classes influencia o tipo de magia utilizado contra o player. A
posição de spawn é feita de forma aleatória, assim como o local onde a magia irá atingir.

### Saída de Dados:
Na saída de dados, são imprimidas as seguintes informações:

● Se a magia acertar o oponente, o console informa o dano causado;

● Caso contrário, o console retorna a mensagem informando que o usuário errou

### Considerações finais:
A batalha ocorre até que o Boss ou o player tenha a vida menor ou igual a zero.
