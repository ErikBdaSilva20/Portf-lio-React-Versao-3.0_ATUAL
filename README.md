<div align="center">

  <img src="public/TitleIcon.svg" alt="Erik.dev Logo" width="72" />

# ERIK.DEV — Portfólio Pessoal

![React](https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-6-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Styled Components](https://img.shields.io/badge/Styled_Components-6-DB7093?style=for-the-badge&logo=styled-components&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-12-black?style=for-the-badge&logo=framer&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES2024-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Portfólio profissional com experiência cinematográfica, design system consistente e animações modernas.**

[🌐 Ver ao vivo](https://erikbdsilva-hg.online/) · [📄 Currículo](public/curriculo-ErikBorges-FrontEnd.pdf) · [💼 LinkedIn](https://www.linkedin.com/in/erik-borgessilva20) · [🐙 GitHub](https://github.com/ErikBdaSilva20)

</div>

---

## ✨ Destaques

| Feature                           | Descrição                                                            |
| --------------------------------- | -------------------------------------------------------------------- |
| 🎬 **Animações Cinematográficas** | Transições com Framer Motion — zoom out na hero, fade+blur por seção |
| 📊 **ScrollProgressBar**          | Barra de progresso com spring physics e gradiente                    |
| 🌊 **Scroll com Easing**          | `easeInOutCubic` customizado — sensação de câmera se movendo         |
| 🎨 **Design System**              | Tokens de cor, tipografia e espaçamento centralizados em `theme.js`  |
| 📱 **Mobile Premium**             | `100svh`, safe-area-inset, touch targets ≥48px                       |
| ⚡ **Performance**                | Code splitting, lazy loading, grid otimizado via pseudo-elemento     |
| 🔍 **SEO**                        | Meta tags, Open Graph, Twitter Card                                  |

---

## 🛠️ Stack Tecnológica

```
Frontend
├── React 19           — Interface de usuário
├── Vite 6             — Bundler e dev server ultrarrápido
├── Styled Components  — CSS-in-JS com Design System
├── Framer Motion 12   — Animações declarativas e spring physics
├── MUI Icons          — Ícones de interface
└── JavaScript ES2024  — Lógica da aplicação

Integrações
├── React Typewriter   — Efeito de digitação na hero
└── React Multi Carousel — Carrosséis de projetos e skills

Ferramentas
├── ESLint + Prettier  — Qualidade e formatação de código
└── pnpm               — Gerenciador de pacotes rápido
```

---

## 📁 Estrutura do Projeto

```
src/
├── assets/                   # Imagens e recursos estáticos
├── Accessories/               # Componentes decorativos (Circle, WhatsApp, Code Snippets)
│   ├── circleIcon.jsx
│   ├── whatsAppIcon.jsx
│   ├── semiSquareCorner.jsx
│   ├── toasterEmailSend.jsx
│   └── CodeSnippets/
├── components/                # Componentes reutilizáveis
│   ├── AnimatedSection/       # 🆕 Wrapper de animações por seção
│   ├── ScrollProgressBar/     # 🆕 Barra de progresso de scroll
│   ├── BioCard/               # Seção hero com dados do dev
│   ├── Header/                # Navbar fixa com blur dinâmico
│   ├── SkillsCards/           # Carrossel de habilidades
│   ├── CarouselProjects/      # Galeria de projetos
│   ├── ContactMe/             # redes sociais
│   ├── Footer/                # Rodapé com links rápidos
│   ├── NavigateToCertificates/ # Carrossel de certificados
│   ├── AboutMeAndCertificates/ # Seção "Sobre mim"
│   ├── TemporalJourneyInfos/  # Timeline de formação
│   └── ToolsAndProficiency/   # Carrossel de ferramentas
├── pages/Home/                # Página principal — monta todas as seções
├── styles/                    # 🆕 Design System
│   ├── theme.js               # Tokens: cores, fontes, espaçamento, breakpoints
│   ├── animations.js          # Keyframes compartilhados
│   └── globalstyles.js        # Reset e estilos globais
└── utils/                     # Funções utilitárias puras
    ├── scrollToSection.js     # Scroll cinematográfico com easing
    ├── lazyRender.jsx         # IntersectionObserver helper
    ├── colors.js              # Paleta de cores (wrapper do theme)
    └── Arrow.jsx              # Componente de seta utilitário
```
---

## 🎨 Design System

O projeto usa um Design System centralizado em `src/styles/theme.js`:

```js
// Cores
theme.colors.primary; // rgba(0, 247, 255, 1) — cyan principal
theme.colors.accent; // rgba(186, 133, 255, 1) — roxo

// Tipografia
theme.fonts.heading; // 'Orbitron' — títulos tech
theme.fonts.body; // 'Poppins' — corpo de texto

// Media Queries
mq.mobile; // @media (max-width: 480px)
mq.tablet; // @media (max-width: 768px)
mq.laptop; // @media (max-width: 1024px)
```

---

## 📈 Melhorias — v2.0 (Março 2026)

```
✅ Design System com tokens centralizados (theme.js)
✅ Animações de entrada com Framer Motion (zoom, fade, slide, blur)
✅ Scroll cinematográfico com easeInOutCubic
✅ ScrollProgressBar com spring physics
✅ Header com bg/blur dinâmicos via useScroll
✅ Menu mobile com slide suave e 100svh (iOS safe area)
✅ Tipografia fluida com clamp() — sem breakpoints de texto
✅ Breakpoints unificados via mq helper
✅ Code splitting por vendor chunks (Framer, MUI, React)
✅ Grid de fundo via pseudo-elemento (melhor performance)
✅ Correção do font-style: italic global (bug crítico)
✅ Correção do valor inválido em colors.darkCyan
✅ Remoção de exports duplicados no barrel index.js
✅ SEO completo: meta tags, Open Graph, Twitter Card
✅ WhatsApp com safe-area-inset para iPhone
✅ Touch targets mínimos de 48px no mobile
✅ Scrollbar customizada com tema
✅ README.md profissional
```

---

## 📞 Contato

<div align="center">

📧 [erik.silvadesenvolvedor@gmail.com](mailto:erik.silvadesenvolvedor@gmail.com)

📱 [+55 (54) 99956-6625](https://wa.me/54999566625)

💼 [LinkedIn](https://www.linkedin.com/in/erik-borgessilva20)

🐙 [GitHub](https://github.com/ErikBdaSilva20)

📍 Rio Grande do Sul — Brasil

</div>

---

<div align="center">
  <p>Feito por <strong>Erik Borges da Silva</strong></p>
  <p><em>© 2025 — Open to work and coding ⚡</em></p>
</div>
