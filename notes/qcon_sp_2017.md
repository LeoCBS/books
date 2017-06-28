# QCon SP 2017


## [Infraestrutura de dados no Nubank: Criando um ferramental para promover uma cultura data-driven](http://qconsp.com/system/files/presentation-slides/alessandro_andrioni_e_andre_midea_-_qcon_2017.pdf)

* Criar contratos que descrevem os dados em produção
* Contratos matem a descrição dos dados atualizados
* Contratos facilitam a criação de modelos
* Contrato devem ser testados e automatizados
* Bancos temporais ajudam a recuperar estado em um timeset
* Spark
* Kafka

## [Microservices e workflows distribuídos: tornando dados acessíveis na 99](http://qconsp.com/system/files/presentation-slides/qconsp_-_airflow_-_gustavo_amigo.pdf)

* Utilizar o airflow para agregar informacoes e fluxos
* Airflow executa tasks para agregar informações
* Estas informacoes ficam disponiveis os demais setores da empresa (Contabilidade)
* Integração dessas informacoes com slack bot - facil interface com o consumidor das informações
* [Metabase](http://www.metabase.com/) para facilitar a buscar de dados


## [Evolução cultural de desenvolvedores a equipes: criando times de alto desempenho no Elo7](http://qconsp.com/system/files/presentation-slides/david.robert.qcon_2017_-_evolucao_cultural_-_desenvolvendo_times_de_alta_performance.pdf)

* Times especialistas - precisa de mais colaboração entre equipes
* Ambiente colaborativo.. não tem entrega individual.. todos envolvidos na feature tem responsabilidades..
* Integração do negócio com o dev.. (mostrar quando a empresa vendeu por semana)
* O dev também é responsável pelo produto - produção diária.. caiu? Porque? Mostrar a produção mensal para motivar
* pareamento de monitores
* autonomia .. confiança nas pessoas

## [Autorização de transações no Nubank: Consumindo serviços anos 80 com tecnologias atuais](http://qconsp.com/system/files/presentation-slides/lucas_e_luiz.qcon-authorizer-nubank.pdf)

* [Datomic](http://www.datomic.com/)
* [Finagle](https://github.com/twitter/finagle)
* Atom banco de dados em memoria



## [Autorização de transações no Nubank: Consumindo serviços anos 80 com tecnologias atuais](http://qconsp.com/system/files/presentation-slides/diego.paris_.o_lider_agil.pptx.pptx)

* todos são responsáveis.. o que vc fez para mudar a equipe?
* atacar a raiz do problema
* círculo de segurança - piramede de Maslow
* não ter medo de gerar feature - bugs
* pensar no coletivo
* valorização confiança cooperação
* líder por exemplo
* saber oq motiva o time e as pessoas?
* moving motivators cards
* coaching - nao dar a resposta do problema.. fazer perguntas pra fazer entender o problema
* mentoring - acompanhar a carreira
* cooperação - visão do futuro.. envolver as pessoas nas missões dá empresa
* confiança - feedback


## [Actors Unleashed: Reactive Systems, DDD, and the Ubiquitous Language](http://qconsp.com/system/files/presentation-slides/usingactormodeldddreactive_vaughnvernon.pdf)

* não fazer otimizações prematuras
* pensar em threads como mensagens. Message drive
* erlarg , elixir
* actor modelos
* reactive é resiliente
* iot - embrace latency
* fazer mais com menos - procurar linguagens não tradicionais.. para ter mais performance.. fazer de modo diferente
* Lock Free.. não compartilhe estado
* transações adicionam complexidade
* actor models facilitam transações.. eventos são atomicos
* DDD linguagens ubliquoas
* Akka
* saber trabalhar com a incerteza

## The Realist’s Guide to Language Design

* Não tem linguagem perfeita
* Deve evitar cometer erros
* Dem ambiguidade.. mesma entrada mesmo valor sempre
* Sintaxe intuitiva.. não pensar muito como faz um IF..
* Footprint razoável
* Abstração demais é ruim.. array..Lista vector..map.. collection
* Eficiência
* [lazy Evaluation](https://en.wikipedia.org/wiki/Lazy_evaluation)
- Tooling
- Boa comunidade
- [Idris Lang] (https://www.idris-lang.org/)

## [Criptografia aplicada: de algoritmos a bibliotecas](http://qconsp.com/system/files/presentation-slides/bruno.applied-cryptography-qconsp2017.pdf)

* Autenticidade
* Confiabilidade
* Integridade
* Hash não garante integridade.. jah tem colisão
* ECB é ruim para criptografia
* GCM
* RSA
* Key agrement

## [Microservices reativos e a experiência do iFood](http://qconsp.com/system/files/presentation-slides/tiago.dolphine.qcon_sp_2017_-_reactive_microservices.pdf)

* manifesto reativo
* não blocar as operações.. o DB avisa quando acabou a operação e ediciona informações as mensagens
* stream reativo
* reactor java
* Spring

## [Resiliência com microservices: cache distribuído, feedback e tuning na Globo.com](http://qconsp.com/system/files/presentation-slides/resiliencia_em_microservices.pdf)

* [cachet status pages](https://github.com/CachetHQ/Cachet)
* Backstage apis com tenants
* Buffer em memória fazendo flush de tempos em tempos - votação BBB
* Load balance


## [Failing Gracefully with the Actor Model](http://qconsp.com/system/files/presentation-slides/roger.failingactors.pptx)

* Não devolver o error direto para o usuário.. remanejar o erro pra quem pode corrigi-lo - erros supervisionados
* Circuit break
* fanout and quickest replay
* active passive consume
* modular redundancy
* throttling to lead with load
* bounded mailboxes
* work pulling - blackpressure
* orbit framework - virtual actor

## From laptop to the world: multi-region container deployment with Kubernetes

* Definir o ambiente de produção desde o começo do projeto.. pensar em como será pelo menos
* Env de desenvolvimento deve ser mais próximo possível de prod.. para evitar configurações diferentes
* Containers
* /static
* delete pod do k8s cria outro pod até q fique igual ao número do scale
* Type loadbalancer
* Dederativo service.. vários clusters de kubernetes
* [Saturnism](https://github.com/saturnism)

## [Processamento de Linguagem Natural com Deep Learning](http://qconsp.com/system/files/presentation-slides/juliano.viana_.kunumi_processamento-linguagem-natural-deep-learning-v3.pdf)

* word2vec
* vdb
* recurrent network
* long short term memory
* detectar se a frase eh autêntica
* música neural sabotagem
* sequence prediction
* seq2seq
* chatbot .. converter perguntas em consultas SQL
* cutting Edge models

## [Billions and Billions](http://qconsp.com/system/files/presentation-slides/jim.qcon_fighting_fraud_with_graphs.pptx)

## [How Apache Beam will change Big Data](http://qconsp.com/system/files/presentation-slides/jesse.beam_intro.pdf)

* Tenta encapsular várias tecnologias.. Kafka.. hadoop
* Uma unica API
* Unifica diferentes API - Kafka se comunica com spark stream

## [IoT e Smart Energy: monitoramento de instalações elétricas através do auto-registro de dispositivos](http://qconsp.com/system/files/presentation-slides/caio.cesar_.uiot-smart-energy.pdf)

- Rede de dispositivos para ajudar a tomada de decisão
- Auto registro do dispositivo
- Tratar comportamento do dispositivo - validar o comportamento
- Couch DB
- Manutenção preventiva consumo de energia
