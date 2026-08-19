# Agro Resource Manager (ARM)

Sistema web interno para gerenciamento de recursos e funcionários de uma propriedade rural.

## Sobre o Projeto

O **Agro Resource Manager (ARM)** foi desenvolvido para auxiliar no controle e na organização dos recursos utilizados na **Fazenda Boa Colheita**, uma organização fictícia.

O sistema tem como objetivo centralizar informações sobre funcionários e recursos agrícolas, permitindo que o administrador controle quais recursos estão disponíveis e quais estão vinculados a cada funcionário.

### Exemplo de utilização

O administrador pode cadastrar o funcionário **Carlos Almeida** e o **Trator 01**. Em seguida, pode realizar a vinculação:

**Trator 01 → Carlos Almeida**

Quando Carlos acessar seu usuário no sistema, poderá visualizar o recurso que está sob sua responsabilidade.

## Funcionalidades

### Administrador

* Realizar login;
* Cadastrar funcionários;
* Editar funcionários;
* Desativar funcionários;
* Cadastrar recursos agrícolas;
* Editar recursos;
* Desativar recursos;
* Vincular recursos aos funcionários;
* Alterar responsáveis pelos recursos;
* Remover vínculos;
* Consultar histórico de utilização;
* Visualizar dashboard;
* Consultar relatórios.

### Funcionário

* Realizar login;
* Visualizar recursos vinculados;
* Consultar informações dos recursos;
* Registrar início de utilização;
* Registrar término de utilização;
* Consultar histórico de utilização.

### Gerente

* Realizar login;
* Visualizar o dashboard;
* Consultar funcionários;
* Consultar recursos;
* Consultar vínculos;
* Consultar histórico;
* Visualizar relatórios.

## Escopo Inicial

O projeto será desenvolvido como um **sistema web interno**, voltado para uma única fazenda.

Nesta primeira versão, o sistema não utilizará APIs externas, sensores físicos, GPS ou inteligência artificial.

Os dados serão armazenados em um **banco de dados PostgreSQL local**.

## Tecnologias

| Categoria          | Tecnologia               |
| ------------------ | ------------------------ |
| Back-end           | Java 21                  |
| Framework          | Spring Boot              |
| Persistência       | Spring Data JPA          |
| Banco de Dados     | PostgreSQL               |
| Front-end          | HTML5, CSS3 e JavaScript |
| Interface          | Bootstrap                |
| Dependências       | Maven                    |
| Controle de Versão | Git                      |
| Repositório        | GitHub                   |
| IDE                | IntelliJ IDEA            |

## Estrutura Principal do Sistema

O projeto terá como principais conceitos:

* **Usuário:** responsável pelo acesso ao sistema;
* **Funcionário:** pessoa cadastrada e vinculada aos recursos;
* **Recurso:** máquina ou equipamento da fazenda;
* **Vínculo:** relacionamento entre funcionário e recurso;
* **Histórico:** registro das utilizações dos recursos.

## Objetivo

Desenvolver uma solução simples e organizada para facilitar o gerenciamento dos recursos agrícolas e permitir que a fazenda tenha maior controle sobre a distribuição e utilização de seus equipamentos.




