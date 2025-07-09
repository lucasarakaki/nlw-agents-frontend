# NLW Agents Frontend 🎙️

## 📝 Descrição

Este é o frontend do projeto NLW Agents, uma plataforma para criar e participar de salas de perguntas e respostas. A aplicação permite que usuários criem salas, compartilhem o link com outras pessoas e respondam perguntas de forma organizada. O projeto foi desenvolvido durante a Next Level Week da Rocketseat e é integrado a um backend que utiliza IA para responder perguntas com base no contexto da sala.

## ✨ Funcionalidades

-   Criação de salas de perguntas e respostas.
-   Listagem de salas públicas.
-   Envio de perguntas em uma sala específica.
-   Respostas geradas por IA com base no contexto da sala.
-   Visualização de perguntas em tempo real.
-   Interface para gravação de áudio.

## 🚀 Tecnologias e Bibliotecas

A seguir estão as principais tecnologias e bibliotecas utilizadas no desenvolvimento deste projeto:

-   **Framework:** [React](https://react.dev/) com [Vite](https://vitejs.dev/)
-   **Linguagem:** [TypeScript](https://www.typescriptlang.org/)
-   **Estilização:** [Tailwind CSS](https://tailwindcss.com/)
-   **Componentes de UI:** [shadcn/ui](https://ui.shadcn.com/) (baseado em Radix UI)
-   **Gerenciamento de Estado de Servidor:** [TanStack Query (React Query)](https://tanstack.com/query/latest)
-   **Roteamento:** [React Router DOM](https://reactrouter.com/)
-   **Formulários:** [React Hook Form](https://react-hook-form.com/) com [Zod](https://zod.dev/) para validação
-   **Outras bibliotecas:**
    -   `lucide-react` para ícones
    -   `dayjs` para manipulação de datas
    -   `clsx` e `tailwind-merge` para utilitários de classes CSS

## 📋 Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:

-   [Node.js](https://nodejs.org/en/) (versão 18 ou superior)
-   [NPM](https://www.npmjs.com/) ou [Yarn](https://yarnpkg.com/)

## ⚙️ Como Rodar o Projeto Localmente

Siga os passos abaixo para executar o projeto em seu ambiente de desenvolvimento:

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/seu-usuario/nlw-agents-frontend.git
    cd nlw-agents-frontend
    ```

2.  **Instale as dependências:**
    ```bash
    npm install
    # ou
    yarn install
    ```

3.  **Execute o projeto:**
    ```bash
    npm run dev
    # ou
    yarn dev
    ```

O servidor de desenvolvimento será iniciado em `http://localhost:5173`.

## 📂 Estrutura de Pastas

A estrutura de pastas do projeto está organizada da seguinte forma:

```
/src
├───app.tsx             # Componente principal da aplicação
├───main.tsx            # Ponto de entrada da aplicação
├───assets/             # Arquivos estáticos (imagens, etc.)
├───components/         # Componentes reutilizáveis
│   ├───ui/             # Componentes de UI (shadcn)
│   └───...
├───http/               # Hooks e tipos para integração com a API
│   ├───hooks/          # Hooks customizados (useQuery, useMutation)
│   └───types/          # Tipos de dados da API
├───lib/                # Funções e utilitários
├───pages/              # Páginas da aplicação
└───...
```

## 🌐 Ambientes

-   **Desenvolvimento:** Ambiente para desenvolvimento local, iniciado com `npm run dev`.
-   **Produção:** Para gerar a versão de produção do projeto, execute o comando `npm run build`. Os arquivos otimizados serão gerados na pasta `dist/`.

## 🧪 Testes

Atualmente, não há uma estrutura de testes configurada para este projeto.

## 🤝 Contribuição

Contribuições são bem-vindas! Para contribuir com o projeto, siga os passos abaixo:

1.  Faça um fork do projeto.
2.  Crie uma nova branch (`git checkout -b feature/nova-funcionalidade`).
3.  Faça commit das suas alterações (`git commit -m 'feat: Adiciona nova funcionalidade'`).
4.  Faça push para a branch (`git push origin feature/nova-funcionalidade`).
5.  Abra um Pull Request.
