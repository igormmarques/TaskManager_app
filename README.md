# Task Manager

## Propósito do Sistema

O Task Manager é uma aplicação web destinada à gestão de tarefas, onde os usuários podem criar, editar, excluir e visualizar tarefas. O sistema oferece funcionalidades simples, porém eficientes, para o controle do status das tarefas (como "Pendente", "Em Progresso" e "Concluída"). Ele visa proporcionar uma interface intuitiva para que os usuários possam organizar suas atividades de forma prática.

## Tecnologias Usadas

### Back-End
- **ASP.NET Core 6**: Framework robusto para construção da API RESTful.
- **Entity Framework Core**: Para o mapeamento objeto-relacional (ORM), facilitando a comunicação com o banco de dados.
- **SQL Server**: Banco de dados utilizado para armazenamento das informações das tarefas.
- **MatSnackBar (Material UI)**: Biblioteca para exibição de notificações no front-end.
- **C#**: Linguagem de programação utilizada no desenvolvimento da API.

### Front-End
- **Angular 14**: Framework de front-end utilizado para a criação da interface interativa.
- **HTML, CSS e Bootstrap**: Usados para construção e estilo da interface do usuário.
- **Router (Angular)**: Para navegação entre as páginas da aplicação (lista de tarefas, criação/edição de tarefas).
- **Angular Forms**: Para gerenciamento de formulários, incluindo validações e envio de dados para a API.

## Como Instalar e Usar

### Requisitos:
- .NET SDK 6 ou superior
- Node.js (para rodar o front-end Angular)
- SQL Server (ou outro banco de dados configurado)

### 1. Clonando o Repositório
```
git clone https://github.com/seu-usuario/task-manager.git
cd task-manager
```
### 2. Configuração do Back-End (API)
```
Navegue até a pasta do back-end (Backend/TaskManagerApi).
Restaure as dependências do projeto:
```
### 3. Configurando o Front-End
```
Navegue até a pasta do front-end
npm install
ng serve
```
### 4. Configurando o Banco de Dados
```
Certifique-se de que o SQL Server esteja em execução. Ajuste as configurações de conexão no arquivo appsettings.json no back-end.
```

### Melhorias e Próximas Features
## Pontos de Melhoria
Animações: Animações foram desativadas devido a erros de configuração no Angular Material. Pretende-se corrigir e reativar esse recurso para melhorar a experiência do usuário.
Responsividade: Aperfeiçoar o layout para dispositivos móveis e telas menores.

## Próximas Features
Autenticação: Adicionar suporte a JWT para autenticação e controle de acesso.
Filtros Avançados: Incluir filtros adicionais, como por data de criação e conclusão.
Persistência de Estado: Garantir que os dados do usuário sejam mantidos mesmo em caso de falha de rede.

## Correções Pendentes
Erro de Animações: Revisar e corrigir o erro relacionado ao uso de animações para permitir reativação.
Design e Layout: Melhorar a interface para maior usabilidade e estética.
