# Metodologias

## Sumário

- [Metodologias](#metodologias)
  - [Sumário](#sumário)
  - [Tabela de Versionamento](#tabela-de-versionamento)
  - [Introdução](#introdução)
  - [1. Lean Inception](#1-lean-inception)
    - [Visão do Produto](#visão-do-produto)
    - [É, Não É; Faz, Não Faz](#é-não-é-faz-não-faz)
    - [Objetivos do Negócio](#objetivos-do-negócio)
    - [Personas](#personas)
    - [Jornada de Usuário](#jornada-de-usuário)
    - [Brainstorming de Funcionalidades](#brainstorming-de-funcionalidades)
    - [Revisão Técnica, de Negócio e de UX](#revisão-técnica-de-negócio-e-de-ux)
    - [Sequenciador](#sequenciador)
    - [Canvas MVP](#canvas-mvp)
  - [2. Scrum](#2-scrum)
    - [Principais Elementos do Scrum](#principais-elementos-do-scrum)
      - [Sprints](#sprints)
      - [Papéis no Scrum](#papéis-no-scrum)
      - [Artefatos do Scrum](#artefatos-do-scrum)
      - [Eventos do Scrum](#eventos-do-scrum)
      - [Filosofia do Scrum](#filosofia-do-scrum)
  - [3. XP (Extreme Programming)](#3-xp-extreme-programming)
    - [Principais Práticas do XP](#principais-práticas-do-xp)
      - [Programação em Pares](#programação-em-pares)
      - [Cliente Presente](#cliente-presente)
      - [Testes Automatizados e Contínuos](#testes-automatizados-e-contínuos)
      - [Refatoração](#refatoração)
    - [Filosofia do XP](#filosofia-do-xp)
  - [4. Kanban](#4-kanban)
    - [Principais Elementos do Kanban](#principais-elementos-do-kanban)
      - [Quadro Kanban](#quadro-kanban)
      - [Limites de Trabalho em Progresso (WIP)](#limites-de-trabalho-em-progresso-wip)
      - [Melhoria Contínua](#melhoria-contínua)
    - [Aplicação no Desenvolvimento de Software](#aplicação-no-desenvolvimento-de-software)
    - [Vantagens do Kanban](#vantagens-do-kanban)
  - [5. PMBOK (Project Management Body of Knowledge)](#5-pmbok-project-management-body-of-knowledge)
  - [Conclusão](#conclusão)
  - [Referências](#referências)

## Tabela de Versionamento

| Versão | Data       | Responsável  | Descrição                    |
| :------: | :----------: | ------------ | ---------------------------- |
|  1.0   | 2024-12-15 | [Levi Queiroz](https://github.com/LeviQ27) | :memo: #116 - Criação do documento de metodologias |
|  1.1   | 2024-12-15 | [Levi Queiroz](https://github.com/LeviQ27) | :memo: #116 - Inserção do tópico Referências |
|  1.2   | 2024-12-15 | [Levi Queiroz](https://github.com/LeviQ27) | :memo: #116 - Preenchimento dos tópicos |


## Introdução

O desenvolvimento de software é uma atividade complexa que demanda a aplicação de metodologias eficientes para garantir a entrega de produtos de alta qualidade, dentro dos prazos e orçamentos estipulados. Neste documento, serão abordadas algumas das metodologias que a equipe optou por embasamente são Lean Inception, Scrum, XP (Extreme Programming), Kanban e PMBOK. Cada uma dessas práticas oferece características e abordagens específicas, permitindo uma melhor organização, colaboração e agilidade das equipes durante o processo de desenvolvimento.

## 1. Lean Inception

O Lean Inception é uma metodologia ágil voltada para alinhar rapidamente a equipe de desenvolvimento e os stakeholders em relação aos objetivos e ao escopo de um projeto. Sua principal finalidade é facilitar a criação do Produto Mínimo Viável (MVP), uma versão simplificada do produto que permite validar hipóteses iniciais e atender às expectativas do negócio de forma rápida e eficaz.

Por meio de uma série de workshops colaborativos realizados no início do projeto, o Lean Inception busca garantir que todos os envolvidos estejam alinhados quanto às metas e prioridades. As principais etapas dessa abordagem incluem:

### Visão do Produto
Definição de uma declaração clara e inspiradora que descreve o propósito e os objetivos do produto, funcionando como guia para manter o foco na criação de valor para os usuários.

### É, Não É; Faz, Não Faz
Elaboração de listas objetivas que definem o que o produto é e não é, e o que ele faz e não faz, ajudando a evitar mal-entendidos e a estabelecer limites claros.

### Objetivos do Negócio
Identificação de metas específicas, frequentemente expressas em termos quantitativos, como aumento de receita, redução de custos ou melhoria na experiência do cliente, demonstrando a relevância do projeto para a organização.

### Personas
Criação de representações fictícias de usuários que compartilham características e necessidades similares. Essa etapa ajuda a equipe a compreender o público-alvo e a desenvolver soluções adaptadas às suas demandas.

### Jornada de Usuário
Mapeamento do caminho percorrido pelos usuários ao interagir com o produto, identificando pontos de dor, oportunidades de melhoria e momentos cruciais na experiência.

### Brainstorming de Funcionalidades
Sessão criativa para gerar ideias de funcionalidades e recursos que atendam aos objetivos do projeto, promovendo inovação e exploração de diferentes abordagens.

### Revisão Técnica, de Negócio e de UX
Avaliação da viabilidade técnica, do alinhamento com os objetivos de negócio e da qualidade da experiência do usuário (usabilidade e acessibilidade) nas funcionalidades propostas.

### Sequenciador
Ferramenta para priorizar e ordenar as funcionalidades com base em critérios como valor para o usuário e complexidade técnica, ajudando a organizar a implementação ao longo do tempo.

### Canvas MVP
Representação visual do MVP, destacando as funcionalidades essenciais que devem ser desenvolvidas inicialmente para lançar o produto de maneira rápida e eficiente.

Por fim, Lean Inception é uma abordagem estruturada que promove um entendimento claro e compartilhado entre a equipe e os stakeholders desde o início do projeto. Essa estratégia contribui para um desenvolvimento mais assertivo, ágil e alinhado às necessidades do negócio e dos usuários.

## 2. Scrum

O Scrum é um framework ágil projetado para ajudar equipes a resolver problemas complexos de maneira colaborativa e adaptativa, entregando produtos de alto valor de forma incremental e contínua. Baseado em ciclos curtos de desenvolvimento chamados sprints, o Scrum organiza o trabalho em etapas bem definidas que promovem transparência, inspeção e adaptação.

### Principais Elementos do Scrum
#### Sprints
São ciclos de trabalho de curta duração, geralmente entre uma e quatro semanas, nos quais a equipe foca em entregar incrementos funcionais do produto. Cada sprint tem início, metas claras e um prazo definido para conclusão.

#### Papéis no Scrum

- Product Owner (PO): Responsável por maximizar o valor do produto, definindo prioridades no Backlog do Produto e garantindo que a equipe esteja trabalhando no que é mais importante para o negócio.
- Scrum Master: Atua como facilitador do processo, ajudando a equipe a seguir os princípios do Scrum e remover impedimentos que possam afetar o progresso.
- Equipe de Desenvolvimento: Grupo multifuncional responsável por transformar as histórias de usuário em incrementos de produto funcionais.

#### Artefatos do Scrum

- Backlog do Produto: Lista priorizada de requisitos (histórias de usuário) planejados para o desenvolvimento.
- Backlog da Sprint: Subconjunto do Backlog do Produto, contendo as tarefas e histórias a serem desenvolvidas durante uma sprint.

#### Eventos do Scrum

- Planejamento da Sprint:
Reunião inicial de cada sprint, onde a equipe e o PO definem as metas e selecionam as histórias de usuário ou tarefas a serem desenvolvidas. Nesta etapa:

  - Os itens do Backlog do Produto são priorizados pelo PO.
  - A equipe estima o esforço necessário para cada tarefa.
  - As metas da sprint são estabelecidas com base na capacidade da equipe.

- Daily Scrum:
Reunião diária curta (stand-up) onde a equipe compartilha progresso, identifica impedimentos e planeja o dia. No contexto da equipe, um bot no Discord automatiza o monitoramento do progresso, oferecendo atualizações em tempo real.

- Desenvolvimento:
Durante a sprint, a equipe trabalha nas tarefas definidas, escrevendo, testando e implementando código. A colaboração próxima é essencial, com revisões regulares para garantir alinhamento com as metas da sprint.

- Revisão da Sprint:
Reunião realizada ao final da sprint, onde a equipe apresenta os incrementos do produto para o PO e os stakeholders. Durante essa reunião:

  - O trabalho concluído é demonstrado.
  - Feedback é coletado para refinar o Backlog do Produto.

- Retrospectiva da Sprint:
Reunião realizada após a Revisão da Sprint, focada na melhoria contínua. A equipe avalia o que funcionou bem e identifica ações para aprimorar processos e desempenho nas sprints seguintes.

#### Filosofia do Scrum
O Scrum incentiva a comunicação clara, entregas incrementais frequentes e adaptação constante às necessidades do projeto. A combinação de práticas como reuniões estruturadas, artefatos organizados e papéis bem definidos permite que as equipes lidem com mudanças e entreguem valor de forma eficaz. Por meio dessa abordagem, o desenvolvimento se torna mais previsível, colaborativo e orientado para resultados de alta qualidade.

## 3. XP (Extreme Programming)

O Extreme Programming (XP) é uma metodologia ágil que foca em otimizar o processo de desenvolvimento, promovendo alta qualidade de código, colaboração próxima entre a equipe e stakeholders, e entregas rápidas e frequentes. Seu objetivo é garantir que os times cumpram suas tarefas de forma eficiente, minimizando atrasos e custos desnecessários.

### Principais Práticas do XP
#### Programação em Pares
Desenvolvedores trabalham em duplas no mesmo código, compartilhando conhecimento e aumentando a qualidade do software. Essa prática promove maior colaboração, detecção precoce de erros e aprendizado mútuo.

#### Cliente Presente
O cliente ou um representante está envolvido de forma contínua no processo de desenvolvimento. Esse contato direto ajuda a garantir que os requisitos do projeto estejam claros e que as prioridades sejam ajustadas conforme necessário.

#### Testes Automatizados e Contínuos

    - Testes Automatizados: Testes unitários e de aceitação são escritos antes do código e executados automaticamente, garantindo que o software atenda aos requisitos esperados.
    - Testes Contínuos: Toda alteração no código é automaticamente testada (build e deploy), permitindo a identificação de problemas imediatamente e mantendo a integridade do sistema.

#### Refatoração
Algoritmos ou trechos de código são continuamente revisados e simplificados para melhorar sua legibilidade e eficiência. A prática de refatoração reduz a complexidade técnica e facilita a manutenção do software.

- Releases Rápidas
O desenvolvimento é organizado em ciclos curtos que resultam em entregas frequentes de pequenas funcionalidades. Isso permite feedback rápido dos usuários e adaptações contínuas ao projeto.

- Entrega Contínua
Novas funcionalidades são integradas ao produto de forma incremental e frequente, reduzindo o tempo entre o desenvolvimento e o uso real das features pelos usuários finais.

### Filosofia do XP
O XP valoriza a simplicidade, o feedback constante e a adaptação. Ele enfatiza a comunicação direta, a confiança entre os membros da equipe e a proximidade com os stakeholders para assegurar que o produto final atenda às expectativas do cliente. Por meio de suas práticas centradas em qualidade e eficiência, o XP se destaca como uma abordagem ágil ideal para projetos que demandam entregas rápidas e alto nível de colaboração.

## 4. Kanban

O Kanban é uma metodologia visual de gerenciamento de projetos focada no controle eficiente do fluxo de trabalho e na entrega contínua de valor. Originalmente desenvolvido no setor de manufatura, o Kanban é amplamente utilizado em diversas áreas, incluindo o desenvolvimento de software, graças à sua adaptabilidade às necessidades específicas de cada equipe ou negócio.

### Principais Elementos do Kanban

#### Quadro Kanban
Um quadro visual que representa o fluxo de trabalho, organizado em colunas que refletem os diferentes estados das tarefas. Este quadro permite que toda a equipe tenha visibilidade clara do progresso do projeto e das prioridades.

Para o projeto, o quadro Kanban será implementado na plataforma Zenhub, com as seguintes colunas:

- New Issues: Tarefas no backlog ainda não iniciadas.
- Epics: Grupos de tarefas relacionadas aos objetivos de longo prazo.
- Icebox: Tarefas de baixa prioridade ou desejos do cliente, sem previsão imediata de execução.
- Product Backlog: Tarefas planejadas para o desenvolvimento atual do produto.
- Sprint Backlog: Tarefas específicas alocadas para a sprint atual.
In Progress: Tarefas em desenvolvimento, controladas pelos limites de trabalho em progresso (WIP).
- Review/QA: Tarefas em revisão para garantir qualidade antes da entrega.
- Done: Tarefas concluídas durante a sprint atual.
- Closed: Tarefas finalizadas de sprints anteriores.

#### Limites de Trabalho em Progresso (WIP)
O Kanban implementa restrições no número de tarefas em andamento em cada coluna. Esses limites ajudam a equipe a evitar sobrecarga, manter o foco e identificar gargalos no fluxo de trabalho.

#### Melhoria Contínua
O Kanban incentiva a análise constante do fluxo de trabalho para identificar e eliminar ineficiências. Isso permite que a equipe ajuste processos de forma iterativa, otimizando a produtividade e a entrega de valor.

### Aplicação no Desenvolvimento de Software
No contexto de desenvolvimento de software, o Kanban é uma ferramenta poderosa para gerenciar tarefas e priorizar atividades com base nas necessidades do cliente e no progresso do time. Com sua flexibilidade, ele pode ser integrado a outras metodologias ágeis, como Scrum, para criar uma abordagem híbrida que combina os benefícios de ciclos bem definidos com a fluidez do Kanban.

### Vantagens do Kanban
- Adaptabilidade: Pode ser ajustado para atender às demandas específicas do projeto e da equipe.
Transparência: Oferece uma visão clara do status de cada tarefa, facilitando a comunicação entre os membros do time e stakeholders.
- Foco em Entregas: Com o controle do WIP e a organização visual, o Kanban promove a entrega contínua e incremental de valor.

Por sua simplicidade e eficácia, o Kanban se destaca como uma metodologia essencial para equipes que buscam otimizar fluxos de trabalho e manter a agilidade no desenvolvimento de software.

## 5. PMBOK (Project Management Body of Knowledge)

O PMBOK é um guia de boas práticas em gerenciamento de projetos desenvolvido pelo Project Management Institute (PMI). Ele fornece um conjunto abrangente de diretrizes, terminologias e metodologias que ajudam a gerenciar projetos de forma eficiente em diferentes setores e indústrias.

Estrutura do PMBOK
O PMBOK organiza suas práticas em cinco grupos de processos e dez áreas de conhecimento, promovendo uma abordagem estruturada para o gerenciamento de projetos:

Grupos de Processos

Iniciação: Define e autoriza o projeto ou uma de suas fases.
Planejamento: Elabora o plano do projeto, detalha os objetivos e especifica as atividades necessárias para alcançá-los.
Execução: Coordena pessoas e recursos para implementar o plano do projeto.
Monitoramento e Controle: Acompanha o progresso, revisa resultados e regula o desempenho do projeto para garantir o alinhamento com os objetivos estabelecidos.
Encerramento: Formaliza a aceitação do projeto e assegura que todas as atividades sejam concluídas de maneira organizada.
Áreas de Conhecimento

Integração
Escopo
Cronograma
Custo
Qualidade
Recursos
Comunicação
Riscos
Aquisições
Partes Interessadas
Aplicação no Projeto
A aplicação do PMBOK em projetos ágeis, como no caso do desenvolvimento de software, pode complementar metodologias ágeis como Scrum, Kanban ou XP, oferecendo uma estrutura robusta para gerenciar aspectos críticos, como:

Escopo: Gerenciado em conjunto pelo Scrum Master e pelo Product Owner (PO), garantindo que os objetivos do projeto estejam claros e alinhados às prioridades do cliente.
Riscos: Monitorados semanalmente, com planos de resposta desenvolvidos para mitigar possíveis impactos negativos, promovendo maior resiliência no gerenciamento do projeto.
Custo: Avaliado regularmente, proporcionando visibilidade constante do orçamento e permitindo ajustes ao longo do ciclo de vida do projeto.
Integração com Métodos Ágeis
Ao integrar o PMBOK com metodologias ágeis, é possível unir a flexibilidade e adaptabilidade dos métodos ágeis com a abordagem estruturada e analítica do PMBOK. Essa combinação permite que equipes:

Alavanquem a eficiência operacional em áreas críticas, como gerenciamento de custos e riscos.
Mantenham um equilíbrio entre entregas iterativas e o alcance dos objetivos estratégicos do projeto.
Garantam a entrega de valor contínuo, sem perder o controle sobre os recursos e prazos.
O PMBOK, quando adaptado à realidade de projetos ágeis, se torna uma poderosa ferramenta para aprimorar a governança e maximizar o sucesso dos projetos.

## Conclusão

As metodologias e frameworks apresentados – como Lean Inception, Scrum, Extreme Programming (XP), Kanban e o PMBOK – oferecem abordagens complementares que auxiliam equipes a organizar, executar e monitorar projetos de forma eficiente. Cada método traz benefícios específicos que podem ser combinados para atender às necessidades de diferentes equipes e contextos, maximizando o valor entregue aos stakeholders.

A integração de práticas ágeis com diretrizes estruturadas, como as do PMBOK, permite maior flexibilidade e controle, promovendo entregas contínuas e alinhadas aos objetivos estratégicos. Por meio da aplicação consciente dessas metodologias, equipes podem lidar com complexidades do desenvolvimento de software, garantindo qualidade, satisfação do cliente e aderência ao prazo e orçamento.

## Referências

> Project Management Institute. A Guide to the Project Management Body of Knowledge (PMBOK® Guide). 6th Edition.
> Schwaber, Ken; Sutherland, Jeff. The Scrum Guide. Scrum.org.
> Beck, Kent. Extreme Programming Explained: Embrace Change. 2nd Edition.
> Anderson, David J. Kanban: Successful Evolutionary Change for Your Technology Business.
> Poppendieck, Mary; Poppendieck, Tom. Lean Software Development: An Agile Toolkit.