# Projeto de Interface Humano-Computador

Projeto apresentado ao Centro Universitário [FEI](https://portal.fei.edu.br/), como parte dos requisitos necessários para aprovação na disciplina de Interface Humano-Computador (CC8122) do curso de Ciencia da Computação, orientado pelo Prof. Dr. [Fagner de Assis Moura Pimentel](https://github.com/fagnerpimentel) e Prof. Dr. Plino Thomaz Aquino Junior.

Este projeto se baseia no Trabalho de Conclusão de Curso (TCC) entitulado **Uma metodologia baseada em modelos Bayesianos e redes neurais profundas para detecção de intrusão em dispositivos IoT** sob orientação do Professor **Rafael Gomes Alves** e desenvolvido pelos seguintes alunos:

- Thiago Monteiro Tinonin
- Angelo Gabriel Vasconcelos Baptista
- Rafael Augusto Feliciano Assembleia

## Resumo

## Introdução

O objetivo de nosso serviço é realizar a detecção de intrusos em redes de computadores utilizando uma abordagem baseada em modelos bayesianos e redes neurais profundas, onde os usuários finais serão organizações e entusiastas que precisam de segurança em sua rede local que utilizam dispositivos de internet das coisas (IoT). Um sistema mais seguro e maior controle da rede será fornecido para os usuários. As seguintes funcionalidades serão propostas:

 - Habilitar/Desabilitar o sistema
 - Checar Log de comportamentos dos usuários da rede
 - Configurar opções do sistema
   
Para o desenvolvimento do projeto usaremos Python com Scikit-learn (sklearn) e TensorFlow como ferramentas de machine-learning e redes neurais.

O Sistema de Detecção e Intrusão (IDS) funcionaria o tempo todo nas redes de computadores, monitorando o comportamento de cada computador. No contexto em que existe uma interface para humanos, poderia ser utilizado para habilitar ou desabilitar o funcionamento do IDS, bem como configurar opções do sistema. A interface teria que ser utilizada por profissionais de segurança da informação e seria utilizada quando houvesse algum problema que solicitasse manutenção do sistema. É importante ressaltar que o produto não prevê o desenvolvimento de uma interface.

## Publico Alvo

- Entusiastas que utilizam (ao menos minimamente) dispositivos IoT dentro de sua rede doméstica, onde o mesmo possui interesse em tecnologia como um Hobby, porém lida com frustações e medo de sua rede ser invadida por meio de seus dispositivos baratos de IoT com IP público e assim comprometer sua privacidade, para este tipo de usuário, pode ser de qualquer lugar do mundo, pois dessa forma estarem lidando com protocolos universais de redes de computadores.

 - Empresas que utilizam dispositivos simples de IoT ou dispositivos de internet das coisas industrial (IIoT), pois elas lidam com diversos dados sensíveis que não podem ser expostos, desde informações sobre servidores ou até mesmo informações sobre colaboradores, estas empresas devem se localizar no Brasil, pois apesar de estarmos lidando com protocolos universais de redes de computadores, também lidaremos com legislações de cada região, como a LGPD.

## Análise de concorrência

#### [Bitdefender](https://www.bitdefender.com/pt-br/)

 - Antivírus com detecção de atividades suspeitas na rede.
 - Proteção para dispositivos hospedeiros na rede.
 - Sistema de Detecção de Intrusão (IDS).
 - Preços extremamente altos tanto em planos individuais e familiares (entre R$300 até R$600).
 - Usuários avaliam em fóruns como um produto bom a razoável, como dizes nesta publicação do Reddit: [link](https://www.reddit.com/r/antivirus/comments/16lu52w/is_bitdefender_really_good/)
 - Sites profissionais avaliam muito bem o produto como: [PCMag](https://www.pcmag.com/reviews/bitdefender-antivirus-plus) [CNET](https://www.cnet.com/tech/services-and-software/bitdefender-antivirus-review/)
 - Recomendo uma melhora em pontos de performance, pois para carregar o site foram gastos 3 segundos encarando para uma tela branca.
 - Pontos de UX também precisam ser avaliados, pois um usuário leigo não entende o que o produto oferece, pois a primeira coisa que o mesmo se depara, é uma tela de Pricing e dizendo vagamente que o produto se trata de um antivírus.

   <img width="1239" height="936" alt="image" src="https://github.com/user-attachments/assets/f53a69e8-b775-444c-b856-c86c213a21d4" />

### [kaspersky](https://www.kaspersky.com.br/)

 - Antivírus com tecnologia de IA
 - Proteção de dispositivos conectados a rede.
 - Preços acessíveis, entre R$100 a R$200.

   <img width="1145" height="620" alt="image" src="https://github.com/user-attachments/assets/c42d751a-f861-4db9-8942-f67910a6d55e" />

 - Site performático, com interface fluida e dinâmica.
 - Um usuário leigo estará ciente de todos os serviços oferecidos pela plataforma, pois estas informação são disponibilizadas com clareza.

   <img width="1147" height="674" alt="image" src="https://github.com/user-attachments/assets/b00d491e-01b2-4201-a58e-b8fbecf84478" />

 - Usuários comuns acreditam ser um ótimo produto a nível profissional com preço acessível, como diz este post do Reddit: [link](https://www.reddit.com/r/antivirus/comments/1ddtnxc/how_good_is_kaspersky/)
 - Rankings como AV Test, avaliam o mesmo como um produto exemplar: [link](https://www.av-test.org/en/antivirus/home-windows/manufacturer/kaspersky-lab/)


### Personas

- Persona Primaria (Autor: Thiago Monteiro Tinonin):

| Categoria      | Dados |
| ----------- | ----------- |
| Nome        | Eduardo       |
| Nascido em  | 2000        |
| Trabalho  | Entregador        |
| Hobbies  | Tecnologias em geral, desde computadores retro, até videogames modernos |
| Sentimentos  | Constantemente ansioso, com receio de que sua identidade virtual será invadida, desde os meios mais imprevisíveis |
| Midia  | Consome conteúdos geeks por meio do YouTube e series e filmes de super heróis |
| Tempo utilizando IoTs por dia | 3h |
| Numero de dispositivos | 4 |
| Dispositivos minimamente configurados? | Sim |
| Dispositivos de qualidade? | Não |

- Persona Secundaria (Autor: Angelo Gabriel Vasconcelos Baptista):

 | Categoria      | Dados |
| ----------- | ----------- |
| Nome        | Nicholas       |
| Nascido em  | 1990        |
| Trabalho  | CTO de multinacional        |
| Hobbies  | Golf e Tenis aos finais de semana |
| Sentimentos  | Tranquilo, porém atento com questões tecnológicas de sua empresa e receoso com vazamentos de dados internos |
| Midia  | Consome conteúdo político pela televisão, e acessa sites de notícias pelo seu Blackberry |
| Tempo utilizando IoTs por dia | 16h |
| Numero de dispositivos | 34 |
| Dispositivos minimamente configurados? | Sim |
| Dispositivos de qualidade? | Sim |

- Persona Extrema (Autor: Rafael Augusto Feliciano Assembleia):

| Categoria      | Dados |
| ----------- | ----------- |
| Nome        | Severino       |
| Nascido em  | 1970        |
| Trabalho  | Programador |
| Hobbies  | Programação em assembly 6502 e pescaria |
| Sentimentos  | Tranquilo |
| Midia  | Leitura de livros e jornais |
| Tempo utilizando IoTs por dia | 20m |
| Número de dispositivos | 1 |
| Dispositivos minimamente configurados? | Não |
| Dispositivos de qualidade? | Sim |

O serviço irá armazenar informações relacionadas aos dispositivos IoT das personas e seu ano de nascimento.

### Mapa de empatia

![Mapa de empatia](empatia.png)

- Determine o mapa de empatia[^1] de pelo menos uma persona primária e uma sercundária.
  - O que o usuário vê: aqui estamos falando do ambiente visual em que o usuário se encontra. Ou seja, o que ele efetivamente enxerga, as pessoas e objetos que estão ao seu redor. Isso ajuda a entender o contexto em que o usuário está inserido e as influências visuais que está recebendo.
  - O que o usuário ouve: neste quadrante, buscamos entender o que o usuário está ouvindo, os sons que o cercam e como eles influenciam suas ações.
  - O que o usuário diz e faz: aqui consideramos ações e comportamentos que o usuário apresenta durante sua interação com serviço ou poduto.
  - O que o usuário pensa e sente: neste quadrante, buscamos entender os pensamentos, sentimentos, emoções e percepções que o usuário tem em relação ao serviço ou poduto. Quais expectativas o usuário cria sobre o serviço ou poduto?
  Que tipo de serviço ou poduto mais agrada essa persona?
  - Dores: quando falamos sobre dores do usuário, estamos fazendo referência a quaisquer obstáculos, necessidades ou frustrações que o usuário possa experimentar ao tentar realizar uma tarefa ou alcançar um objetivo. Isso inclui, por exemplo, problemas de usabilidade, dificuldades de acesso ou outros desafios que podem afetar a experiência do usuário.
  - Ganhos: nesse caso estamos falando de quaisquer benefícios ou recompensas que o usuário possa experimentar ao utilizar o serviço ou poduto. Isso pode incluir economia de tempo ou facilidade de uso, por exemplo. Que desejos do usuário o serviço ou poduto satisfaz?

## Contexto de uso

- Descreva o ambiente em que o serviço ou poduto deve ser utilizado.
- Qual/quais o(s) contexto(s) sociais, econômicos e culturais existentes neste ambiente?
- Quais informações sobre o ambiente, o serviço ou poduto deve guardar antes de iniciar a interação?
- O que normalmente deve estar acontecendo com o ambiente quando o usuário interagir com o serviço ou poduto?

## Jornada do usuário

- Criar uma narrativa para o o seu serviço ou poduto com o usuário.
- Determine o que o usuário realiza desde a primeira até o última interação com o serviço ou poduto.
  - Descreva o que acontece ou pode acontecer passo a passo
  - Como a tarefa começa? Como a tarefa se desenvolve? Como a tarefa termina?


<!--
## Análise de concorrência

- Pesquise serviços ou podutos existentes atualmente que possam realizar o objetivo deste projeto.
- Selecione pelo menos 3 serviços ou podutos diferentes.
- Em relação aos concorrentes, respondam as seguintes perguntas?
  - Existe plataforma similar que atende o mesmo mercado e funcionalidades? Se sim: Quais os pontos positivos? Quais os pontos negativos?
  - Existe plataforma diferente quanto ao serviço, mas que atenda esse mercado? Se sim: Quais os pontos positivos? Quais os pontos negativos?
 -->
 
## Coleta de dados

## Modelo de tarefas

## Design

- Pense nas características de Affordances do seu serviço ou poduto. 
    - Que tipo de acessibilidades devem ser consideradas dentro do seu projeto?
- Discuta o papel das expectativas do usuário no projeto deste serviço ou poduto. Qual a importância e pontos a serem considerados se você quiser vender esse serviço ou poduto?

### Prototipação em baixo nível (papel)
#### Avaliação heurística

### Prtotipação em médio nível (Figma)
#### Avaliação heurística

### Prtotipação em alto nível (React)
#### Avaliação heurística

[^1]: Fonte: Adaptado de <https://hazeshift.com.br/mapa-de-empatia/>

<!-- TODOs:
- Add exemplos
 -->
