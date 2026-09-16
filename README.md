## Demo

**Acesse o site:**

https://gleybsondias.github.io/react-todo/

# Lista de Tarefas (React + Vite)

[![React](https://img.shields.io/badge/React-16.8%2B-61DAFB?logo=react&logoColor=white)](https://reactjs.org) [![Vite](https://img.shields.io/badge/Vite-3%2B-646cff?logo=vite&logoColor=white)](https://vitejs.dev) [![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3%2B-06B6D4?logo=tailwindcss&logoColor=white)](https://tailwindcss.com) [![Node.js](https://img.shields.io/badge/Node.js-16%2B-339933?logo=node.js&logoColor=white)](https://nodejs.org)

> Aplicação simples de lista de tarefas construída com React, Vite e Tailwind CSS — projeto pessoal pensado para demonstrar organização de componentes, boas práticas em UI e fluxo de trabalho front-end.

**Status:** Concluído — protótipo funcional

**Visão rápida**

Esta aplicação permite adicionar, visualizar detalhes, marcar como concluída e remover tarefas. Foi desenvolvida para demonstrar habilidades práticas em React (componentização e Hooks), roteamento com `react-router-dom` e estilização com Tailwind CSS.

**Demonstração local**

Requisitos: Node.js 16+ (recomendado 18+)

Instalação e execução:

```bash
npm install
npm run dev
```

Para gerar build de produção:

```bash
npm run build
npm run preview
```

Observação: existe também um script `npm run deploy` no projeto (consulte `package.json`).

**Funcionalidades principais**

- Adicionar nova tarefa com título e descrição (validação básica de entrada).
- Listagem de tarefas com ações: marcar como concluída, ver detalhes e excluir.
- Página de detalhes da tarefa com navegação de volta.
- UI responsiva simples construída com Tailwind CSS.

**Stack técnico**

- React (componentes funcionais + Hooks)
- Vite (bundler / dev server)
- Tailwind CSS (estilização utilitária)
- react-router-dom (roteamento e parâmetros de query)
- Lucide-react (ícones)

**Arquitetura / Estrutura do projeto (resumo)**

- `src/components/AddTask.jsx` — componente para adicionar tarefas (form simples e validação).
- `src/components/Tasks.jsx` — componente de listagem e botões de ação (detalhes, excluir, marcar).
- `src/pages/TaskPage.jsx` — página de detalhes que lê parâmetros de query.
- `src/main.jsx`, `src/App.jsx` — inicialização e configuração de rotas.

**O que este projeto demonstra (para recrutadores)**

- Capacidade de projetar e implementar componentes reutilizáveis em React.
- Uso prático de Hooks (`useState`, `useNavigate`, `useSearchParams`).
- Gerenciamento simples de estado e interação entre componentes (passagem de callbacks).
- Implementação de navegação e passagem de dados via query string.
- Estilização consistente com Tailwind e preocupação com layout/UX básico.

**Como revisar o código**

Para avaliar rapidamente as partes essenciais, confira estes arquivos:

- `src/components/AddTask.jsx`
- `src/components/Tasks.jsx`
- `src/pages/TaskPage.jsx`

**Contato / Autor**

Gleybson Dias — disponível para entrevistas técnicas e revisões de código.
