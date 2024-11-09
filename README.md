# Uso do Hibernate

### Introdução ao Hibernate
- O que é Hibernate e ORM (Object-Relational Mapping) 
- Benefícios e limitações do Hibernate 
- Comparação com JDBC e vantagens do uso do Hibernate
  
### Configuração do Hibenate
- Estrutura de um projeto com Hibernate
- Configuração usando o arquivo hibernate.cfg.xml
- Configuração com persistence.xml (para uso com JPA)
- Propriedades principais (dialeto, pool de conexões, cache)
  
### Mapeamento de entidades e anotações
- Como mapear classes Java para tabelas no banco de dados
- Anotações essenciais: @Entity, @Table, @Id, @GeneratedValue, @Column
- Estratégias de geração de ID (Auto, Sequence, Identity)
  
### Mapeamento de relacionamento entre entidades
- Tipos de relacionamentos (One-to-One, One-to-Many, Many-to-One, Many-to-Many)
- Anotações de relacionamento: @OneToOne, @OneToMany, @ManyToOne, @ManyToMany
- Cascade e FetchType (Lazy vs. Eager Loading)
- Configuração de chave estrangeira e propriedades de união (joinColumns)

### Herança e Polimorfismo
- Estratégias de mapeamento de herança (SINGLE_TABLE, JOINED, TABLE_PER_CLASS)
- Como usar anotações como @Inheritance, @DiscriminatorColumn, @DiscriminatorValue

### Operações CRUD com Hibernate
- Inserção, atualização, exclusão e busca de dados no banco
- Métodos da API Session (save, update, delete, get, load)
- Diferenciação entre Session e EntityManager
  
### Consultas com Hibernate
- Linguagem de consulta do Hibernate (HQL - Hibernate Query Language)
- Consultas com Criteria API (para consultas dinâmicas)
- Uso de Native SQL Queries e Named Queries

### Gerenciamento de Transações
### Cache no Hibernate
### Validação de Dados
### Otimização de Desempenho
### Integração com o Spring Framework
###  Ferramentas e Práticas de Depuração



