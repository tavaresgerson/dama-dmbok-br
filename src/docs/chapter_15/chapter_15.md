# Avaliação de Maturidade em Gestão de Dados

## 1. Introdução

A Avaliação de Maturidade de Capacidades (CMA) é uma abordagem para melhoria de processos baseada em uma estrutura – um Modelo de Maturidade de Capacidades (CMM) – que descreve como as características de um processo evoluem de ad hoc para ótimo. O conceito de CMA surgiu dos esforços do Departamento de Defesa dos Estados Unidos para estabelecer critérios para avaliar fornecedores de software. Em meados da década de 1980, o Modelo de Maturidade de Capacidades para Software foi publicado pelo Instituto de Engenharia de Software da Universidade Carnegie-Mellon. Embora inicialmente aplicados ao desenvolvimento de software, os CMMs foram desenvolvidos para uma variedade de outras áreas, incluindo a gestão de dados.

Os modelos de maturidade são definidos em termos de uma progressão por níveis que descrevem as características do processo. Quando uma organização adquire uma compreensão das características do processo, ela pode avaliar seu nível de maturidade e implementar um plano para aprimorar suas capacidades. Ela também pode mensurar a melhoria e se comparar com concorrentes ou parceiros, guiada pelos níveis do modelo. A cada novo nível, a execução do processo se torna mais consistente, previsível e confiável. Os processos melhoram à medida que assumem as características dos níveis. A progressão ocorre em uma ordem definida. Nenhum nível pode ser pulado. Os níveis geralmente incluem: [^96]

* **Nível 0:** Ausência de capacidade
* **Nível 1:** Inicial ou Ad Hoc: O sucesso depende da competência dos indivíduos
* **Nível 2:** Repetível: Disciplina mínima de processo em vigor
* **Nível 3:** Definido: Padrões são definidos e utilizados
* **Nível 4:** Gerenciado: Processos são quantificados e controlados
* **Nível 5:** Otimizado: Metas de melhoria de processo são quantificadas

Dentro de cada nível, os critérios são descritos em todas as características do processo. Por exemplo, um modelo de maturidade pode incluir critérios relacionados à forma como os processos são executados, incluindo o nível de automação desses processos. Ele pode se concentrar em políticas e controles, bem como em detalhes do processo.

Essa avaliação ajuda a identificar o que está funcionando bem, o que não está funcionando bem e onde uma organização apresenta lacunas. Com base nas descobertas, a organização pode desenvolver um roteiro para atingir:

* Oportunidades de melhoria de alto valor relacionadas a processos, métodos, recursos e automação
* Capacidades alinhadas à estratégia de negócios
* Processos de governança para avaliação periódica do progresso organizacional com base nas características do modelo

Uma Avaliação de Maturidade em Gestão de Dados (DMMA) pode ser usada para avaliar a gestão de dados como um todo ou para focar em uma única Área de Conhecimento ou até mesmo em um único processo. Seja qual for o foco, uma DMMA pode ajudar a preencher a lacuna entre as perspectivas de negócios e de TI sobre a saúde e a eficácia das práticas de gestão de dados. Uma DMMA fornece uma linguagem comum para descrever o progresso em todas as Áreas de Conhecimento em Gestão de Dados e oferece um caminho para a melhoria baseado em estágios, que pode ser adaptado às prioridades estratégicas de uma organização. [^97] Portanto, pode ser usada tanto para definir quanto para mensurar metas organizacionais, bem como para comparar a organização com outras organizações ou benchmarks do setor.

Antes de iniciar qualquer DMMA, uma organização precisa estabelecer uma compreensão básica de seu estado atual de capacidades, ativos, metas e prioridades. Um certo nível de maturidade organizacional é necessário para conduzir a avaliação em primeiro lugar, bem como para responder efetivamente aos resultados da avaliação definindo metas, estabelecendo um roteiro e monitorando o progresso.

### 1.1 Impulsionadores de Negócios

As organizações realizam avaliações de maturidade de capacidade por diversos motivos:

* Regulamentação: A supervisão regulatória exige níveis mínimos de maturidade em gerenciamento de dados.
* Governança de Dados: A função de governança de dados exige uma avaliação de maturidade para fins de planejamento e conformidade.
* Prontidão organizacional para melhoria de processos: Uma organização reconhece a necessidade de aprimorar suas práticas e começa avaliando seu estado atual. Por exemplo, ela se compromete a gerenciar Dados Mestres e precisa avaliar sua prontidão para implantar processos e ferramentas de MDM.
* Mudança organizacional: Uma mudança organizacional, como uma fusão, apresenta desafios de gerenciamento de dados. Uma DMMA fornece informações para o planejamento para enfrentar esses desafios.
* Novas tecnologias: Os avanços tecnológicos oferecem novas maneiras de gerenciar e usar dados. A organização deseja entender a probabilidade de adoção bem-sucedida.
* Problemas de gerenciamento de dados: Há necessidade de abordar problemas de qualidade de dados ou outros desafios de gerenciamento de dados, e a organização deseja estabelecer uma linha de base para seu estado atual a fim de tomar melhores decisões sobre como implementar a mudança.

![Figura 103 Diagrama de Contexto: Avaliação de Maturidade em Gestão de Dados](figure_103.png)
Figura 103 Diagrama de Contexto: Avaliação de Maturidade em Gestão de Dados

### 1.2 Metas e Princípios

O principal objetivo de uma avaliação de capacidade de gestão de dados é avaliar o estado atual das atividades críticas de gestão de dados para planejar melhorias. A avaliação coloca a organização na escala de maturidade, esclarecendo pontos fortes e fracos específicos. Ela ajuda a organização a identificar, priorizar e implementar oportunidades de melhoria.

Ao atingir seu objetivo principal, uma DMMA pode ter um impacto positivo na cultura. Ela ajuda a:

* Educar as partes interessadas sobre os conceitos, princípios e práticas de gestão de dados
* Esclarecer as funções e responsabilidades das partes interessadas em relação aos dados organizacionais
* Destacar a necessidade de gerenciar dados como um ativo crítico
* Ampliar o reconhecimento das atividades de gestão de dados em toda a organização
* Contribuir para melhorar a colaboração necessária para uma governança de dados eficaz

Com base nos resultados da avaliação, uma organização pode aprimorar seu programa de Gestão de Dados para que ele apoie a direção operacional e estratégica da organização. Normalmente, os programas de Gestão de Dados se desenvolvem em silos organizacionais. Raramente começam com uma visão corporativa dos dados. Uma DMMA pode equipar a organização para desenvolver uma visão coesa que suporte a estratégia organizacional geral. Uma DMMA permite que a organização esclareça prioridades, cristalize objetivos e desenvolva um plano integrado de melhorias.

### 1.3 Conceitos Essenciais

#### 1.3.1 Níveis e Características da Avaliação

Os CMMs geralmente definem cinco ou seis níveis de maturidade, cada um com suas próprias características, que vão desde inexistente ou ad hoc até otimizado ou de alto desempenho. Veja a Figura 104 para uma visualização de exemplo. A seguir, um resumo genérico dos macroestados de maturidade da gestão de dados. Uma avaliação detalhada incluiria critérios para subcategorias como estratégia, política, padrões, definição de papéis, etc., dentro de cada uma das Áreas de Conhecimento.

* **Nível 0: Sem Capacidade:** Não há práticas organizadas de gestão de dados ou processos corporativos formais para gerenciar dados. Existem muito poucas organizações no Nível 0. Este nível é reconhecido em um modelo de maturidade para fins de definição.

* **Nível 1 Inicial / Ad Hoc:** Gerenciamento de dados de uso geral, utilizando um conjunto limitado de ferramentas, com pouca ou nenhuma governança. O tratamento de dados depende fortemente de poucos especialistas. Funções e responsabilidades são definidas em silos. Cada proprietário de dados recebe, gera e envia dados de forma autônoma. Os controles, se existentes, são aplicados de forma inconsistente. As soluções para o gerenciamento de dados são limitadas. Problemas de qualidade de dados são generalizados, mas não são resolvidos. Os suportes de infraestrutura estão no nível da unidade de negócios.

![Figura 104 Exemplo de Modelo de Maturidade em Gerenciamento de Dados](figure_104.png)
Figura 104 Exemplo de Modelo de Maturidade em Gerenciamento de Dados

Os critérios de avaliação podem incluir a presença de quaisquer controles de processo, como o registro de problemas de qualidade de dados.

* **Nível 2 Repetível:** Surgimento de ferramentas consistentes e definição de papéis para apoiar a execução dos processos. No Nível 2, a organização começa a utilizar ferramentas centralizadas e a fornecer maior supervisão para o gerenciamento de dados. Os papéis são definidos e os processos não dependem apenas de especialistas específicos. Há consciência organizacional sobre questões e conceitos de qualidade de dados. Os conceitos de Dados Mestres e de Referência começam a ser reconhecidos.

Os critérios de avaliação podem incluir a definição formal de papéis em artefatos como descrições de cargos, a existência de documentação de processos e a capacidade de utilizar conjuntos de ferramentas.

* **Nível 3 Definido:** Capacidade emergente de gerenciamento de dados. O Nível 3 prevê a introdução e a institucionalização de processos escaláveis ​​de gerenciamento de dados e uma visão do Gerenciamento de Dados como um facilitador organizacional. As características incluem a replicação de dados em uma organização com alguns controles implementados e um aumento geral na qualidade geral dos dados, juntamente com a definição e o gerenciamento coordenados de políticas. Uma definição mais formal de processos leva a uma redução significativa na intervenção manual. Isso, juntamente com um processo de design centralizado, significa que os resultados do processo são mais previsíveis.

Os critérios de avaliação podem incluir a existência de políticas de gerenciamento de dados, o uso de processos escaláveis ​​e a consistência dos modelos de dados e controles do sistema.

* **Nível 4** Gerenciado: O conhecimento institucional adquirido com o crescimento nos Níveis 1 a 3 permite que a organização preveja resultados ao abordar novos projetos e tarefas e comece a gerenciar riscos relacionados aos dados. O gerenciamento de dados inclui métricas de desempenho. As características do Nível 4 incluem ferramentas padronizadas para gerenciamento de dados, do desktop à infraestrutura, juntamente com uma função centralizada de planejamento e governança bem estruturada. Expressões deste nível são um aumento mensurável na qualidade dos dados e em recursos em toda a organização, como auditorias de dados de ponta a ponta.

Os critérios de avaliação podem incluir métricas relacionadas ao sucesso do projeto, métricas operacionais para sistemas e métricas de qualidade de dados.

* **Nível 5:** Otimização: Quando as práticas de gerenciamento de dados são otimizadas, elas são altamente previsíveis, devido à automação de processos e ao gerenciamento de mudanças tecnológicas. Organizações neste nível de maturidade focam na melhoria contínua. No Nível 5, as ferramentas permitem uma visão dos dados em todos os processos. A proliferação de dados é controlada para evitar duplicações desnecessárias. Métricas bem compreendidas são utilizadas para gerenciar e mensurar a qualidade dos dados e dos processos.

Os critérios de avaliação podem incluir artefatos de gestão de mudanças e métricas de melhoria de processos.

#### 1.3.2 Critérios de Avaliação

Cada nível de capacidade terá critérios de avaliação específicos relacionados aos processos avaliados. Por exemplo, se a maturidade da função de modelagem de dados estiver sendo avaliada, o nível 1 pode perguntar se existe alguma prática de modelagem de dados e a quantos sistemas ela se estende; o nível 2 pode perguntar se uma abordagem para modelagem de dados corporativos foi definida; o nível 3 perguntará o grau de implementação da abordagem; o nível 4 perguntará se os padrões de modelagem foram efetivamente aplicados; e o nível 5 perguntará sobre os processos em vigor para aprimorar as práticas de modelagem. (Consulte o Capítulo 5.)

Em qualquer nível, os critérios de avaliação serão avaliados em uma escala, como 1 – Não iniciado, 2 – Em andamento, 3 – Funcional, 4 – Eficaz, mostrando o progresso dentro desse nível e o movimento em direção ao próximo nível. As pontuações podem ser combinadas ou exibidas visualmente para permitir a compreensão da variação entre o estado atual e o desejado. Ao avaliar usando um modelo que pode ser mapeado para uma Área de Conhecimento em Gerenciamento de Dados DAMA-DMBOK, os critérios podem ser formulados com base nas categorias do Diagrama de Contexto:

* **Atividade:** Em que grau a atividade ou processo está em vigor? Os critérios estão definidos para uma execução eficaz e eficiente? Quão bem definida e executada é a atividade? Os resultados das melhores práticas são produzidos?
* **Ferramentas:** Em que grau a atividade é automatizada e suportada por um conjunto comum de ferramentas? O treinamento em ferramentas é fornecido dentro de funções e responsabilidades específicas? As ferramentas estão disponíveis quando e onde necessário? Elas estão configuradas de forma otimizada para fornecer os resultados mais eficazes e eficientes? Em que medida o planejamento tecnológico de longo prazo está em vigor para acomodar as capacidades do estado futuro?
* **Padrões:** Em que grau a atividade é suportada por um conjunto comum de padrões? Quão bem documentados são os padrões? Os padrões são aplicados e suportados pela governança e gestão de mudanças?
* **Pessoas e recursos:** Em que grau a organização possui pessoal para executar a atividade? Quais habilidades, treinamento e conhecimento específicos são necessários para executar a atividade? Quão bem as funções e responsabilidades são definidas?

A Figura 105 ilustra uma maneira de apresentar um resumo visual das descobertas de um DMMA. Para cada uma das capacidades (Governança, Arquitetura, etc.), o anel externo da tela mostra o nível de capacidade que a organização determinou ser necessário para competir com sucesso. O anel interno exibe o nível de capacidade determinado pela avaliação. As áreas onde a distância entre os dois anéis é maior representam os maiores riscos para a organização. Esse relatório pode ajudar a definir prioridades. Também pode ser usado para medir o progresso ao longo do tempo.

![Figura 105 Exemplo de uma Visualização de Avaliação de Maturidade em Gestão de Dados](figure_105.png)
Figura 105 Exemplo de uma Visualização de Avaliação de Maturidade em Gestão de Dados

#### 1.3.3 Frameworks de DMMA Existentes [^98]

Um framework de avaliação de maturidade em gestão de dados é segmentado em tópicos discretos de gestão de dados. O foco e o conteúdo do framework variam dependendo se eles têm um foco geral ou específico do setor. No entanto, a maioria aborda assuntos que podem ser mapeados para as Áreas de Conhecimento DAMA-DMBOK. Os exemplos abaixo pretendem ilustrar a gama de Modelos de Maturidade de Capacidades que foram desenvolvidos na área de gerenciamento de dados. Muitos fornecedores desenvolveram seus próprios modelos. As organizações devem avaliar vários modelos antes de escolher um fornecedor ou antes de desenvolver sua própria estrutura.

##### 1.3.3.1 Modelo de Maturidade em Gerenciamento de Dados (DMM) do CMMI

O CMMI (Capability Maturity Model Institute) desenvolveu o CMMI-DMM (Modelo de Maturidade em Gerenciamento de Dados), que fornece critérios de avaliação para as seguintes áreas de gerenciamento de dados:

* Estratégia de Gerenciamento de Dados
* Governança de Dados
* Qualidade de Dados
* Plataforma e Arquitetura
* Operações de Dados
* Processos de Suporte

Dentro de cada um desses processos, o modelo identifica subprocessos para avaliação. Por exemplo, a seção Qualidade de Dados considera a Estratégia de Qualidade de Dados e a Avaliação, Criação de Perfil e Limpeza da Qualidade de Dados. O modelo também considera a relação entre as áreas de gerenciamento de dados. Por exemplo, a necessidade de alinhamento das partes interessadas e a relação entre os processos de negócios e o Gerenciamento de Qualidade de Dados. [^99]

##### 1.3.3.2 DCAM do Conselho de EDM [^100]

O Enterprise Data Management Council, uma organização de defesa do setor de serviços financeiros com sede nos Estados Unidos, desenvolveu o DCAM (Modelo de Avaliação de Capacidades de Gestão de Dados). Resultado de um esforço conjunto de membros para obter consenso sobre as melhores práticas de gestão de dados, o DCAM descreve 37 capacidades e 115 subcapacidades associadas ao desenvolvimento de um programa sustentável de Gestão de Dados. A pontuação se concentra no nível de engajamento das partes interessadas, na formalidade do processo e na existência de artefatos que demonstram a obtenção das capacidades.

##### 1.3.3.3 Modelo de Maturidade do Conselho de Governança de Dados da IBM [^101]

O Modelo de Maturidade do Conselho de Governança de Dados da IBM foi baseado nas contribuições de um conselho de 55 organizações. Os membros do conselho colaboraram para definir um conjunto comum de comportamentos observáveis ​​e desejados que as organizações podem usar para avaliar e projetar seus próprios programas de governança de dados. O objetivo do modelo é ajudar as organizações a construir consistência e controle de qualidade na governança por meio de tecnologias de negócios comprovadas, métodos colaborativos e melhores práticas. O modelo é organizado em quatro categorias principais:

* **Resultados:** Gestão de riscos de dados e conformidade, criação de valor
* **Facilitadores:** Estrutura organizacional e conscientização, política, administração
* **Disciplinas principais:** Gestão da Qualidade de Dados, gestão do ciclo de vida da informação, segurança da informação e privacidade
* **Disciplinas de Suporte:** Arquitetura de Dados, classificação e Metadados, informações de auditoria, registro e relatórios

O modelo da IBM é apresentado como uma Estrutura de Maturidade e como um conjunto de perguntas de avaliação com respostas construídas para indicar os níveis de maturidade.

##### 1.3.3.4 Modelo de Maturidade de Governança de Dados de Stanford [^102]

O Modelo de Maturidade de Governança de Dados de Stanford foi desenvolvido para uso pela Universidade; não se destinava a ser um padrão do setor. Mesmo assim, serve como um exemplo sólido de um modelo que fornece orientação e um padrão de mensuração. O modelo se concentra na governança de dados, não na gestão de dados, mas, ainda assim, fornece uma base para avaliar a gestão de dados em geral. O modelo diferencia entre componentes fundamentais (conscientização, formalização, metadados) e de projeto (administração de dados, qualidade de dados, dados mestres). Dentro de cada um, articula os motivadores para pessoas, políticas e capacidades. Em seguida, articula as características de cada nível de maturidade. Também fornece métricas qualitativas e quantitativas para cada nível.

##### 1.3.3.5 Modelo de Maturidade em Gestão da Informação Corporativa da Gartner

A Gartner publicou um modelo de maturidade em Gestão da Informação Corporativa (EIM), que estabelece critérios para avaliar visão, estratégia, métricas, governança, papéis e responsabilidades, ciclo de vida e infraestrutura.

## 2. Atividades

Avaliações de Maturidade em Gestão de Dados exigem planejamento. Para garantir resultados práticos e acionáveis, reserve um tempo dentro do plano para a preparação de materiais e a avaliação dos resultados. As avaliações devem ser realizadas em um prazo curto e definido. O objetivo da avaliação é expor os pontos fortes atuais e as oportunidades de melhoria – não resolver problemas.

As avaliações são realizadas por meio da solicitação de conhecimento de participantes de negócios, gestão de dados e tecnologia da informação. O objetivo é chegar a uma visão consensual das capacidades do estado atual, apoiada por evidências. As evidências podem vir da análise de artefatos (como a existência de backups de banco de dados), de entrevistas (verificando se alguém está realizando a avaliação do sistema de registros para reutilização) ou de ambos.

As avaliações podem e devem ser dimensionadas para atender às necessidades da organização. No entanto, faça alterações com cuidado. Os modelos podem perder o rigor ou a rastreabilidade da intenção original se forem encurtados ou editados. Mantenha a integridade do modelo intacta ao personalizá-lo.

### 2.1 Planejar as Atividades de Avaliação

O planejamento de uma avaliação inclui a definição da abordagem geral e a comunicação com as partes interessadas antes e durante a avaliação para garantir o seu engajamento. A avaliação em si inclui a coleta e a avaliação de insumos e a comunicação de resultados, recomendações e planos de ação.

#### 2.1.1 Definir Objetivos

Qualquer organização que decida avaliar seu nível de maturidade em gerenciamento de dados já está engajada no esforço de aprimorar suas práticas. Na maioria dos casos, essa organização já terá identificado os motivadores da avaliação. Esses direcionadores devem ser esclarecidos na forma de objetivos que descrevam o foco e influenciem o escopo da avaliação. Os objetivos da avaliação devem ser claramente compreendidos pelos executivos e pelas linhas de negócios, que podem ajudar a garantir o alinhamento com a direção estratégica da organização.

Os objetivos da avaliação também fornecem critérios para avaliar qual modelo de avaliação adotar, quais áreas de negócios priorizar para avaliação e quem deve contribuir diretamente para o processo.

#### 2.1.2 Escolha uma Estrutura

Conforme descrito na Seção 1.3.3, as estruturas existentes concentram-se em diferentes aspectos da gestão de dados. Revise essas estruturas no contexto de premissas sobre o estado atual e os objetivos da avaliação, a fim de escolher uma que informe a organização de maneira significativa. As áreas de foco do modelo de avaliação podem ser personalizadas com base no foco ou escopo organizacional.

A escolha da estrutura influencia a forma como a avaliação é conduzida. A equipe que trabalha nela deve ter experiência no modelo e na metodologia da qual ele depende.

#### 2.1.3 Definir o Escopo Organizacional

A maioria das Estruturas DMM é projetada para ser aplicada a uma empresa inteira. No entanto, um escopo que abranja toda a empresa pode ser impraticável. Para uma primeira avaliação, geralmente é melhor definir um escopo gerenciável, como uma única área de negócios ou programa. As áreas escolhidas representam um subconjunto significativo da organização e os participantes devem ser capazes de influenciar os principais processos de negócios que afetam os ativos de dados dentro do escopo. Como parte de uma abordagem em fases, a avaliação pode ser repetida para outras partes da organização. Existem compensações entre avaliações locais e empresariais:

* As avaliações localizadas podem se aprofundar muito mais nos detalhes. Elas também podem ser realizadas mais rapidamente, pois o escopo é restrito. Para realizar uma avaliação localizada, selecione uma função altamente regulamentada, como relatórios financeiros em uma empresa de capital aberto. As entradas, funções, ferramentas e consumidores podem estar fora das funções avaliadas, o que pode complicar o escopo e a execução da avaliação. Avaliações localizadas bem planejadas podem frequentemente ser agregadas e ponderadas para formar uma avaliação empresarial, uma vez que muitos ativos de dados são compartilhados.
* As avaliações empresariais concentram-se nas partes amplas e, às vezes, desconexas de uma organização. Uma avaliação empresarial pode ser criada a partir de DMMAs localizadas ou pode ser uma tarefa separada. Por exemplo, uma organização pode avaliar diferentes funções (pesquisa e desenvolvimento, manufatura e financiamento) com base nos mesmos critérios. As entradas, funções, ferramentas e consumidores são normalmente pan-empresariais e multiníveis.

#### 2.1.4 Definir a Abordagem de Interação

Ao conduzir uma DMMA, uma organização deve seguir as recomendações para o modelo selecionado. As atividades de coleta de informações podem incluir workshops, entrevistas, pesquisas e revisões de artefatos. Empregue métodos que funcionem bem dentro da cultura organizacional, minimizem o tempo dedicado pelos participantes e permitam que a avaliação seja concluída rapidamente, para que as ações da avaliação possam ser definidas enquanto o processo ainda está fresco na mente dos participantes.

Em todos os casos, as respostas precisarão ser formalizadas, solicitando que os participantes avaliem os critérios de avaliação. Em muitos casos, a avaliação também incluirá inspeção e avaliação reais de artefatos e outras evidências.

Se houver atrasos na conclusão da avaliação, as partes interessadas provavelmente perderão o entusiasmo pelo programa de Gestão de Dados e o ímpeto de contribuir para uma mudança positiva. É aconselhável evitar análises detalhadas e abrangentes e enfatizar o bom senso com base na expertise dos líderes da avaliação. As Estruturas DMM fornecem os critérios de mensuração e um caminho integrado para a melhoria. Isso permite a síntese de um panorama completo do programa de Gestão de Dados atual e de suas partes.

#### 2.1.5 Planejar as Comunicações

As comunicações contribuem para o sucesso geral da avaliação e para os itens de ação resultantes dela. A comunicação será direcionada aos participantes e outras partes interessadas. As descobertas podem impactar o trabalho das pessoas, por meio de mudanças na metodologia e no alinhamento organizacional, por isso é importante comunicar claramente o propósito, o processo e as expectativas específicas para indivíduos e grupos. Certifique-se de que os participantes entendam o modelo de avaliação, bem como como as descobertas serão utilizadas.

Antes do início da avaliação, as partes interessadas devem ser informadas sobre as expectativas para a avaliação. As comunicações devem descrever:

* O propósito do DMMA
* Como será conduzido
* Qual poderá ser o seu envolvimento
* O cronograma das atividades de avaliação

Durante qualquer atividade da avaliação (por exemplo, uma reunião de grupo focal), certifique-se de que haja uma agenda clara, incluindo um plano para responder a quaisquer perguntas de acompanhamento. Lembre continuamente os participantes das metas e objetivos. Sempre agradeça aos participantes e descreva os próximos passos.

Determine se a abordagem planejada tem probabilidade de sucesso em todo o escopo de negócios visado, incluindo fatores como resistência/cooperação, possíveis preocupações legais internas sobre a exposição à inspeção externa caso sejam encontradas lacunas preocupantes, ou possíveis preocupações com Recursos Humanos.

O plano de comunicação deve incluir um cronograma para relatar as descobertas e recomendações em todos os níveis, incluindo relatórios gerais e briefings executivos.

### 2.2 Realizar a Avaliação de Maturidade

#### 2.2.1 Coletar Informações

O próximo passo é coletar as informações apropriadas para a avaliação, com base no modelo de interação. No mínimo, as informações coletadas incluirão classificações formais dos critérios de avaliação. Também podem incluir informações de entrevistas e grupos focais, análise de sistemas e documentação de design, investigação de dados, sequências de e-mails, manuais de procedimentos, padrões, políticas, repositórios de arquivos, fluxos de trabalho de aprovação, diversos produtos de trabalho, repositórios de metadados, arquiteturas de referência de dados e integração, modelos e formulários.

#### 2.2.2 Realizar a Avaliação

As atribuições e interpretações gerais das avaliações são normalmente multifásicas. Os participantes terão opiniões diferentes, gerando classificações diferentes entre os tópicos da avaliação. Discussão e racionalização serão necessárias para reconciliar as classificações. As informações são fornecidas pelos participantes e, em seguida, refinadas por meio de revisões de artefatos ou análise pela equipe de avaliação. O objetivo é chegar a uma visão consensual do estado atual. Essa visão deve ser apoiada por evidências (ou seja, comprovação de prática demonstrada por comportamento e artefatos). Se as partes interessadas não chegarem a um consenso sobre o estado atual, será difícil chegar a um consenso sobre como melhorar a organização.

O refinamento geralmente funciona da seguinte forma:

* Analisar os resultados em relação ao método de classificação e atribuir uma classificação preliminar a cada produto de trabalho ou atividade.
* Documentar as evidências de apoio.
* Revisar com os participantes para chegar a um consenso sobre uma classificação final para cada área. Se apropriado, usar modificadores de peso com base na importância de cada critério.
* Documentar a interpretação da classificação usando as declarações de critérios do modelo e os comentários do avaliador.
* Desenvolver visualizações para ilustrar os resultados da avaliação.

### 2.3 Interpretar os Resultados

A interpretação dos resultados consiste em identificar oportunidades de melhoria alinhadas à estratégia organizacional e recomendar as ações necessárias para aproveitar essas oportunidades. Em outras palavras, a interpretação define os próximos passos em direção a um estado-alvo. Quando a avaliação estiver concluída, as organizações precisam planejar o estado-alvo que desejam alcançar em gerenciamento de dados. O tempo e o esforço necessários para atingir a meta desejada variam, dependendo do ponto de partida, da cultura da organização e dos motivadores da mudança.

Ao apresentar os resultados da avaliação, comece com o significado das classificações para a organização. As classificações podem ser expressas em relação aos motivadores organizacionais e culturais, bem como às metas de negócios, como satisfação do cliente ou aumento nas vendas. Ilustre a ligação entre as capacidades atuais da organização e os processos e estratégias de negócios que elas suportam, e os benefícios de aprimorar essas capacidades ao atingir o estado-alvo.

#### 2.3.1 Relatar os Resultados da Avaliação

O relatório de avaliação deve incluir:

* Motivadores de negócios para a avaliação
* Resultados gerais da avaliação
* Classificações por tópico com as lacunas indicadas
* Uma abordagem recomendada para eliminar as lacunas
* Pontos fortes da organização conforme observados
* Riscos para o progresso
* Opções de investimento e resultados
* Governança e métricas para medir o progresso
* Análise de recursos e potencial utilização futura
* Artefatos que podem ser usados ​​ou reutilizados dentro da organização

O relatório de avaliação é uma contribuição para o aprimoramento do programa de Gestão de Dados, seja como um todo ou por Área de Conhecimento em Gestão de Dados. A partir dele, a organização pode desenvolver ou aprimorar sua estratégia de gestão de dados. A estratégia deve incluir iniciativas que promovam os objetivos de negócios por meio da melhoria da governança de processos e padrões.

#### 2.3.2 Desenvolver Briefings Executivos

A equipe de avaliação deve preparar briefings executivos que resumam as descobertas – pontos fortes, lacunas e recomendações – que os executivos usarão como subsídio para decisões sobre metas, iniciativas e cronogramas. A equipe deve adaptar as mensagens para esclarecer os prováveis ​​impactos e benefícios para cada grupo executivo. Frequentemente, os executivos desejam atingir metas mais altas do que as recomendações da avaliação. Em outras palavras, eles querem pular níveis no modelo de maturidade. A busca por um nível mais alto de maturidade deve ser refletida na análise de impacto das recomendações. Há um custo para esse tipo de aceleração, e os custos devem ser ponderados em relação aos benefícios.

### 2.4 Criar um Programa Direcionado para Melhorias

O DMMA deve ter um impacto direto na estratégia de dados e na governança de TI, bem como no programa e na estratégia de Gerenciamento de Dados. As recomendações do DMMA devem ser acionáveis. Elas devem descrever as capacidades que a organização requer. Ao fazer isso, uma avaliação pode ser uma ferramenta poderosa para líderes de TI e negócios definirem prioridades organizacionais e alocarem recursos.

#### 2.4.1 Identificar Ações e Criar um Roteiro

As classificações DMMA destacam itens que exigem atenção da gerência. Inicialmente, uma classificação provavelmente será usada como uma métrica independente para determinar o quão bem uma organização está realizando uma atividade específica. No entanto, as classificações podem ser rapidamente operacionalizadas em medidas contínuas, especialmente para atividades em que a mudança é desejada (por exemplo, "A meta é nível 'n' porque precisamos ou queremos ser capazes de fazer algo 'z'"). Se o modelo de avaliação for usado para mensuração contínua, seus critérios não apenas guiarão a organização para níveis mais elevados de maturidade, como também manterão a atenção da organização nos esforços de melhoria.

Os resultados da avaliação DMM devem ser detalhados e abrangentes o suficiente para fundamentar um programa de melhoria da gestão de dados de vários anos, incluindo iniciativas que desenvolverão a capacidade de gestão de dados à medida que a organização adotar as melhores práticas. Como a mudança ocorre em grande parte nas organizações por meio de projetos, novos projetos devem ser influenciados para adotar melhores práticas. O roteiro ou plano de referência deve conter:

* Atividades sequenciadas para efetuar melhorias em funções específicas de gerenciamento de dados
* Um cronograma para a implementação de atividades de melhoria
* Melhorias esperadas nas classificações do DMMA após a implementação das atividades
* Atividades de supervisão, incluindo o amadurecimento dessa supervisão ao longo do cronograma

O roteiro estabelecerá metas e um ritmo para a mudança dentro dos fluxos de trabalho priorizados, acompanhado de uma abordagem para mensurar o progresso.

### 2.5 Reavaliar a Maturidade

As reavaliações devem ser realizadas em intervalos regulares. Elas fazem parte do ciclo de melhoria contínua:

* Estabelecer uma classificação de base até a primeira avaliação
* Definir os parâmetros de reavaliação, incluindo o escopo organizacional
* Repetir a avaliação do DMM conforme necessário em um cronograma publicado
* Acompanhar as tendências em relação à linha de base inicial
* Desenvolver recomendações com base nas conclusões da reavaliação

A reavaliação também pode revigorar ou redirecionar os esforços. O progresso mensurável auxilia na manutenção do comprometimento e do entusiasmo em toda a organização. Mudanças em marcos regulatórios, políticas internas ou externas, ou inovações que possam alterar a abordagem de governança e estratégias são motivos adicionais para reavaliações periódicas.

## 3. Ferramentas

* **Estrutura de Maturidade em Gestão de Dados:** A principal ferramenta utilizada em uma avaliação de maturidade é a própria estrutura do DMM.
* **Plano de Comunicação:** Um plano de comunicação inclui um modelo de engajamento para as partes interessadas, o tipo de informação a ser compartilhada e o cronograma para o compartilhamento de informações.
* **Ferramentas de Colaboração:** As ferramentas de colaboração permitem o compartilhamento dos resultados da avaliação. Além disso, evidências de práticas de gestão de dados podem ser encontradas em e-mails, modelos preenchidos e documentos de revisão criados por meio de processos padrão para design colaborativo, operações, rastreamento de incidentes, revisões e aprovações.
* **Gestão do Conhecimento e Repositórios de Metadados:** Padrões de dados, políticas, métodos, agendas, atas de reuniões ou decisões e artefatos técnicos e de negócios que servem como prova de prática podem ser gerenciados nesses repositórios. Em alguns CMMs, a falta desses repositórios é um indicador de menor maturidade na organização. Repositórios de metadados podem existir em diversas construções, o que pode não ser óbvio para os participantes. Por exemplo, alguns aplicativos de Business Intelligence dependem completamente de metadados para compilar suas visualizações e relatórios, sem se referir a eles como um repositório distinto e separado.

## 4. Técnicas

Muitas técnicas relacionadas à execução de um DMMA são definidas pela metodologia da estrutura DMM escolhida. Técnicas mais gerais são descritas aqui.

### 4.1 Selecionando uma Estrutura DMM

Os seguintes critérios devem ser considerados ao selecionar uma estrutura DMM.

* **Acessibilidade:** As práticas são apresentadas em termos não técnicos que transmitem a essência funcional da atividade.
* **Abrangente:** A estrutura aborda um amplo escopo de atividades de gerenciamento de dados e inclui o engajamento do negócio, não apenas os processos de TI.
* **Extensível e flexível:** O modelo é estruturado para permitir o aprimoramento de disciplinas específicas do setor ou adicionais, e pode ser usado no todo ou em parte, dependendo das necessidades da organização.
* **Caminho de progresso futuro integrado:** Embora as prioridades específicas variem de organização para organização, a estrutura DMM descreve um caminho lógico a seguir dentro de cada uma das funções que descreve.
* **Agnóstico em relação ao setor vs. específico do setor:** Algumas organizações se beneficiarão de uma abordagem específica do setor, outras de uma estrutura mais genérica. Qualquer estrutura DMM também deve aderir às melhores práticas de gerenciamento de dados que abrangem setores verticais.
* **Nível de abstração ou detalhamento:** As práticas e os critérios de avaliação são expressos com um nível de detalhamento suficiente para garantir que possam ser relacionados à organização e ao trabalho que ela realiza.
* **Não prescritivo:** A estrutura descreve o que precisa ser executado, não como deve ser executado.
* **Organizado por tópico:** A estrutura coloca as atividades de gerenciamento de dados em seu contexto apropriado, permitindo que cada uma seja avaliada separadamente, reconhecendo as dependências.
* **Repetível:** A estrutura pode ser interpretada de forma consistente, permitindo resultados repetíveis para comparar uma organização com outras em seu setor e acompanhar o progresso ao longo do tempo.
* **Suportado por uma organização neutra e independente:** O modelo deve ser neutro em relação a fornecedores, a fim de evitar conflitos de interesse, e amplamente disponível para garantir uma ampla representação das melhores práticas.
* **Neutro em relação à tecnologia:** O foco do modelo deve ser nas práticas, e não nas ferramentas.
* **Suporte de treinamento incluído:** O modelo é apoiado por treinamento abrangente para permitir que os profissionais dominem a estrutura e otimizem seu uso.

### 4.2 Uso da Estrutura DAMA-DMBOK

A DAMA-DMBOK pode ser usada para preparar ou estabelecer critérios para uma DMMA. Os responsáveis ​​pela execução verão uma ligação direta entre funções segmentadas (as Áreas de Conhecimento) e as tarefas correspondentes (atividades).

As Áreas de Conhecimento, atividades e entregas (produtos de trabalho) da DMBOK podem ser configuradas para uma estrutura DMM específica com base nas áreas medidas, suas atividades de suporte, relevância e tempo disponível. Essa abordagem rápida e baseada em lista de verificação pode ser usada para determinar áreas que precisam de uma análise mais aprofundada, representam lacunas ou apontam pontos críticos para correção.

A DMBOK oferece uma vantagem adicional como ferramenta de planejamento de avaliação: há uma grande comunidade de profissionais do conhecimento que a utilizam como guia em diversos setores, criando uma comunidade de práticas em torno de seu uso.

## 5. Diretrizes para uma DMMA

### 5.1 Avaliação de Prontidão / Avaliação de Risco

Antes de realizar uma avaliação de maturidade, é útil identificar os riscos potenciais e algumas estratégias de mitigação de riscos. A Tabela 33 resume os riscos e as abordagens de mitigação.

Tabela 33 Riscos e Mitigações Típicos para uma DMMA

<table>
  <thead>
    <tr>
      <th>Risco</th>
      <th colspan="2">Mitigação</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        Falta de adesão organizacional
      </td>
      <td>
        Socialize os conceitos relacionados à avaliação. Estabeleça declarações de benefícios antes de conduzir a avaliação. Compartilhe artigos e histórias de sucesso. Contrate um patrocinador executivo para apoiar o esforço e revisar os resultados.
      </td>
    </tr>
    <tr>
      <td>
        Falta de experiência em DMMA, Falta de tempo ou experiência interna, Falta de planejamento ou padrões de comunicação
      </td>
      <td>
        Use recursos ou especialistas de terceiros. Exija transferência de conhecimento e treinamento como parte do engajamento.
      </td>
    </tr>
    <tr>
      <td>
        Falta de "linguagem de dados" na organização; conversas sobre dados rapidamente se transformam em discussões sobre sistemas
      </td>
      <td>
        Relacione o DMMA a problemas ou cenários de negócios específicos. Aborde no plano de comunicação. O DMMA educará todos os participantes, independentemente de sua formação e experiência técnica. Oriente os participantes sobre os principais conceitos antes do DMMA.
      </td>
    </tr>
    <tr>
      <td>
        Ativos incompletos ou desatualizados para análise
      </td>
      <td>
        Marque "a partir de" ou equilibre a classificação de acordo. Por exemplo, dê -1 a tudo que estiver desatualizado há mais de 1 ano.
      </td>
    </tr>
    <tr>
      <td>
        Foco restrito
      </td>
      <td>
        Reduza a profundidade da investigação a um simples DMMA e vá para outras áreas para uma avaliação rápida a fim de estabelecer classificações para uma linha de base comparativa posterior. Conduza o primeiro DMMA como piloto e, em seguida, aplique as lições aprendidas para abordar um escopo mais amplo. Apresente o foco dentro do escopo da avaliação proposta no contexto das Áreas de Conhecimento DAMA-DMBOK. Ilustre o que está sendo deixado de fora do escopo e discuta a necessidade de inclusão.
      </td>
    </tr>
    <tr>
      <td>
        Equipe ou sistemas inacessíveis
      </td>
      <td>
        Reduza o escopo horizontal do DMMA, concentrando-se apenas nas Áreas de Conhecimento e na equipe disponíveis
      </td>
    </tr>
    <tr>
      <td>
        Surpresas surgem, como mudanças na regulamentação
      </td>
      <td>
        Adicione flexibilidade ao fluxo de trabalho de avaliação e ao foco.
      </td>
    </tr>
  </tbody>
</table>

### 5.2 Mudança Organizacional e Cultural

Estabelecer ou aprimorar um programa de Gestão de Dados inclui mudanças em processos, métodos e ferramentas. Com essas mudanças, a cultura também precisa mudar. A transformação organizacional e cultural começa com o reconhecimento de que as coisas podem ser melhores. Funções de mensuração normalmente inauguram mudanças significativas. O DMMA situa a organização em uma escala de maturidade e fornece um roteiro para melhorias. Dessa forma, pode direcionar a organização para o futuro em meio à mudança. Os resultados do DMMA devem fazer parte de uma discussão mais ampla dentro da organização. Quando devidamente apoiados por uma governança de dados eficaz, os resultados do DMMA podem unir diferentes perspectivas, resultar em uma visão compartilhada e acelerar o progresso da organização. (Consulte o Capítulo 17.)

## 6. Governança da Gestão da Maturidade

Normalmente, um DMMA faz parte de um conjunto geral de atividades de governança de dados, cada uma com um ciclo de vida. O ciclo de vida de um DMMA consiste no planejamento e na avaliação iniciais, seguidos por recomendações, um plano de ação e reavaliações periódicas. O próprio ciclo de vida deve ser governado.

### 6.1 Supervisão do Processo DMMA

A supervisão do processo DMMA cabe à equipe de Governança de Dados. Se a Governança de Dados formal não estiver implementada, a supervisão recai, por padrão, sobre o comitê diretor ou a camada de gestão que iniciou o DMMA. O processo deve ter um patrocinador executivo, idealmente o CDO, para garantir que as melhorias nas atividades de gerenciamento de dados estejam diretamente relacionadas aos objetivos de negócios.

A amplitude e a profundidade da supervisão dependem do escopo do DMMA. Cada função envolvida no processo tem voz ativa na execução, no método, nos resultados e nos roteiros decorrentes da avaliação geral. Cada área de gerenciamento de dados e função organizacional envolvida terá uma visão independente, mas também terá uma linguagem comum por meio da estrutura do DMM.

### 6.2 Métricas

Além de serem um componente central de qualquer estratégia de melhoria, as métricas são uma ferramenta de comunicação fundamental. As métricas iniciais do DMMA são as classificações que representam o estado atual do gerenciamento de dados. Elas podem ser reavaliadas periodicamente para mostrar tendências de melhoria. Cada organização deve desenvolver métricas adaptadas ao seu roteiro de estado-alvo. Exemplos de métricas podem incluir:

* **Classificações DMMA:** As classificações DMMA apresentam uma visão geral do nível de capacidade da organização. As classificações podem ser acompanhadas por uma descrição, talvez uma ponderação personalizada para a classificação em uma avaliação ou área temática específica, e um estado-alvo recomendado.
* **Taxas de utilização de recursos:** Exemplos poderosos de métricas que ajudam a expressar o custo do gerenciamento de dados na forma de número de funcionários. Um exemplo desse tipo de métrica é: "Cada recurso na organização gasta 10% do seu tempo agregando dados manualmente."
* **Exposição a riscos** ou a capacidade de responder a cenários de risco expressa as capacidades de uma organização em relação às suas classificações DMMA. Por exemplo, se uma organização quisesse iniciar um novo negócio que exigisse um alto nível de automação, mas seu modelo operacional atual fosse baseado no gerenciamento manual de dados (Nível 1), ela correria o risco de não entregar.
* **Gerenciamento de gastos** expressa como o custo do gerenciamento de dados é alocado em uma organização e identifica os impactos desse custo na sustentabilidade e no valor. Essas métricas se sobrepõem às métricas de governança de dados.
  * Sustentabilidade da gestão de dados
  * Atingimento das metas e objetivos da iniciativa
  * Eficácia da comunicação
  * Eficácia da educação e do treinamento
  * Velocidade de adoção de mudanças
  * Valor da gestão de dados
  * Contribuições para os objetivos de negócios
  * Redução de riscos
  * Maior eficiência nas operações
* As entradas para o DMMA são importantes para o gerenciamento, pois refletem a abrangência da cobertura, o nível de investigação e os detalhes do escopo relevantes para a interpretação dos resultados da pontuação. As entradas principais podem incluir o seguinte: contagem, cobertura, disponibilidade, número de sistemas, volumes de dados, equipes envolvidas, etc.
* Taxa de Mudança: a taxa na qual uma organização está aprimorando sua capacidade. Uma linha de base é estabelecida por meio do DMMA. Reavaliações periódicas são usadas para monitorar a tendência de melhoria.

## 7. Trabalhos Citados / Recomendados

Afflerbach, Peter. Essential Readings on Assessment. International Reading Association, 2010. Print.

Baskarada, Sasa. IQM-CMM: Information Quality Management Capability Maturity Model. Vieweg+Teubner Verlag, 2009. Print. Ausgezeichnete Arbeiten zur Informationsqualität.

Boutros, Tristan and Tim Purdie. The Process Improvement Handbook: A Blueprint for Managing Change and Increasing Organizational Performance. McGraw-Hill Education, 2013. Print.

CMMI Institute (website). http://bit.ly/1Vev9xx.

Crawford, J. Kent. Project Management Maturity Model. 3rd ed. Auerbach Publications, 2014. Print. PM Solutions Research.

Enterprise Data Management Council (website).

Freund, Jack and Jack Jones. Measuring and Managing Information Risk: A FAIR Approach. Butterworth-Heinemann, 2014. Print.

Ghavami, Peter PhD. Big Data Governance: Modern Data Management Principles for Hadoop, NoSQL and Big Data Analytics. CreateSpace Independent Publishing Platform, 2015. Print.

Honeysett, Sarah. Limited Capability - The Assessment Phase. Amazon Digital Services LLC., 2013. Social Insecurity Book 3.

IBM Data Governance Council. https://ibm.co/2sUKIng.

Jeff Gorball, Introduction to Data Management Maturity Models. SlideShare.net, 2016-08-01. http://bit.ly/2tsIOqR.

Marchewka, Jack T. Information Technology Project Management: Providing Measurable Organizational Value. 5th ed. Wiley, 2016. Print.

McSweeney, Alan. Review of Data Management Maturity Models. SlideShare.net, 2013-10-23. http://bit.ly/2spTCY9.

Persse, James R. Implementing the Capability Maturity Model. Wiley, 2001.Print.

Saaksvuori, Antti. Product Management Maturity Assessment Framework. Sirrus Publishing Ltd., 2015. Print.

Select Business Solutions. “What is the Capability Maturity Model?” http://bit.ly/IFMJI8 (Accessed 2016-11-10).

Stanford University. Stanford Data Governance Maturity Model. http://stanford.io/2ttOMrF.

Van Haren Publishing. IT Capability Maturity Framework IT-CMF. Van Haren Pub, 2015. Print.

[^96]: Adaptado de Select Business Solutions, “O que é o Modelo de Maturidade de Capabilidade?” http://bit.ly/IFMJI8 (Acessado em 10/11/2016).
[^97]: http://bit.ly/1Vev9xx 18 de julho de 2015.
[^98]: Para obter informações adicionais e uma análise dos CMMs de Gerenciamento de Dados existentes, consulte: Alan McSweeney, Review of Data Management Maturity Models, SlideShare.net, publicado em 23/10/2013. http://bit.ly/2spTCY9. Jeff Gorball, Introduction to Data Management Maturity Models, SlideShare.net, publicado em 1º de agosto de 2016. McSweeney inclui o DAMA-DMBOK como um de seus modelos de maturidade, embora o DMBOK não seja estruturado como tal.
[^99]: http://bit.ly/1Vev9xx acessado em 18/07/2015
[^100]: http://bit.ly/2sqaSga acessado em 18/07/2015
[^101]: https://ibm.co/2sRfBIn (acessado em 04/12/2016)
[^102]: http://stanford.io/2sBR5bZ (acessado em 04/12/2016) e http://stanford.io/2rVPyM2 (acessado em 04/12/2016).
