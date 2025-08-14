Bewear: E-commerce Moderno com Next.js 15

Este é um projeto de e-commerce de alta performance, construído com uma stack moderna e totalmente type-safe. O foco principal é a manutenibilidade, escalabilidade e uma experiência de desenvolvimento excepcional, seguindo rigorosos padrões de código e arquitetura.
Tabela de Conteúdos

    ✨ Features

    🚀 Stack de Tecnologia

    📋 Pré-requisitos

    ⚙️ Instalação e Configuração

    📜 Princípios e Convenções

    🏗️ Arquitetura e Padrões do Projeto

    🤝 Como Contribuir

✨ Features

    [X] Catálogo de produtos com busca e filtros.

    [X] Carrinho de compras funcional.

    [X] Autenticação de usuários (Login, Cadastro).

    [X] Checkout e integração de pagamento.

    [X] Painel do usuário para gerenciamento de pedidos e dados.

🚀 Stack de Tecnologia

A seleção de tecnologias foi feita para garantir um desenvolvimento robusto, eficiente e moderno.

    Framework: Next.js 15 (App Router)

    Linguagem: TypeScript

    Estilização: Tailwind CSS

    Componentes UI: shadcn/ui

    Banco de Dados: PostgreSQL

    ORM: Drizzle

    Autenticação: BetterAuth

    Formulários: React Hook Form

    Validação de Dados: Zod

    Data Fetching/Client State: React Query

📋 Pré-requisitos

Antes de começar, certifique-se de ter as seguintes ferramentas instaladas em seu ambiente de desenvolvimento:

    Node.js (versão 20.x ou superior)

    NPM/Yarn

    Uma instância do PostgreSQL rodando localmente ou remotamente

⚙️ Instalação e Configuração

Siga os passos abaixo para configurar o ambiente de desenvolvimento local.

    Clone o repositório:

    git clone https://github.com/seu-usuario/seu-repositorio.git
    cd seu-repositorio

    Instale as dependências:

    npm install

    Configure as variáveis de ambiente:
    Crie uma cópia do arquivo .env.example e renomeie para .env.

    cp .env.example .env

    Preencha o arquivo .env com as suas credenciais, principalmente a DATABASE_URL.

    # Exemplo de .env
    DATABASE_URL="postgresql://USER:PASSWORD@HOST:PORT/DATABASE"

    Execute as migrações do banco de dados:
    O Drizzle usará o schema para sincronizar o estado do banco de dados.

    npm db:push

    Inicie o servidor de desenvolvimento:

    npm run dev

    O servidor estará disponível em http://localhost:3000.

📜 Princípios e Convenções

Este projeto segue um conjunto estrito de regras para garantir a qualidade e a consistência do código.

    Clean Code & SOLID: O código deve ser limpo, conciso e seguir os princípios SOLID.

    DRY (Don't Repeat Yourself): Evite a duplicação. Crie abstrações (funções, componentes) quando necessário.

    Tipagem: TypeScript é mandatório em todos os arquivos.

    Nomenclatura:

        Variáveis: camelCase, descritivas e claras (ex: isLoading, hasError).

        Pastas e arquivos: kebab-case (ex: sign-in-form).
