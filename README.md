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



# Cenário de Análise/Problema

> **_NOTE:_**: A equipe deve pensar em cenários existentes na atualidade (que causam problemas para os usuários) e que a interface prevista ajudará a resolver o problema. Cenário de Análise/Problema é uma história triste. Não descreve a solução. Descreve somente o problema.
<!--
Usuários que compram dispositivos IoT de má qualidade (porém de baixo custo), como uma câmera de segurança, devido a má prototipagem do dispositivo seu endereço IP está disponivel publicamente em sites como [Shodan](https://www.shodan.io/), onde pessoas maliciosas do mundo inteiro podem invadir e escanear por portas críticas abertas, tendo assim acesso a rede doméstica do usuário do dispositivo.
-->

- Cenário de Análise/Problema
  - Quando Eduardo não está trabalhando como entregador, costuma investir tempo em seus hobbies de tecnologia. Desta vez, Eduardo decidiu comprar uma câmera de segurança com conexão com a Internet, o que permite consultar as suas gravações através de um dispositivo móvel. No entanto, embora essa câmera tenha sido extremamente barata, possui qualidade duvidosa, e suas barreiras de segurança podem ser facilmente burladas, permitindo que invasores acessem suas gravações pessoais. Como Eduardo é bastante esperto, decide assinar um plano de um software que detecta intrusos em aparelhos IoT. Através da interface gráfica do aplicativo IDS, Eduardo consegue mapear todos os aparelhos IoT que estão conectados no Wi-Fi de sua casa. Um dia, Eduardo recebeu uma notificação de emergência de seu aplicativo, alertando que havia algum intruso tentando acessar a sua câmera. Ele decidiu bloquear o acesso do endereço de IP do invasor, e logo em seguida, foi analisar o histórico daquele usuário suspeito, descobrindo que ele havia tentado se conectar àquele dispositivo mais de 5 vezes.
  - Quando Nicholas não está ocupado coordenando as equipes de desenvolvimento e infraestrutura da empresa, ele costuma testar novas soluções tecnológicas diretamente no escritório. Recentemente, a empresa adquiriu uma série de smart locks (fechaduras inteligentes) para controlar o acesso às salas de reunião, substituindo os crachás tradicionais. Esses dispositivos permitem monitorar e liberar acessos por meio de um painel centralizado conectado à rede corporativa.
No entanto, embora os smart locks tenham trazido mais praticidade, Nicholas sabe que qualquer dispositivo IoT mal configurado pode representar uma porta de entrada para invasores. Por isso, ele implantou um sistema IDS corporativo especializado em monitorar dispositivos IoT, integrado à infraestrutura de segurança da empresa.
Certa manhã, enquanto revisava relatórios no dashboard, Nicholas recebeu uma notificação crítica do IDS: um endereço IP externo tentava realizar conexões suspeitas com um dos smart locks do andar administrativo. Imediatamente, Nicholas ordenou o bloqueio do tráfego daquela origem e acionou a equipe de segurança para verificar logs detalhados.
Na análise posterior, descobriram que o invasor havia tentado forçar o acesso ao dispositivo mais de 10 vezes em poucos minutos, explorando vulnerabilidades conhecidas em firmware desatualizado. Graças ao IDS, a ameaça foi identificada antes que conseguisse comprometer a rede interna. Nicholas então estabeleceu uma nova política de atualização automática e monitoramento contínuo.

- Questões de Refinamento
1. O que é um dispositivo IoT?
2. Qual dispositivo IoT foi utilizado?
3. Para que serve o sistema IDS?
4. Como o IDS notifica o usuário sobre possíveis ameaças?
5. Que ação imediata pode ser tomada ao detectar um invasor?
6. Qual risco está associado ao uso de dispositivos IoT?
7. Como o IDS contribuiu para impedir um ataque?
8. Que tipo de vulnerabilidade o invasor tentou explorar?
9. Quais informações o usuário pode obter ao analisar os registros de acesso?
10. Quais medidas de prevenção foram adotadas após o incidente?

- Refinamento do Cenário Análise/Problema
  - Quando Eduardo não está trabalhando como entregador, costuma investir tempo em seus hobbies de tecnologia. Desta vez, Eduardo decidiu comprar uma câmera de segurança com conexão com a Internet [1][2], o que permite consultar as suas gravações através de um dispositivo móvel. No entanto, embora essa câmera tenha sido extremamente barata, possui qualidade duvidosa, e suas barreiras de segurança podem ser facilmente burladas, permitindo que invasores acessem gravações pessoais do Eduardo [6].
Como o Eduardo é bastante esperto, decide assinar um plano de um software que detecta intrusos em aparelhos IoT (IDS) [3]. Através da interface gráfica do aplicativo IDS, Eduardo consegue mapear todos os aparelhos IoT que estão conectados no Wi-Fi de sua casa.
Um dia, Eduardo recebeu uma notificação de emergência [4] de seu aplicativo, alertando que havia algum intruso tentando acessar a sua câmera. Ele decidiu bloquear o acesso do endereço de IP do invasor [5], e logo em seguida, foi analisar o histórico daquele usuário suspeito, descobrindo que ele havia tentado se conectar àquele dispositivo mais de 5 vezes [9].
  - Quando Nicholas não está ocupado coordenando as equipes de desenvolvimento e infraestrutura da empresa, ele costuma testar novas soluções tecnológicas diretamente no escritório. Recentemente, a empresa adquiriu uma série de smart locks (fechaduras inteligentes) [1][2] para controlar o acesso às salas de reunião, substituindo os crachás tradicionais. Esses dispositivos permitem monitorar e liberar acessos por meio de um painel centralizado conectado à rede corporativa.
No entanto, embora os smart locks tenham trazido mais praticidade, Nicholas sabe que qualquer dispositivo IoT mal configurado pode representar uma porta de entrada para invasores [6]. Por isso, ele implantou um sistema IDS corporativo [3] especializado em monitorar dispositivos IoT, integrado à infraestrutura de segurança da empresa.
Certa manhã, enquanto revisava relatórios no dashboard, Nicholas recebeu uma notificação crítica [4] do IDS: um endereço IP externo tentava realizar conexões suspeitas com um dos smart locks do andar administrativo. Na análise posterior, descobriram que o invasor tentou explorar vulnerabilidades conhecidas em firmware desatualizado [8].
Graças ao IDS, a ameaça foi identificada antes que conseguisse comprometer a rede interna [7]. Nicholas então estabeleceu uma nova política de atualização automática e monitoramento contínuo [10].

# Análise de Tarefas

> **_NOTE:_**: A equipe deve descrever as funcionalidades mais importantes da interface/produto. A equipe deve modelar pelo menos 1 HTA, 1 GOMS e 1 CTT (de pelo menos 4 funcionalidades diferentes). Cada diagrama deve ter um texto explicando a funcionalidade.

## Tarefa: Analisar Dispositivo da Rede

### 0. Explicação da funcionalidade
- O usuário seleciona um dispositivo (IP/PC/hostname) para inspeção.
- O sistema **carrega traços** (PCAP/logs) ou inicia **captura ao vivo**, usando janela temporal definida.
- Os dados são **pré-processados e transformados em *features*** (estatísticas de fluxo, portas, bytes, flags etc.), passando por **seleção de atributos** via machine learning.
- Aplica-se **modelo bayesiano** e **rede neural profunda**, podendo combinar resultados por *ensemble*.
- O resultado é exibido como **rótulo e score** (Normal/Intruso), com **explicações** (top features) e opção de **relatório em PDF**.

### 1. HTA

![](https://github.com/Westzin/Interface-Humano-Computador/blob/main/Diagramas/HTA/HTA_T1_OF.png)

### 2. GOMS

#### GOAL 0: Analisar Dispositivo da Rede
- **GOAL 1:** Selecionar dispositivo  
  - OP 1.1: Abrir lista/consulta por IP, PC ou hostname  
  - OP 1.2: Aplicar filtro e confirmar seleção  

- **GOAL 2:** Obter traços de rede  
  - OP 2.1: Carregar PCAP/Logs OU iniciar captura  
  - OP 2.2: Definir janela temporal e fonte  

- **GOAL 3:** Pré-processar e extrair features  
  - OP 3.1: Limpar/normalizar dados  
  - OP 3.2: Extrair métricas (flows, portas, bytes, taxa, flags)  
  - OP 3.3: Selecionar *features* via filtros de relevância (ML)  

- **GOAL 4:** Classificar com modelos  
  - METHOD 4.A: Classificar com modelo bayesiano  
    - OP 4.A.1: Executar inferência bayesiana  
    - OP 4.A.2: Capturar probabilidade de intrusão  
  - METHOD 4.B: Classificar com rede neural  
    - OP 4.B.1: Executar predição DNN  
    - OP 4.B.2: Capturar score/softmax  
  - **SEL.RULE:** Usar ambos se disponível; combinar por ensemble  

- **GOAL 5:** Visualizar resultado  
  - METHOD 5.A: Visão simples (UI)  
    - OP 5.A.1: Ler rótulo/score (Normal vs Intruso)  
  - METHOD 5.B: Relatório detalhado (PDF)  
    - OP 5.B.1: Abrir relatório com top features, timeline e amostras  
    - OP 5.B.2: Ver recomendações de ação  

### 3. CTT

![](https://github.com/Westzin/Interface-Humano-Computador/blob/main/Diagramas/CTT/LegendaCTT.png)
![](https://github.com/Westzin/Interface-Humano-Computador/blob/main/Diagramas/CTT/CTT_T1_OF.png)

## Tarefa: Banir Dispositivo da Rede

### 0. Explicação da funcionalidade
- O usuário escolhe o **alvo** (IP/PC), normalmente a partir do resultado da análise.
- Define a **política de bloqueio** (temporário × permanente) e o **escopo** (firewall, VLAN, AP Wi-Fi/SDN).
- O sistema **aplica a regra** (ex.: `iptables`, firewall central, controlador SDN/AP) e **propaga** para a rede.
- A interface permite **verificação** (teste de conectividade) e **registro de auditoria** (quem/quando/motivo), com opção de **desfazer**.

### 1. HTA

![](https://github.com/Westzin/Interface-Humano-Computador/blob/main/Diagramas/HTA/HTA_T2_OF_ATT.png)

### 2. GOMS

#### GOAL 0: Banir Dispositivo da Rede
- **GOAL 1:** Escolher alvo do bloqueio  
  - OP 1.1: Selecionar IP/PC a partir da análise  
  - OP 1.2: Validar identidade do dispositivo  

- **GOAL 2:** Definir política de bloqueio  
  - METHOD 2.A: Bloqueio temporário  
    - OP 2.A.1: Selecionar duração (ex.: 1h, 24h)  
  - METHOD 2.B: Bloqueio permanente  
    - OP 2.B.1: Marcar como permanente e exigir justificativa  
  - OP 2.3: Definir escopo (firewall, VLAN, AP Wi-Fi)  

- **GOAL 3:** Executar bloqueio  
  - OP 3.1: Enviar regra ao firewall/SDN  
  - OP 3.2: Verificar retorno de sucesso  
  - OP 3.3: Propagar para nós relevantes  

- **GOAL 4:** Verificar e registrar  
  - OP 4.1: Testar conectividade do alvo (esperado: bloqueado)  
  - OP 4.2: Registrar log (quem, quando, motivo, evidências)  
  - OP 4.3: Disponibilizar opção de desfazer  

### 3. CTT

![](https://github.com/Westzin/Interface-Humano-Computador/blob/main/Diagramas/CTT/LegendaCTT.png)
![](https://github.com/Westzin/Interface-Humano-Computador/blob/main/Diagramas/CTT/CTT_T2_OF.png)
  
# Prototipacao

![](https://github.com/Westzin/Interface-Humano-Computador/blob/215e4612fce47738f6ff9c6219fbc4cb48d33ba8/PROTOTIPO-HOME.png)
![](https://github.com/Westzin/Interface-Humano-Computador/blob/215e4612fce47738f6ff9c6219fbc4cb48d33ba8/PROTOTIPO-RELATORIO.png)
![](https://github.com/Westzin/Interface-Humano-Computador/blob/215e4612fce47738f6ff9c6219fbc4cb48d33ba8/PROTOTIPO-DETALHES-DIPOSITIVO.png)
 
## Coleta de dados

1. Identificação de Necessidades dos Usuários e Requisitos de IHC:

 ### Que dados coletar?

#### Usuário e hosts em rede

1. Endereço IP e MAC.
2. Nome de dispositivo.
3. Data e hora de acesso a rede.
4. Idade e geolocalização.
5. Numero de dispositivos comunmente em rede.

#### Relação com tecnologia

1. Utilizar desktops ou smartphones.
2. Estar confortavel com o uso de softwares como antivirus

#### Conhecimento do domínio

1. Nivel de dominio basico de computadores.
2. Conhecimento basico/nenhum em redes de computadores.

#### Tarefas

1. Objetivos: Uso do sistema para banir hosts supeitos de sua rede.
2. Tarefas: Todas as tarefas de usuario não precisar ser apoiadas, todas podem e devem ser realizadas individualmente. Assim consideramos a tarefa de banir um host de sua rede, como primaria.
3. Gravidade dos erros: Caso um usuario realize um banimento por engano, uma serie de processos devera ser realizada para reverter este erro.

#### Motivações e valores

1. Atitudes e valores: O usuario prefere um poroduto que seja intuitivo e abstraia os procedimentos que ele esta executando, uma vez que nao possui dominio avancado em redes de computadores.

 ### De quem coletar?

 #### Quem utilizará o sistema

 1. Entusiastas que nao possuem conhecimento tecnico, porem querem sua rede protegida.
 2. Tecnicos em rededs de computadores, que nao precisam de abstracoes, porem querem maior dominio de sua rede.

 #### Quem será afetado por ele

 1. Usuarios que buscam uma rede sem invasores.

  #### Quem é responsável por decidir quais objetivos o sistema deve apoiar e quais funcionalidades ele deve ter

  1. Os desenvolvedores.

2. Aspectos Éticos
   
Sim nosso projeto ira considerar aspectos eticos, o sistema armazenara dados como: enderco IP e MAC, nome de dispositivo e protocolos realizados pelo mesmo, serão respeitados os princípios da autonomia, garantindo o consentimento dos hosts em rede antes do uso do programa, o princípio da não maleficência e beneficência definitivamente sera considerado, uma vez que iremos trabalhar com dados sensiveis que podem comprometer usuarios.

3.​ Ferramentas de Coleta de Dados (três técnicas diferentes)

#### Scripts
- Aplicação: Assim que o programa for configurado e introduzido a rede, um script utilizando a biblioteca `socket` para adquirirmos o endereço IP e `getmac` para endereços MAC.
- Instrumento: Script python

#### Formulário:
- Aplicação: Antes de executar o programa, será realizado um formulario com perguntas basicas, como: "Quantos dispositivos voce conecta em sua rede geralmente?", para identificar-mos o nivel de dominancia do usuário sobre a propria rede. 
- Instrumento: Formulário web React

#### Entrevista Semiestruturada Pós-Uso
- Aplicação: Logo após o teste da aplicação, o pesquisador faz perguntas guiadas por um roteiro curto para entender como o usuário se sentiu
- Instrumento: Roteiro estruturado pelo Google Forms.

## Ciclo de vida da engenharia de usabilidade

1. **Características da Plataforma**  
   
| Característica | Descrição |
| :---- | :---- |
| Descrição do Software | Aplicacao de analise de rede local (LAN) |
| Descrição do Hardware | Computadores de mesa com conexao cabeada a internet, com sistema operacional Windows 7/8/10/11  |
| LISTA DE Capacidades da Plataforma (com explicação) | Captação em tempo real: Pesquisa e analise de comportamento de dispositivos e automaticamente realizada. Processamento em nuvem: Dados sao processados em um super servidor para que nao seja dependente do hardware local do usuario. |
| LISTA DE Restrições da Plataforma (com explicação) | Conexao estavel com a rede: Para o pleno funcionamento do servico, e necessario uma boa conexao com a internet. Servidor sobrecarregado: Muitos algoritimos sao processados pelo lado do servidor, assim causando um gargalo de alguns segundos. |

2. **Princípios Gerais do Projeto (INCREMENTAR TABELA)**     

| Nome | Descrição | Link |
| :---- | :---- | :---- |
| Descrição do Contexto | Um sistema que busca por intrusos (hackers) em uma rede privada domestica, baseado no comportamento do usuario em rede, utilizando de algoritimos bio-inspirados para uma analise precisa  |  |
| Lei Geral de Proteção de Dados (LGPD) \- Lei n.º 13.709/2018 | A LGPD é a legislação brasileira que regulamenta o tratamento de dados pessoais no Brasil. É importante para o projeto porque estabelece regras sobre como os dados dos usuários devem ser coletados, armazenados, processados e protegidos, garantindo sua privacidade e segurança. | [https://www.planalto.gov.br/ccivil\_03/\_ato2015-2018/2018/lei/l13709.htm](https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709.htm) |
| Lei n.º 10.098/2000 \- Lei da Acessibilidade |  Esta lei brasileira estabelece normas gerais e critérios básicos para a promoção da acessibilidade das pessoas com deficiência ou com mobilidade reduzida. É importante para o projeto porque define diretrizes para tornar produtos e serviços, incluindo interfaces de usuário, acessíveis a todos os usuários, independentemente de suas habilidades físicas ou cognitivas. | [https://www.planalto.gov.br/ccivil\_03/leis/l10098.htm](https://www.planalto.gov.br/ccivil_03/leis/l10098.htm) |
| ABNT NBR ISO 9241 Ergonomia da interação humano-sistema |  Esta série de normas brasileiras, baseadas nas normas ISO 9241, fornece diretrizes e orientações para o design centrado no usuário de sistemas interativos, incluindo a concepção de interfaces de usuário. A parte 210 aborda o processo de design centrado no humano, enquanto a parte 11 fornece orientações específicas sobre usabilidade. Essas normas são importantes para o projeto porque estabelecem princípios e métodos para garantir que a interface do usuário atenda às necessidades e expectativas dos usuários. | [https://www.inf.ufsc.br/\~edla.ramos/ine5624/\_Walter/Normas/Parte%2011/iso9241-11F2.pdf](https://www.inf.ufsc.br/~edla.ramos/ine5624/_Walter/Normas/Parte%2011/iso9241-11F2.pdf) |
|  | . |  |

## FIGMA
[Link para o protótipo feito no figma](https://www.figma.com/proto/plJfl37vVXmdxtc0YtbM4O/Untitled?node-id=4-396&t=UAMbQmrPicrESdyM-0&scaling=scale-down&content-scaling=fixed&page-id=4%3A209)


## Modelo de tarefas

## Design

- Pense nas características de Affordances do seu serviço ou poduto. 
    - Que tipo de acessibilidades devem ser consideradas dentro do seu projeto?
- Discuta o papel das expectativas do usuário no projeto deste serviço ou poduto. Qual a importância e pontos a serem considerados se você quiser vender esse serviço ou poduto?

## Planejamento da Avaliação

### 1. Planejamento de Usabilidade utilizando método DECIDE

| Etapa | Descrição |
|-------|------------|
| **D** | Avaliar a usabilidade, clareza e eficiência do sistema de detecção de intrusão em redes IoT. Verificar se os usuários compreendem as notificações, confiam nas informações apresentadas e conseguem agir de forma adequada diante de alertas de segurança. |
| **E** | - Os usuários entendem o propósito e funcionamento do sistema?<br>- Quais informações são mais importantes ao receber um alerta de intrusão?<br>- As notificações são claras e compreensíveis?<br>- O design da interface transmite confiança?<br>- O sistema é fácil de usar para diferentes níveis técnicos?<br>- O usuário consegue distinguir falsos positivos de ameaças reais?<br>- O tempo de resposta do sistema influencia a percepção de segurança?<br>- Há sobrecarga de informações na interface? |
| **C** | Será utilizado o método de avaliação heurística para encontrar problemas durante o processo do design de forma rápida e barata. Além disso, serão utilizados testes com os usuários para avaliar a performance deles usando o sistema, anotando todos os possíveis problemas encontrados na avaliação. |
| **I** | A avaliação heurística é composta por três fases principais:<br>1. Fase de preparação:<br>Os avaliadores devem se familiarizar com a situação atual, incluindo os usuários, o domínio e o contexto de uso. Em seguida, selecionam as partes da interface que serão avaliadas (no caso, todas as telas), definem a lista de heurísticas que serão utilizadas e passam algum tempo explorando a interface de modo geral. É recomendável compreender o fluxo de interação da interface (por exemplo, por meio de um diagrama MOLIC) e alinhar um protocolo comum para a documentação dos achados. <br> 2. Fase de coleta de dados e interpretação:<br>Cada avaliador inspeciona a interface individualmente, identificando possíveis violações das heurísticas. Os problemas encontrados devem ser registrados com as seguintes informações: heurística violada, local da ocorrência, grau de severidade, justificativa e possíveis soluções recomendadas. <br> 3. Fase de consolidação e relato dos resultados:<br>Após as inspeções individuais, os avaliadores reúnem-se para revisar e discutir os problemas identificados, avaliando sua relevância, gravidade e justificativas. Em seguida, elaboram um relatório consolidado que reúne todas as violações e recomendações de melhoria. |
| **D** | Garantir consentimento informado dos participantes. Manter anonimato e confidencialidade dos dados. Evitar exposição de informações reais de rede ou dispositivos IoT. Informar aos participantes que os testes não envolvem riscos reais de intrusão. |
| **E** | Após a etapa de coleta, os resultados da Avaliação Heurística e dos Testes com Usuários serão reunidos em um relatório integrado. Os achados serão organizados conforme seu nível de gravidade, frequência de ocorrência e impacto na experiência do usuário, de modo a priorizar as falhas mais críticas. As métricas quantitativas, como tempo de execução, taxa de sucesso e número de erros, serão analisadas em conjunto com as evidências qualitativas, como comentários, percepções e dificuldades relatadas. O documento final apresentará os principais problemas de interação, suas causas prováveis, as heurísticas violadas e recomendações práticas de melhoria, servindo como base para as próximas versões do sistema. |

### 2. Lista de instrumentos
i) 
Termo de consentimento <br>
ii) Questionários  <br>
iii) Tabela de Observação <br> 
iv) Formulário de avaliação Heuristica. <br>

## Avaliação de IHC através de Inspeção Heurística

### Avaliação de IHC através de Inspeção HEURÍSTICA
**Tabela 1 - Conjunto de heurísticas de Nielsen (1994)**
| Nº | Heurística | Descrição | Análise |
|----|-------------|------------|----------|
| 1 | **Visibilidade do status do sistema** | O sistema deve sempre manter os usuários informados sobre o que está acontecendo através de feedback apropriado, em um tempo razoável. | O sistema exibe todos os dispositivos conectados à rede e indica o nível de gravidade de seus comportamentos. Também fornece relatórios e histórico de atividades, o que garante boa visibilidade sobre o status geral. |
| 2 | **Compatibilidade entre sistema e mundo real** | O sistema deve utilizar a linguagem do usuário, com palavras, frases e conceitos familiares, evitando jargões técnicos. As informações devem seguir uma ordem lógica e natural. | O sistema adota uma linguagem técnica adequada a profissionais de redes e cibersegurança, mas pode dificultar a compreensão por parte de usuários domésticos, que podem não estar familiarizados com os termos utilizados. |
| 3 | **Controle e liberdade para o usuário** | Os usuários devem ter liberdade para desfazer ações ou sair de estados indesejados sem esforço, por meio de comandos como *undo* e *redo*. | O sistema não oferece suporte a *undo* ou *redo*, disponibilizando apenas mecanismos básicos de navegação entre páginas, o que limita a liberdade de correção de ações. |
| 4 | **Consistência e padrões** | Os elementos da interface devem seguir convenções claras e consistentes, evitando que ações ou termos diferentes representem o mesmo conceito. | A interface mantém uma boa consistência visual e terminológica, sem apresentar ambiguidades entre componentes ou funcionalidades. |
| 5 | **Prevenção de erros** | O sistema deve ser projetado para evitar que erros ocorram, reduzindo a frustração e o retrabalho do usuário. | O sistema não oferece suporte preventivo para erros de conexão dos dispositivos, o que pode comprometer a estabilidade da experiência de uso. |
| 6 | **Reconhecimento em vez de lembrança** | As opções e elementos da interface devem ser visíveis e autoexplicativos, reduzindo a necessidade de o usuário memorizar informações. | Apesar de não haver instruções explícitas, a interface é simples, padronizada e intuitiva, o que facilita o uso mesmo sem documentação. |
| 7 | **Flexibilidade e eficiência de uso** | O sistema deve ser eficiente para usuários iniciantes e experientes, permitindo adaptação a diferentes níveis de habilidade. | A presença de jargões técnicos reduz a acessibilidade e eficiência para usuários menos experientes, embora não afete significativamente os profissionais da área. |
| 8 | **Projeto estético e minimalista** | A interface deve conter apenas informações relevantes, evitando elementos desnecessários que possam distrair o usuário. | O sistema adota um design minimalista e objetivo, apresentando apenas informações essenciais para o uso da aplicação. |
| 9 | **Auxiliar no reconhecimento, diagnóstico e recuperação de erros** | As mensagens de erro devem ser claras, indicar precisamente o problema e sugerir uma solução compreensível. | O sistema não exibe mensagens de erro, o que dificulta a identificação e resolução de falhas pelo usuário. |
| 10 | **Ajuda e documentação** | Mesmo que o sistema seja intuitivo, deve oferecer documentação e ajuda de fácil acesso, centradas nas tarefas do usuário. | A interface não possui documentação nem guias de uso, o que pode dificultar o aprendizado inicial e a resolução de dúvidas. |


**Tabela 2 - Grau de severidade dos problemas de usabilidade**
| Grau de severidade | Tipo          | Descrição                                         |
|--------------------|----------------|---------------------------------------------------|
| 0                  | Sem importância | Não afeta a operação da interface                |
| 1                  | Cosmético       | Não há necessidade imediata de solução           |
| 2                  | Simples         | Problema de baixa prioridade (pode ser reparado) |
| 3                  | Grave           | Problema de alta prioridade (deve ser reparado)  |
| 4                  | Catastrófico    | Muito grave, deve ser reparado de qualquer forma |

**Sua tarefa é avaliar o sistema procurando possíveis problemas de usabilidade. Quando um problema qualquer for detectado, classifique-o em uma das dez heurísticas de Nielsen, anotando o problema na tabela correspondente e atribuindo o grau de severidade (0 até 4) para este problema (dado pela tabela 2) e recomece novamente até não encontrar mais problemas de usabilidade.**

### Atividade
| Nº | Heurística Violada | Local | Severidade | Justificativa | Solução Recomendada |
|----|--------------------|-------|-------------|----------------|---------------------|
| 1 | Compatibilidade entre sistema e mundo real | dados do dispositivo | 0 (Sem importância) | A interface só utiliza termos técnicos na página de especificações dos dispositivos e detalhes de conexão. | Nenhuma solução é necessária pois essa página só tem utilidade para usuários técnicos. |
| 2 | Controle e liberdade para o usuário | Navegação entre telas | 3 (Grave) | O sistema não possui suporte para desfazer ou cancelar ações, limitando o controle do usuário em caso de erro. | Implementar funções de *undo* e *redo*. |
| 3 | Prevenção de erros | Conexão de dispositivos | 3 (Grave) | Não há tratamento adequado para falhas de conexão de dispositivos, podendo gerar confusão ou interrupção na operação. | Adicionar verificações preventivas e mensagens claras para orientar o usuário quando ocorrerem falhas de conexão. |
| 4 | Auxiliar no reconhecimento, diagnóstico e recuperação de erros | Mensagens de sistema | 4 (Catastrófico) | A interface não apresenta mensagens de erro compreensíveis, dificultando a identificação e correção de problemas. | Implementar mensagens de erro claras e descritivas, em linguagem natural, indicando a causa e o procedimento para correção. |
| 5 | Ajuda e documentação | tela inicial | 2 (Simples) | O sistema não possui documentação ou guia de uso, o que pode prejudicar novos usuários. | Criar uma seção de ajuda acessível no próprio sistema, com instruções básicas, FAQs e tutoriais rápidos. |
| 6 | Flexibilidade e eficiência de uso | Painel de controle | 1 (Cosmético) | A interface não oferece atalhos nem opções avançadas que agilizem o uso por usuários experientes. | Incluir atalhos de teclado ou personalização de comandos para usuários avançados. |

### LOCAIS
#### Problema Nº1

#### Problema Nº2

#### Problema Nº3
* Não existe imagem para ilustrar esse problema.

#### Problema Nº4
* Não existe imagem para ilustrar esse problema.

#### Problema Nº5


#### Problema Nº6
* Não existe imagem para ilustrar esse problema.


### INDICAÇÃO DE BOAS PRÁTICAS DE HEURÍSTICA
#### Heurística 1: Visibilidade do status do sistema

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
