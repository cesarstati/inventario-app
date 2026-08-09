# Levantamento de Requisitos
## Objetivo

Levantar, analisar e documentar os requisitos do sistema de inventário com leitor de código de barras, definindo claramente as funcionalidades, regras de negócio e estrutura inicial do projeto.

### 1. Problema

Atualmente o controle de estoque é realizado de forma manual ou em planilhas, tornando o processo de inventário lento, sujeito a erros e difícil de rastrear.

O sistema deverá permitir a leitura de códigos de barras utilizando a câmera do celular ou um leitor USB, agilizando a conferência dos itens e registrando automaticamente as movimentações.

### 2. Objetivos do Sistema

O sistema deverá permitir:

- cadastrar produtos;
- localizar produtos rapidamente;
- realizar inventários;
- registrar entradas e saídas;
- controlar quantidades;
- emitir relatórios;
- utilizar leitor de código de barras;
- funcionar em computadores e celulares.
- consultar histórico de movimentações;
- identificar produtos com estoque baixo;
- controlar estoque mínimo.

### 3. Stakeholders

| Stakeholder | Responsabilidade Principal | Nível de Acesso | Frequência de Uso |
| :--- | :--- | :---: | :--- |
| **Administrador** | Gerencia o sistema e usuários | Total | Diário / Sempre |
| **Estoquista** | Faz inventários e auditorias | Estoque | Semanal / Mensal |
| **Operador** | Registra entradas e saídas de produtos | Operacional | Contínuo (Turnos) |
| **Gestor** | Utiliza os relatórios estratégicos | Relatórios | Sob Demanda |


### 4. Requisitos Funcionais
RF01: Cadastrar produto.

RF02: Editar produto.

RF03: Excluir produto.

RF04: Pesquisar produto.

RF05: Listar produtos.

RF06: Ler código de barras utilizando câmera.

RF07: Ler código de barras utilizando leitor USB.

RF08: Realizar inventário.

RF09: Registrar entrada de estoque.

RF10: Registrar saída de estoque.

RF11: Atualizar quantidade automaticamente.

RF12: Consultar histórico de movimentações.

RF13: Gerar relatório de inventário.

RF14: Exportar relatório para Excel.

RF15: Exportar relatório para PDF.

### 5. Requisitos Não Funcionais
RNF01: O sistema deve possuir interface responsiva, adaptando-se a computadores, tablets e celulares.

RNF02: A interface deve ser simples e intuitiva.

RNF03: As operações comuns do sistema devem apresentar tempo de resposta inferior a 2 segundos em condições normais de uso.

RNF04: O sistema deve ser compatível com versões atuais dos navegadores Google Chrome, Microsoft Edge e Mozilla Firefox.

RNF05: O sistema deve utilizar um banco de dados relacional como fonte principal e oficial dos dados do sistema.

RNF06: A comunicação entre frontend e backend deve utilizar API REST.

RNF07: O código-fonte deve ser versionado utilizando Git e hospedado no GitHub.

RNF08: O sistema deve utilizar arquitetura em camadas, separando as responsabilidades da aplicação.

RNF09: A API deve possuir documentação utilizando Swagger/OpenAPI.

RNF10: O sistema deve estar preparado para implantação em ambiente de nuvem.

RNF11: O sistema deve permitir integração com o Google Sheets para importação e/ou exportação de dados, sem utilizar a planilha como banco de dados principal.

