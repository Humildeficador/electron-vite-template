# Electron Vite Template

Um template minimalista e robusto para iniciar projetos desktop. Configurado para separar estritamente os ambientes de Node (Main/Preload) e Web (Renderer), garantindo segurança e performance.

## 🚀 Tecnologias

- [Electron](https://www.electronjs.org/)
- [Vite](https://vitejs.dev/)
- [React](https://react.dev/) + [TypeScript](https://www.typescriptlang.org/)
- [Tailwind CSS v4](https://tailwindcss.com/)
- [Biome](https://biomejs.dev/) (Linting & Formatação)
- [PNPM](https://pnpm.io/) (Gerenciador de Pacotes)

## ⚙️ Pré-requisitos

Antes de começar, você vai precisar ter instalado:

- [Node.js](https://nodejs.org/) (versão 18 ou superior)
- [PNPM](https://pnpm.io/installation)

Se você ainda não tem o PNPM, instale-o via terminal:

```bash
npm i -g pnpm
```

## 📦 Instalação

Clone o repositório e instale as dependências:

1. Clone o projeto:

   ```bash
   git clone https://github.com/Humildeficador/electron-vite-template.git
   ```

2. Entre no diretório:

   ```bash
   cd electron-vite-template
   ```

3. Instale as dependências (estritamente com pnpm):

   ```bash
   pnpm install
   ```

## 💻 Desenvolvimento

Para rodar o aplicativo em modo de desenvolvimento com Hot Module Replacement (HMR):

```bash
pnpm dev
```

## 🛠️ Build (Produção)

Para empacotar o aplicativo e gerar os executáveis finais para o seu sistema operacional:

```bash
pnpm build
```

### Para cada sistema individual

```bash
# Para windows
pnpm build:win

# Para macOS
pnpm build:mac

# Para Linux
pnpm build:linux
```

> **Nota:** Os arquivos empacotados pelo Electron-Builder estarão disponíveis na pasta `dist/` ou `build/` (pastas ignoradas pelo Git).
