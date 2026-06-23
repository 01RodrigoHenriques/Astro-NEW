# Nexus Twin Industrial Suite

[![Astro](https://img.shields.io/badge/Astro-5.0-FF5D01?style=flat&logo=astro&logoColor=white)](https://astro.build)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.4-06B6D4?style=flat&logo=tailwindcss&logoColor=white)](https://tailwindcss.com)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-000000?style=flat&logo=github&logoColor=white)](https://pages.github.com)

Landing page para a Nexus Twin Industrial Suite - plataforma B2B de cibersegurança industrial com foco em conformidade NIS2.

## Live Demo

🔗 [https://rodrigohenriques00.github.io/Astro-NEW/](https://rodrigohenriques00.github.io/Astro-NEW/)

## Tech Stack

- **Framework:** [Astro 5](https://astro.build)
- **Styling:** [Tailwind CSS 3](https://tailwindcss.com)
- **Background:** WebGL shader (Simplex noise)
- **Deploy:** GitHub Pages (via GitHub Actions)

## Estrutura

```
src/
├── components/        # Componentes .astro
│   ├── HowItWorks.astro      # Secção "Como Funciona"
│   ├── LeadMagnetForm.astro  # Formulário de lead magnet
│   ├── MarketParallelSection.astro
│   ├── ProblemSection.astro
│   ├── QuoteSection.astro
│   ├── SolutionSection.astro
│   ├── SupplyChainSection.astro
│   └── WebGLBackground.astro # Background animado
├── layouts/
│   └── BaseLayout.astro
├── pages/
│   ├── index.astro           # Homepage (scroll horizontal)
│   ├── 404.astro             # Erro personalizado
│   ├── politica-privacidade.astro
│   └── termos-uso.astro
└── styles/
    └── globals.css
```

## Desenvolvimento

```bash
pnpm install
pnpm dev       # http://localhost:4321
pnpm build     # gera dist/
```

## Deploy

O deploy é feito automaticamente via GitHub Actions quando fazes push para a branch `main`.

### Setup manual:

1. Faz push do código para o repositório `Astro-NEW`
2. Vai a **Settings > Pages** no GitHub
3. Em **Source**, seleciona **GitHub Actions**
4. O deploy acontece automaticamente

### URL do site:

```
https://rodrigohenriques00.github.io/Astro-NEW/
```

## Licença

MIT.