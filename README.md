# TormentinhaDaQuarentena
Daniel Silveira de Lemos

Contexto:
Tormenta 20 é um sistema de RPG de mesa, criado pela Jambô editora, uma editora de Porto Alegre - RS, Brasil.
O sistema conta com uma diversidade de raças e classe jogaveis para que o jogador tenha um grande gama de costumização para criar personagens diversos e interessantes.
O nome "Tormentinha da Quarentena" surgiu como o nome da campanha que eu - Daniel Lemos - e meus amigos começamos a jogar para não perdermos o contato uns com os outros nos tempos de pandemia.
É uma atividade que eu adoro, tanto a interação com meus amigos, como poder presenciar histórias épicas, então sempre que posso faço trabalhos avaliativos com esse tema.
_______________________________________
#Etapa 1 - 05/10/2021

A ideia do projeto é criar um sistema que cria e armazena fichas simples, para usar como ideias para personagens.
A ficha de personagem é onde todas as informações necessárias para jogar vão, portanto ela é essencial para o jogo.
Não tenho certeza se irá ter integração com um banco de dados, então provavelmente será apenas um sistema para registrar o seguinte:
- Nome do personagem a ser criado;
- Raça;
- Classe;
- Valor de atributo, começando com Força, depois Destreza, Constituição, Inteligência, Sabedoria e, por fim, Carisma;
- Nível do personagem.
Seria possível também registrar uma lista de "poderes desejados", poderes sendo novas habilidades adquiridas quando um personagem aumenta de nível.
Existem dezenas de poderes, portanto o usuário terá que saber os nomes desejados, para então deixar escolhido suas melhorias futuras.

DISCOVERY: 

https://gabrielmadeirapessoa.github.io/gerador-tormenta20/ Esse projeto (inclusive do mesmo sistema de RPG) gera automáticamente um personagem com seus atributos.
![Screenshot_8](https://user-images.githubusercontent.com/69585927/136120802-131154e3-18a7-4843-b175-92cc3310c0ce.png)
Esta imagem é um exemplo de ficha completa do sistema Dungeons and Dragons (5ª edição), tirada do site www.dndbeyond.com

Este site gera uma ficha aleatória (com algum grau de customização) de NPC (non player characters, figurantes da história): http://www.npcgenerator.com
Seria possível seguir um modelo parecido, deixando algumas inputs para que o usuário preencha seu personagem para quando ele clique em salvar, apareça em outra parte da tela. Bem como ter outra seção da página com os nomes de personagens salvos.

FLUXOGRAMA:

![Screenshot_9](https://user-images.githubusercontent.com/69585927/136122174-04ec1b1c-e1b1-4962-a862-133ec5fbc16c.png)

_______________________________________
#Etapa 2 - 06/10/2021

Diagrama UML: Confesso que sei muito pouco de criação de diagrama UML, portanto me inspirei drásticamente no diagrama da atividade da N1 que valia 5 pontos.

![Screenshot_10](https://user-images.githubusercontent.com/69585927/136302768-0ab129d3-75fd-48df-884e-a45e82e9709a.png)

A ideia original seria colocar os atributos do personagem na classe "Personagem", porém os atributos sendo: Força, Destreza, Constituição, Inteligência, Sabedoria e Carisma. Eu pensei que fosse ser atributos demais para serem colocados em uma única classe, portanto resolvi tirá-los, mas se fosse fazer com eles, todos seriam tipo byte e privados (com seus métodos getters e setters).

Também não tenho certeza de qual seria o número ideal de classes, acredito que, como o sistema é um tanto similar ao realizado na tarefa da Fila de Atendimento na N1, acabei por deixar o mesmo número de classes.

_____________________________________________
# Review Etapa 2 - 07/10/2021
Eu também acredito que esteja bom, só analisa, depois quando codar se a classe main não ficará muito extensa, não que seja problema, mas está ficando muito bom.
