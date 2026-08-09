### Perfis de Usuário
1. Objetivo

Definir os perfis de usuários do Inventário App e suas respectivas responsabilidades e permissões dentro do sistema.

2. Perfis
2.1 Administrador

Responsabilidade: Gerenciar o sistema e seus usuários.

Permissões:

Acessar o sistema;
Cadastrar usuários;
Editar usuários;
Inativar usuários;
Cadastrar produtos;
Editar produtos;
Inativar produtos;
Consultar produtos;
Realizar inventários;
Registrar entradas e saídas;
Consultar histórico;
Gerar relatórios;
Exportar dados;
Acessar o dashboard.

2.2 Estoquista

Responsabilidade: Controlar o estoque e realizar inventários.

Permissões:

Acessar o sistema;
Consultar produtos;
Cadastrar produtos;
Editar produtos;
Realizar inventários;
Ler códigos de barras;
Registrar entradas;
Registrar saídas;
Consultar histórico;
Gerar relatórios;
Exportar dados;
Acessar o dashboard.

2.3 Operador

Responsabilidade: Registrar as movimentações de estoque.

Permissões:

Acessar o sistema;
Consultar produtos;
Ler códigos de barras;
Registrar entradas;
Registrar saídas;
Consultar suas movimentações;
Visualizar informações básicas do estoque.

Restrições:

Não pode cadastrar usuários;
Não pode excluir/inativar produtos;
Não pode alterar configurações do sistema.
2.4 Gestor

Responsabilidade: Acompanhar os indicadores e informações estratégicas do estoque.

Permissões:

Acessar o dashboard;
Consultar produtos;
Consultar estoque;
Consultar histórico;
Gerar relatórios;
Exportar relatórios para Excel/PDF.

Restrições:

Não realiza movimentações;
Não cadastra usuários;
Não altera produtos.

## 3. Matriz de Permissões

| Funcionalidade | Administrador | Estoquista | Operador | Gestor |
|---|:---:|:---:|:---:|:---:|
| Login | ✅ | ✅ | ✅ | ✅ |
| Gerenciar usuários | ✅ | ❌ | ❌ | ❌ |
| Cadastrar produto | ✅ | ✅ | ❌ | ❌ |
| Editar produto | ✅ | ✅ | ❌ | ❌ |
| Inativar produto | ✅ | ❌ | ❌ | ❌ |
| Consultar produtos | ✅ | ✅ | ✅ | ✅ |
| Ler código de barras | ✅ | ✅ | ✅ | ❌ |
| Realizar inventário | ✅ | ✅ | ❌ | ❌ |
| Entrada de estoque | ✅ | ✅ | ✅ | ❌ |
| Saída de estoque | ✅ | ✅ | ✅ | ❌ |
| Consultar histórico | ✅ | ✅ | ✅* | ✅ |
| Dashboard | ✅ | ✅ | ✅ | ✅ |
| Gerar relatórios | ✅ | ✅ | ❌ | ✅ |
| Exportar dados | ✅ | ✅ | ❌ | ✅ |

\* O Operador poderá consultar apenas as movimentações permitidas pelo seu perfil.
