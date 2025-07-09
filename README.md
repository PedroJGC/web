# NLW Agents

Projeto desenvolvido durante o evento **NLW Agents** da Rocketseat. Uma aplicação React para gerenciamento de salas com interface moderna e responsiva.

## 🚀 Tecnologias

- **React 19** - Biblioteca para interfaces de usuário
- **TypeScript** - Linguagem com tipagem estática
- **Vite** - Build tool e dev server
- **React Router DOM** - Roteamento client-side
- **TanStack Query** - Gerenciamento de estado server
- **Tailwind CSS** - Framework CSS utilitário
- **shadcn/ui** - Componentes de interface
- **Lucide React** - Ícones

## 📦 Estrutura do Projeto

```
src/
├── components/ui/     # Componentes reutilizáveis
├── lib/              # Utilitários e configurações
├── pages/            # Páginas da aplicação
├── index.css         # Estilos globais
├── app.tsx          # Configuração de rotas
└── main.tsx         # Ponto de entrada
```

## 🛠️ Padrões Utilizados

- **Component Composition** - Componentes reutilizáveis com shadcn/ui
- **Custom Hooks** - TanStack Query para gerenciamento de estado
- **File-based Routing** - Organização de páginas por arquivos
- **CSS-in-JS** - Tailwind CSS com variáveis CSS personalizadas
- **TypeScript Strict** - Tipagem rigorosa em todo o projeto

## ⚙️ Configuração e Setup

### Pré-requisitos

- Node.js 18+
- npm, yarn ou pnpm

### Instalação

1. Clone o repositório:

```bash
git clone <url-do-repositorio>
cd nlw-agents
```

2. Instale as dependências:

```bash
npm install
```

3. Inicie o servidor de desenvolvimento:

```bash
npm run dev
```

4. Acesse a aplicação em `http://localhost:5173`

### Scripts Disponíveis

```bash
npm run dev      # Servidor de desenvolvimento
npm run build    # Build para produção
npm run preview  # Preview do build
```

## 🎨 Tema e Estilização

O projeto utiliza um sistema de design baseado em:

- **Tailwind CSS 4** com configuração personalizada
- **Tema escuro** por padrão
- **Variáveis CSS** para cores e espaçamentos
- **Componentes shadcn/ui** com estilo New York

## 📁 Configurações

- **Biome** - Linting e formatação de código
- **TypeScript** - Configuração strict com path mapping
- **Vite** - Build otimizado com plugins React e Tailwind

---

Desenvolvido com ❤️ durante o **NLW Agents** da Rocketseat
