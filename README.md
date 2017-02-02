# projeto-jpa-2

Conteúdo Detalhado

Mapeando relacionamentos Muitos-para-Muitos
Requisitos do treinamento
Conhecendo os relacionamentos
Relacionamento muitos-para-muitos
Representando esse relacionamento no banco de dados
O que aprendemos
Consultas dinâmicas com Criteria API
O velho problema da concatenação de Strings
Montando a consulta dinâmicas
Usando Predicates
Adicionando mais filtros à consulta
O que aprendemos
O comportamento Lazy e OpenEntityManagerInView
Editando produtos
Entendendo comportamento preguiçoso
Ciclo da vida do EntityManager
O padrão OpenEntityManagerInView
Configurando OpenEntityManagerInView com Spring
O que aprendemos
Gerenciando conexões com Pool de conexão
Um EntityManager por requisição?
Muitas ou poucas conexões?
Gerenciando conexões
Isolando os dados de conexão com DataSource
Conhecendo o Pool de conexões
Configurações importante do Pool C3P0
Limitando a quantidade de conexões
O que aprendemos
Evitando conflitos com Lock otimista
Quem chegará primeiro?
O que é Lock pessimista?
Problemas com Lock Pessimista
Resolvendo o problema com Lock Otimista
Usando @Version
Testando o Lock Otimista
O que aprendemos
Melhorando o desempenho com Cache
Pensando em performance
Conhecendo o cache de primeiro nível
Cache para vários EntityManagers?
Conhecendo o cache de segundo nível
Habilitando o EhCache
Usando o cache de segundo nível na aplicação
Cache de Collections
Armazenando a Categoria no cache
Cache de queries
O que aprendemos
Caçando seus gargalos com o Hibernate Statistics
Coletando informações sobre a camada de persistência
Configurando o Hibernate Statistics
Visualizando dados sobre o cache de queries:
Outras estatísticas
