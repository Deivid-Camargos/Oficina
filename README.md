# Sistema de Oficina Mecânica

Sistema de gestão para oficinas mecânicas, desenvolvido em **Java** com **Maven**, organizado no padrão **MVC**.

> 🚧 Projeto em desenvolvimento: no momento contém a modelagem inicial das classes e a estrutura de pacotes.

## Funcionalidades previstas

- Cadastro de clientes e veículos
- Abertura e acompanhamento de ordens de serviço
- Controle de estoque de peças
- Agendamento de serviços e uso dos elevadores
- Controle de acesso por perfil (administrador, atendente e mecânico)
- Gerenciamento financeiro e relatórios

## Estrutura

```
src/main/java/com/deividcamargos/sistemaoficina/
├── MODEL/        # Entidades: Cliente, Veiculo, OrdemServico, Peca, Usuario...
├── Controller/   # Regras de negócio: acesso, estoque e agendamentos
└── SistemaOficina.java
```

A hierarquia de usuários usa herança: `Administrador`, `Atendente`, `Mecanico` e `Cliente` estendem `Usuario`.

## Tecnologias

- Java 24
- Maven
- NetBeans

## Como executar

```bash
mvn compile exec:java
```

## Autor

**Deivid Camargos Batista** · [LinkedIn](https://www.linkedin.com/in/deivid-camargos-batista)
