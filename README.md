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
- Conceito de transação e seu controle no Hibernate
- Uso de transações com @Transactional (Spring) e controle explícito

### Cache no Hibernate
- Integração com Bean Validation (JSR-303)
- Validações comuns: @NotNull, @Size, @Pattern
  
### Validação de Dados
- Estratégias de fetching: lazy e eager loading
- Redução de consultas N+1
- Uso de índices no banco de dados e otimização de consultas
  
### Otimização de Desempenho
- Configuração do Hibernate com Spring Boot e Spring Data JPA
- Anotações @Repository e @Transactional
- Uso de Spring Data JPA para simplificar o acesso ao banco
  
### Integração com o Spring Framework
###  Ferramentas e Práticas de Depuração



