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


