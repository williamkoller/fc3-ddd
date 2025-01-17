# Full Cycle 3.0

## Domain-Driven Design

## O que é DDD?

- É uma forma de desenvolver software com foco no coração da aplicação - o que chamamos
  de domínio - tendo o objetivo de entender regras, processos e complexidades,
  separando-as assim de outros ponmtos complexos que normalmente são adicionados durante o
  processo de desenvolvimento.

## De onde surgiu o DDD?

- Eric evans

- Livro lançado em 2003

  - Filosofia
  - Exemplos reais
  - Patterns

- Comunidade de entusiastas seguindo essa prática

- Lançamento de outros livros

## Softwares Complexos

- DDD é / deve ser aplicado para casos de projetos de softwares complexos

- Grandes projetos possuem mais áreas, muitas regras de negócio, muitos processos
  com diferrentes visões em diferentes contextos

- Não há como não utilizar técnicas avançadas em projetos de alta complexidade

- Grande parte da complexidade desse tipo de software não vem da tecnologia, mas sim da
  comunicação, separação de contextos, entendimento do negócio por viversos ângulos

- Pessoas

## Como o DDD pode ajudar?

- Entender com profundidade o domínio e subdomínios da aplicação

- Ter uma linguagem universal (linguagem ubíqua) entre todos os envolvidos

- Criar o design estratégico utilizando Bounded Contexts

- Criar um design tático para conseguir mapear e agragar as entidades e objetos de valor da
  aplicação, bem como os eventos de domínio

- Clareza do que é complexidade de negócio e complexidade técnica

# Domínio e Subdomínios

<p align="center">
  <a href="">
    <img src="./resources/domain-subdomain.drawio.png">
  </a>
</p>

# Problema vs Solução

<p align="center">
  <a href="">
    <img src="./resources/problema-solucao.drawio.png">
  </a>
</p>

# O que é um contexto delimitado?

- Bounded Contexts

- É uma forma de dividir o domínio em partes menores, delimitando o contexto de cada uma delas.

- Cada Bounded Context é uma parte do domínio que possui sua própria linguagem ubíqua, regras de negócio e processos.

# Contexto é Rei

<p align="center">
  <a href="">
    <img src="./resources/contexto-rei.drawio.png">
  </a>
</p>

# Modelagem estratégica / Context Mapping

<p align="center">
  <a href="">
    <img src="./resources/context-mapping.drawio.png">
  </a>
</p>

# Padrões de Context Mapping

- Partnership
- Shared Kernel
- Customer-Supplier Development
- Conformist
- Anticorruption-layer
- Open host service
- Publish language
- Separate ways
- Big Ball and Mud
- [ddd-crew/context-mapping](https://github.com/ddd-crew/context-mapping)
