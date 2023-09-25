# Front-End: Projeto Passeio Carioca
## Nosso entendimento do projeto: 

O intuito desse projeto é criar um feed de notícias no estilo do instagram, mostrando a atualização dos imóveis, fazendo com que o turista saiba das últimas atualizações realizadas pela empresa Passeio Carioca.
Publicar anúncios, para caso o cliente queria participar de alguma experiência em relação aos imóveis.
Vai existir uma parte em que o usuário comente sobre o imóvel. A mensagem vai pro administrador e se aprovar vai para o aplicativo (o foco é em avaliar a história e não o imóvel). Possui opção de favoritos e curtidas.

Exemplo: Bar lagoa, exemplo de ponto de interesse e no final ira ter um cupom de desconto (viva a experiência).

## Anotações

Voltado ao turismo arquitetônico, de lugares recentes também, de prédios comuns, residenciais. História recentes. Conta sobre o estilo da construção, da parte da arquitetura.

Gameficação -> medalhas que o usuário pode ganhar caso ele faça check in em um determinado ponto. Pode usar como anúncios também.

Rankeamento dos usuários em termos de medalha.

Mapa do rj, pode escolher a sua geolocalização, visando ver os imóveis mais perto dele ou não.
No feed são apenas os pontos de interesses adicionados recentemente.

O mapa aparece primeiro quando o usuário abre o app, com vários pontos de interesses.
 
Referência: Página no instagram -> @riocasaseprediosantigos 

## Plano de Ação 5W2H
## Projeto, Usuário e Sistema

### Who
#### (Quem -> Projeto/Sitema) - Quem vai fazer o projeto/sistema e para quem é o projeto?
Os membros da Equipiada farão o projeto, que será destinado para os clientes, ou seja, os usuarios do aplicativo Passeio Carioca.
#### (Quem -> Usuário) - Quem vai utilizar o projeto?
As pessoas que tiverem interesse e curiosidade em conhecer as obras arquitetônicas do Rio de Janeiro.

### When 
#### (Quando -> Projeto) - Para quando é o projeto? -> data de entrega ou formato de atualizações do cliente ao projeto:
As datas de atualização serão semanais, e terão apresentações maiores nos dias das provas AP1 e AP2.
#### (Quando -> Usuário) - Quando o usuário vai utilizar?
No momento em que o usuário tiver o interesse de consultar imóveis na cidade do Rio de Janeiro.
#### (Quando -> Sitema) - Quando o sistema vai ficar pronto?
O sistema ficara pronto ate o final dessa disciplina de Projeto Front-End.

### Where 
#### (Onde -> Projeto) -  Aonde será feito o projeto? -> Qual plataforma ou destino que terá esse projeto?
O projeto será feito num Ambiente de Desenvolvimento Integrado (IDE) que suporte a linguagem JavaScript, como VSCode ou Node.js. O destino do projeto será o aplicativo da empresa.
#### (Onde -> Usuário) - Onde será possível acessar o projeto? -> feed de notícias + aplicativo:
Na rua, em casa, em todos os lugares onde eles possuírem um dispositivo com acesso a internet.
#### (Onde -> Sistema) - Onde sera feito o sistema?
O sistema sera realizado em sala de aula como tambem em reuniao virtuais do nosso grupo Equipiada.

### What 
#### (O que -> Projeto/Sistema) - O que é o projeto?/sistema O que precisa ser feito? -> Quais são os requisitos feitos pelo cliente?
O projeto se trata de criar uma pagina web com um feed de noticias para manter os clientes atualizados à respeito dos novos imóveis  que a empresa adicionou ao seu sistema. Esse feed tem que conter uma imagem do imóvel, uma descrição dos imóveis e uma parte para adicionar um link que possa levar a uma possível experiência no imóvel. Assim como tera um espaco para curtir, favoritar e comentar uma publicacao.
#### (O que -> Usuário) - O que o usuário vai fazer no aplicativo?
A experiência do usuário será baseada na sua interação com os imóveis já cadastrados e com a história que cada um deles possui. 
Ele poderá entrar em contato para participar de algum evento dos imóveis, além de avaliá-los no feed de notícias com likes e comentários, a fim de melhorar a notoriedade daquele imóvel.

### Why 
#### (Por que -> Projeto/Sistema) - Porque esse projeto/sistema é necessário? -> No que ele vai ajudar o cliente?
Esse projeto do Passeio Carioca vai ajudar o cliente a se manter atualizado sobre as novas descobertas que foram feitas, assim como as novas possíveis experiências que vem com esses edifícios.
#### (Por que -> Usuário) -Por que o usuario vai usar o aplicativo? Por que que ele vai usar o feed? 
Para obter informações e curiosidades consultando as construções arquitetônicas no Rio de Janeiro. 

### How 
#### (Como -> Projeto/Sistema) - Como será feito o projeto/sistema? -> metodologias, processos e linguagens:
O projeto será feito a partir de reuniões da equipe durante e fora das aulas, documentando o que for necessário para realização do projeto e assim programando a partir do React utilizando a linguagem JavaScript.
#### (Como -> Usuário) - Como o usuário terá acesso ao sistema?
O usuário poderá acessar o aplicativo e interagir no feed de notícias usando seu smartphone.

### How much 
#### (Preço -> Projeto/Sistema) - Quanto será gasto no projeto/sistema? -> o valor do projeto: 
O principal custos desse projeto nao e monetario, mas sim o tempo da equipe que faz o projeto/sistema.
#### (Preço -> Usuário) - Quanto o usuário gastará usando o aplicativo?
Será medido, apenas, o tempo de acesso gasto pelo usuário na sua interação com o aplicativo.

## Resquisitos do sistema:

#### Funcionais(os requisitos funcionais são todos os problemas e necessidades que devem ser atendidos e resolvidos pelo software por meio de funções ou serviços. O sistema faz e oferece ao cliente.)
-  O sistema exibira as postagens mais recentes no topo;
-  O sistema oferece uma interacao de curtir um post;
-  O sistema oferece uma interacao de comentar num post;
-  O sistema oferece uma interacao de favoritar um post;
-  O sistema oferece uma interacao de busca no feed;
  

#### Não Funcionais(Os requisitos não funcionais são todos aqueles relacionados à forma como o software tornará realidade que está sendo planejado. Não é uma funcionalidade atribuída ao cliente.)
- O sistema usará o framework REACT;


## Propósito do Sistema
Construir uma página web, na qual irá possuir um feed. Será construída para mobile apenas. 
O feed vai conter imagens e a descrição delas, mapa que atribui aos imóveis alguns pontos e haverá utilização de geolocalização.
Outra funcionalidade é um sistema de audio, que vai reproduzir a voz da estátua feita através de inteligência artificial.
Tudo isso será interativo para o usuário.


## Casos de Uso
Atores: os clientes do aplicativo Passeio Carioca.
Pre condicoes: Abrir o aplicativo
Fluxo principal -> No sistema, o usuario poderá:
Visualizar os posts mais recentes no topo do feed de publicações; Realizar uma busca por uma publicação de interesse; Curtir uma publicação; Comentar uma publicação; Favoritar uma publicação;
Pós-condições: Nenhuma.


3 casos de uso: visualizar o feed, ver mais detalhes (saiba mais) e link externo
