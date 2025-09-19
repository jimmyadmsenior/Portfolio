# 🚀 Portfolio Profissional - Jimmy Castilho

<div align="center">

![Portfolio Banner](https://img.shields.io/badge/Portfolio-2024-blue?style=for-the-badge&logo=react&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-14.1.4-black?style=for-the-badge&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.3-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

**Um portfólio moderno e interativo construído com as mais recentes tecnologias web**

[🌐 Ver Demo](#) • [📧 Contato](mailto:jimmycastilho555@gmail.com) • [💼 LinkedIn](https://www.linkedin.com/in/jimmy-castilho-003733270/)

</div>

---

## 📋 Índice

- [🎯 Sobre o Projeto](#-sobre-o-projeto)
- [✨ Características](#-características)
- [🛠️ Tecnologias Utilizadas](#%EF%B8%8F-tecnologias-utilizadas)
- [📦 Instalação e Execução](#-instalação-e-execução)
- [📁 Estrutura do Projeto](#-estrutura-do-projeto)
- [🎨 Componentes Principais](#-componentes-principais)
- [🔧 Configuração](#-configuração)
- [📱 Responsividade](#-responsividade)
- [🚀 Deploy](#-deploy)
- [📈 Performance](#-performance)
- [🤝 Contribuição](#-contribuição)
- [📄 Licença](#-licença)

---

## 🎯 Sobre o Projeto

Este portfólio é uma aplicação web moderna e totalmente responsiva, desenvolvida para demonstrar minhas habilidades como desenvolvedor full-stack e especialista em cibersegurança. O projeto combina design elegante com funcionalidades avançadas, oferecendo uma experiência de usuário excepcional.

### 🎨 Design Highlights

- **Interface Moderna**: Design minimalista com elementos visuais sofisticados
- **Animações Fluidas**: Transições suaves utilizando Framer Motion
- **Efeitos 3D**: Integração com Three.js para elementos interativos
- **Tema Dark**: Interface elegante com paleta de cores dark
- **Navegação Flutuante**: Navbar responsiva com scroll spy

---

## ✨ Características

### 🌟 Funcionalidades Principais

- 🎭 **Hero Section Animada**: Apresentação impactante com efeitos visuais
- 🎯 **Grid Interativo**: Seção sobre mim com layout responsivo
- 💼 **Portfólio de Projetos**: Showcase dos principais projetos desenvolvidos
- 🏢 **Clientes & Tecnologias**: Carrossel de tecnologias dominadas
- 📊 **Experiência Profissional**: Timeline interativa de experiências
- 🎨 **Metodologia de Trabalho**: Apresentação da abordagem profissional
- 📞 **Contato**: Formulário de contato integrado

### 🔧 Características Técnicas

- **Server-Side Rendering (SSR)**: Otimização para SEO com Next.js
- **TypeScript**: Tipagem estática para maior confiabilidade
- **Componentes Reutilizáveis**: Arquitetura modular e escalável
- **Performance Otimizada**: Carregamento rápido e otimizações avançadas
- **Monitoramento**: Integração com Sentry para tracking de erros
- **Responsive Design**: Adaptável a todos os tamanhos de tela

---

## 🛠️ Tecnologias Utilizadas

### 🎨 Frontend

| Tecnologia | Versão | Descrição |
|------------|--------|-----------|
| **Next.js** | 14.1.4 | Framework React para produção |
| **React** | 18.x | Biblioteca para interfaces de usuário |
| **TypeScript** | 5.x | Superset tipado do JavaScript |
| **Tailwind CSS** | 3.3 | Framework CSS utilitário |
| **Framer Motion** | 11.0.25 | Biblioteca de animações |

### 🎭 Animações & Efeitos

| Biblioteca | Versão | Uso |
|------------|--------|-----|
| **Three.js** | 0.163.0 | Gráficos 3D e WebGL |
| **@react-three/fiber** | 8.16.2 | React renderer para Three.js |
| **@react-three/drei** | 9.105.4 | Helpers para Three.js |
| **react-lottie** | 1.2.4 | Animações Lottie |

### 🎯 UI/UX

| Ferramenta | Versão | Finalidade |
|------------|--------|------------|
| **Lucide React** | 0.365.0 | Ícones modernos |
| **@tabler/icons-react** | 3.1.0 | Conjunto adicional de ícones |
| **React Icons** | 5.0.1 | Biblioteca abrangente de ícones |
| **next-themes** | 0.3.0 | Gerenciamento de temas |

### 🔧 Utilitários

- **clsx** & **tailwind-merge**: Gerenciamento de classes CSS
- **class-variance-authority**: Variantes de componentes
- **mini-svg-data-uri**: Otimização de SVGs

### 📊 Monitoramento & Deploy

- **@sentry/nextjs**: Monitoramento de erros em produção
- **Vercel**: Plataforma de deploy e hospedagem

---

## 📦 Instalação e Execução

### 📋 Pré-requisitos

- **Node.js** (versão 18 ou superior)
- **npm** ou **yarn** ou **pnpm**
- **Git**

### 🚀 Passos para Instalação

1. **Clone o repositório**
   ```bash
   git clone https://github.com/jimmyadmsenior/Portfolio.git
   cd Portfolio/Portfolio
   ```

2. **Instale as dependências**
   ```bash
   npm install
   # ou
   yarn install
   # ou
   pnpm install
   ```

3. **Configure as variáveis de ambiente**
   ```bash
   cp .env.local.example .env.local
   ```
   
   Edite o arquivo `.env.local` com suas configurações:
   ```env
   NEXT_PUBLIC_SENTRY_DSN=your_sentry_dsn_here
   SENTRY_ORG=your_sentry_org
   SENTRY_PROJECT=your_sentry_project
   ```

4. **Execute o projeto em modo desenvolvimento**
   ```bash
   npm run dev
   # ou
   yarn dev
   # ou
   pnpm dev
   ```

5. **Acesse no navegador**
   ```
   http://localhost:3000
   ```

### 🏗️ Build para Produção

```bash
# Build da aplicação
npm run build

# Iniciar em modo produção
npm start
```

---

## 📁 Estrutura do Projeto

```
Portfolio/
├── 📂 app/                     # App Router do Next.js 14
│   ├── 📄 layout.tsx          # Layout principal
│   ├── 📄 page.tsx            # Página inicial
│   ├── 📄 globals.css         # Estilos globais
│   ├── 📄 provider.tsx        # Providers de contexto
│   └── 📂 api/               # API Routes
│
├── 📂 components/             # Componentes React
│   ├── 📄 Hero.tsx           # Seção hero principal
│   ├── 📄 Grid.tsx           # Grid de apresentação
│   ├── 📄 RecentProjects.tsx # Portfólio de projetos
│   ├── 📄 Experience.tsx     # Experiência profissional
│   ├── 📄 Approach.tsx       # Metodologia de trabalho
│   ├── 📄 Clients.tsx        # Clientes e tecnologias
│   ├── 📄 Footer.tsx         # Rodapé e contato
│   └── 📂 ui/               # Componentes de UI reutilizáveis
│       ├── 📄 FloatingNavbar.tsx    # Navegação flutuante
│       ├── 📄 BentoGrid.tsx         # Grid layout
│       ├── 📄 MovingBorders.tsx     # Bordas animadas
│       ├── 📄 TextGenerateEffect.tsx # Efeito de texto
│       ├── 📄 CanvasRevealEffect.tsx # Efeitos canvas
│       ├── 📄 Globe.tsx             # Globo 3D
│       └── 📄 ...                   # Outros componentes UI
│
├── 📂 data/                   # Dados e configurações
│   ├── 📄 index.ts           # Dados principais
│   ├── 📄 confetti.json      # Configuração de confetti
│   └── 📄 globe.json         # Dados do globo 3D
│
├── 📂 lib/                    # Utilitários e helpers
│   └── 📄 utils.ts           # Funções utilitárias
│
├── 📂 public/                 # Assets estáticos
│   ├── 🖼️ *.svg              # Ícones e ilustrações
│   ├── 🖼️ *.png              # Imagens
│   └── 🎭 *.gif              # Animações
│
├── 📄 package.json            # Dependências e scripts
├── 📄 next.config.mjs         # Configuração do Next.js
├── 📄 tailwind.config.ts      # Configuração do Tailwind
├── 📄 tsconfig.json           # Configuração do TypeScript
└── 📄 components.json         # Configuração de componentes UI
```

---

## 🎨 Componentes Principais

### 🦸‍♂️ Hero Section
**Localização**: `/components/Hero.tsx`

Seção de apresentação principal com:
- Efeito de texto animado
- Background com spotlight
- Call-to-action interativo
- Animações de entrada suaves

### 🎯 Grid Interativo
**Localização**: `/components/Grid.tsx`

Grid responsivo apresentando:
- Informações pessoais
- Stack tecnológica
- Localização
- Interesses profissionais

### 💼 Portfólio de Projetos
**Localização**: `/components/RecentProjects.tsx`

Showcase dos projetos com:
- Cards interativos com hover effects
- Links para repositórios GitHub
- Stack tecnológica utilizada
- Descrições detalhadas

### 📊 Experiência Profissional
**Localização**: `/components/Experience.tsx`

Timeline de experiências incluindo:
- Desenvolvimento Full Stack
- Cibersegurança
- Desenvolvimento Mobile
- Infraestrutura e Sistemas

### 🎨 Metodologia de Trabalho
**Localização**: `/components/Approach.tsx`

Apresentação da abordagem profissional:
- Planejamento e estratégia
- Desenvolvimento iterativo
- Testes e qualidade
- Deploy e manutenção

---

## 🔧 Configuração

### 🎨 Personalização de Temas

O projeto utiliza **Tailwind CSS** com configuração customizada:

```typescript
// tailwind.config.ts
export default {
  content: [
    "./pages/**/*.{js,ts,jsx,tsx,mdx}",
    "./components/**/*.{js,ts,jsx,tsx,mdx}",
    "./app/**/*.{js,ts,jsx,tsx,mdx}",
  ],
  darkMode: "class",
  theme: {
    extend: {
      colors: {
        black: {
          DEFAULT: "#000",
          100: "#000319",
          200: "rgba(17, 25, 40, 0.75)",
          300: "rgba(255, 255, 255, 0.125)",
        },
        white: {
          DEFAULT: "#FFF",
          100: "#BEC1DD",
          200: "#C1C2D3",
        },
        blue: {
          "100": "#E4ECFF",
        },
        purple: "#CBACF9",
      },
      // ... outras configurações
    },
  },
  plugins: [require("tailwindcss-animate")],
}
```

### 📊 Configuração do Sentry

Para monitoramento de erros em produção:

```javascript
// sentry.client.config.ts
import * as Sentry from "@sentry/nextjs";

Sentry.init({
  dsn: process.env.NEXT_PUBLIC_SENTRY_DSN,
  integrations: [
    new Sentry.Replay({
      maskAllText: true,
      blockAllMedia: true,
    }),
  ],
  tracesSampleRate: 1,
  replaysSessionSampleRate: 0.1,
  replaysOnErrorSampleRate: 1.0,
  debug: false,
});
```

---

## 📱 Responsividade

O projeto foi desenvolvido seguindo a metodologia **Mobile First** com breakpoints:

| Dispositivo | Breakpoint | Características |
|-------------|------------|-----------------|
| 📱 **Mobile** | < 640px | Layout vertical, navegação adaptada |
| 📟 **Tablet** | 640px - 1024px | Grid de 2 colunas, elementos redimensionados |
| 💻 **Desktop** | 1024px - 1280px | Layout completo, todas as funcionalidades |
| 🖥️ **Large Desktop** | > 1280px | Espaçamento otimizado, elementos expandidos |

### 🎨 Adaptações por Dispositivo

- **Mobile**: Menu hamburger, grid vertical, texto otimizado
- **Tablet**: Grid híbrido, navegação lateral, imagens responsivas
- **Desktop**: Layout completo, hover effects, animações complexas

---

## 🚀 Deploy

### 🌐 Vercel (Recomendado)

1. **Deploy Automático**:
   ```bash
   npm run deploy
   ```

2. **Configuração de Domínio**:
   - Conecte seu domínio personalizado
   - Configure SSL automático
   - Otimizações de performance automáticas

### 🐳 Docker

```dockerfile
# Dockerfile
FROM node:18-alpine AS base
WORKDIR /app
COPY package*.json ./
RUN npm ci --only=production

FROM base AS build
COPY . .
RUN npm run build

FROM node:18-alpine AS runtime
WORKDIR /app
COPY --from=build /app/.next/standalone ./
COPY --from=build /app/.next/static ./.next/static
COPY --from=build /app/public ./public

EXPOSE 3000
CMD ["node", "server.js"]
```

### 🔧 Netlify

1. Conecte o repositório
2. Configure build command: `npm run build`
3. Defina publish directory: `.next`

---

## 📈 Performance

### ⚡ Otimizações Implementadas

- **Image Optimization**: Next.js Image component com lazy loading
- **Code Splitting**: Carregamento automático de componentes
- **Bundle Analysis**: Monitoramento do tamanho dos bundles
- **Caching**: Estratégias de cache avançadas
- **Minification**: Compressão automática de assets

### 📊 Métricas de Performance

| Métrica | Score | Otimização |
|---------|-------|------------|
| **First Contentful Paint** | < 1.8s | Otimização de critical path |
| **Largest Contentful Paint** | < 2.5s | Image optimization |
| **Cumulative Layout Shift** | < 0.1 | Layout stability |
| **Time to Interactive** | < 3.8s | Code splitting |

---

## 🤝 Contribuição

Contribuições são sempre bem-vindas! Para contribuir:

### 📝 Guidelines

1. **Fork** o projeto
2. **Crie** uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. **Commit** suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. **Push** para a branch (`git push origin feature/AmazingFeature`)
5. **Abra** um Pull Request

### 🐛 Reportando Bugs

Use o template de issue para reportar bugs:
- Descrição clara do problema
- Passos para reproduzir
- Comportamento esperado vs atual
- Screenshots se aplicável

### 💡 Sugerindo Melhorias

- Use o template de feature request
- Descreva a melhoria proposta
- Explique os benefícios
- Considere alternativas

---

## 📄 Licença

Este projeto está sob a licença **MIT**. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## 📞 Contato

<div align="center">

**Jimmy Castilho** - Desenvolvedor Full Stack & Especialista em Cibersegurança

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jimmy-castilho-003733270/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/jimmyadmsenior)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/jimmycastilho/)

📍 **Localização**: Salto, SP - Brasil  
📧 **Email**: [jimmycastilho555@gmail.com](mailto:jimmycastilho555@gmail.com)

</div>

---

<div align="center">

### 🌟 Se este projeto foi útil, considere dar uma ⭐!

**Feito com ❤️ e muito ☕ por Jimmy Castilho**

</div>

