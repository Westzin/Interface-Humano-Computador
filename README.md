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
 - Um usuário leigo estará ciente de todos os serviços oferecidos pela plataforma, pois estas informaçsão disponibilizadas com clareza.

   <img width="1147" height="674" alt="image" src="https://github.com/user-attachments/assets/b00d491e-01b2-4201-a58e-b8fbecf84478" />

 - Usuários comuns acreditam ser um ótimo produto a nível profissional com preço acessível, como diz este post do Reddit: [link](https://www.reddit.com/r/antivirus/comments/1ddtnxc/how_good_is_kaspersky/)
 - Rankings como AV Test, avaliam o mesmo como um produto exemplar: [link](https://www.av-test.org/en/antivirus/home-windows/manufacturer/kaspersky-lab/)


## Personas

- Persona Primaria (Autor: Thiago Monteiro Tinonin):

| Categoria      | Dados |
| ----------- | ----------- |
| Foto |  ![Alt text](https://github.com/Westzin/Interface-Humano-Computador/blob/4ae46275f4e6a7f71d26fcc7e95ff17f671fd039/persona1.png) |
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

- Persona Primária 2 (Autor: Angelo Gabriel Vasconcelos Baptista):

 | Categoria      | Dados |
| ----------- | ----------- |
| Foto |  ![Alt text](https://github.com/Westzin/Interface-Humano-Computador/blob/4ae46275f4e6a7f71d26fcc7e95ff17f671fd039/persona2.png) |
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

O serviço irá armazenar informações relacionadas aos dispositivos IoT das personas e seu ano de nascimento.

## Mapa de empatia

![empatia.png](https://github.com/FagnerPimentel-Academic/template-ihc/blob/3471821dc52120e61c5648dc3156a83672f35a4a/docs/imagens/empatia.png)

### Persona Primaria.
  
  - O que o usuário vê:
     1. Amigos em regime de trabalho CLT.
     2. Como dispositivos IoT são aplicados em sua cidade inteligente.
  - O que o usuário ouve:
     1. Assiste filmes e series Geeks em plataformas como HBO Max e Netflix.
     2. Precisa trabalhar menos e relaxar mais.
  - O que o usuário diz e faz:
     1. Valoriza seu tempo livre.
  - O que o usuário pensa e sente:
     1. Precisa fazer horas extras para pagar as suas assinaturas.
     2. Dispositivos IoT facilitam sua vida em tarefas domésticas.
  - Dores:
     1. Se sente muito exausto em seu tempo livre.
     2. Sente que todos estão a sua frente.
     3. Sente que sua rede privada será invadida.
  - Ganhos:
     1. Tranquilidade de monitorar sua rede.
     2. Possibilidade de utilizar dispositivos IoTs baratos sem se preocupar com brechas na segurança do mesmo.

### Persona Primária 2

  - O que o usuário vê:
     1. Amigos empresários.
     2. Dispositivos IoT servindo de estrutura essencial para sua empresa.
  - O que o usuário ouve:
     1. Assiste o jornal nacional e escuta radio antena 1.
     2. Muitas empresas colapsam devido a vazamentos de dados entre seus funcionários.
  - O que o usuário diz e faz:
     1. Valoriza seu tempo livre.
  - O que o usuário pensa e sente:
     1. Precisa se conectar mais com a tecnologia e abandonar alternativas analógicas.
     2. Dispositivos IoT são complexos.
  - Dores:
     1. Se sente muito exausto mentalmente em seu tempo livre.
     2. Sente que seu cargo de CTO esta sendo ameaçado.
  - Ganhos:
     1. Tranquilidade em saber que sua rede será protegida.
     2. Possibilidade de utilizar dispositivos IoTs baratos sem se preocupar com brechas na segurança do mesmo.

## Contexto de uso

- Ambientes onde o produto será utilizado:
     - Ambiente domiciliar entre familiares ou pessoas sozinhas;
     - Ambiente empresarial que utiliza IoT de alguma forma;
     - Ambiente industrial;
- Contexto(s) sociais, econômicos e culturais dos ambientes:
     - Familiares de classe baixa/média com formação no ensino superior/médio;
     - Colaboradores em empresas de classe média/alta com formação em ensino superior;
     - Operadores de maquinário industrial de classe baixa/média com formação em superior/médio;
- Informações que o produto deve guardar antes de iniciar a interação:
     - Todos os dispositivos IoT da rede;
- Rotina comum dos ambientes em que o produto será utilizado:
     - Em redes domésticas, os familiares estarão usando os dispositivos naturalmente;
     - Em redes empresariais, será horário comercial e os colaboradores estarão trabalhando em seus dispositivos;
     - Em redes Industriais, os operários estarão operando o maquinário;

## Jornada do usuário

- Narrativa do serviço/produto com o usuário
     - O usuário utiliza o IDS em um ambiente com dispositivos IoT (doméstico, empresarial ou industrial);
     - O sistema realiza a varredura e monitora continuamente os dispositivos conectados à rede;
     - Ao longo da interação, o usuário recebe alertas de anomalias, tentativas de acesso suspeitas ou falhas de segurança;
     - O serviço/produto auxilia na tomada de decisão, permitindo que o usuário atue preventivamente ou reaja a incidentes;
- Passo a passo da interação
  - Início da tarefa:
     - O usuário instala e configura o IDS na rede IoT.
     - O sistema identifica automaticamente todos os dispositivos conectados.
     - O IDS inicia o monitoramento contínuo em segundo plano.
  - Desenvolvimento da tarefa:
     - O sistema analisa o tráfego de rede e o comportamento dos dispositivos IoT.
     - Caso detecte anomalias (ex.: tráfego suspeito, acessos não autorizados, falhas de configuração), o IDS gera um alerta.
     - O usuário recebe notificações claras (em dashboard ou aplicativo) sobre o problema identificado.
     - O sistema sugere possíveis ações (ex.: bloquear IP suspeito, reiniciar dispositivo, atualizar firmware).
  - Término da tarefa:
     - O usuário valida as ações realizadas pelo IDS ou toma decisões adicionais.
     - O sistema registra os incidentes e armazena logs para auditoria futura.
     - O processo se encerra quando o ambiente volta ao funcionamento normal e seguro, mas o IDS permanece ativo, pronto para detectar novas ameaças.

<!--
## Jornada do usuário

- Criar uma narrativa para o seu serviço ou poduto com o usuário.
     - O usuário utiliza o IDS em um ambiente com dispositivos IoT (doméstico, empresarial ou industrial);
     - O sistema realiza a varredura e monitora continuamente os dispositivos conectados à rede;
     - Ao longo da interação, o usuário recebe alertas de anomalias, tentativas de acesso suspeitas ou falhas de segurança;
     - O serviço/produto auxilia na tomada de decisão, permitindo que o usuário atue preventivamente ou reaja a incidentes;
- Determine o que o usuário realiza desde a primeira até o última interação com o serviço ou poduto.
  - Descreva o que acontece ou pode acontecer passo a passo
  - Como a tarefa começa? Como a tarefa se desenvolve? Como a tarefa termina?
-->

<!--
## Análise de concorrência

- Pesquise serviços ou podutos existentes atualmente que possam realizar o objetivo deste projeto.
- Selecione pelo menos 3 serviços ou podutos diferentes.
- Em relação aos concorrentes, respondam as seguintes perguntas?
  - Existe plataforma similar que atende o mesmo mercado e funcionalidades? Se sim: Quais os pontos positivos? Quais os pontos negativos?
  - Existe plataforma diferente quanto ao serviço, mas que atenda esse mercado? Se sim: Quais os pontos positivos? Quais os pontos negativos?
 -->

# Cenário de Análise/Problema

> **_NOTE:_**: A equipe deve pensar em cenários existentes na atualidade (que causam problemas para os usuários) e que a interface prevista ajudará a resolver o problema. Cenário de Análise/Problema é uma história triste. Não descreve a solução. Descreve somente o problema.

- Cenário de Análise/Problema

Usuários que compram dispositivos IoT de má qualidade (porém de baixo custo), como uma câmera de segurança, devido a má prototipagem do dispositivo seu endereço IP está disponivel publicamente em sites como [Shodan](https://www.shodan.io/), onde pessoas maliciosas do mundo inteiro podem invadir e escanear por portas críticas abertas, tendo assim acesso a rede doméstica do usuário do dispositivo.
   
- Questões de Refinamento

1. O que é um invasor?
2. Por que analisar açoes de usuários dentro da rede?
3. Como invasores acessam a rede?
4. Por que usuários compram dispositivos de má qualidade?
5. Quem pode invadir a rede?
6. Qual é o principal alvo dos invasores?
7. Quais dispositivos IoT críticos são alvos de invasores?

- Refinamento do Cenário Análise/Problema

Usuários que compram dispositivos IoT de má qualidade[6] (porém de baixo custo)[4], como uma câmera de segurança[7], devido a má prototipagem do dispositivo seu endereço IP está disponivel publicamente em sites como [Shodan](https://www.shodan.io/) [3], onde pessoas maliciosas[1] do mundo inteiro[5] podem invadir e escanear por portas críticas abertas[2], tendo assim acesso a rede doméstica do usuário do dispositivo.

 
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
