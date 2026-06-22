# BolinaTEC

[![Astro](https://img.shields.io/badge/Astro-5.0-FF5D01?style=flat&logo=astro&logoColor=white)](https://astro.build)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.4-06B6D4?style=flat&logo=tailwindcss&logoColor=white)](https://tailwindcss.com)
[![Deployed on Cloudflare](https://img.shields.io/badge/Cloudflare%20Pages-000000?style=flat&logo=cloudflare&logoColor=white)](https://pages.cloudflare.com)

Landing page com scroll horizontal, fundo WebGL animado e formulário de contacto.

## Tech Stack

- **Framework:** [Astro 5](https://astro.build)
- **Styling:** [Tailwind CSS 3](https://tailwindcss.com)
- **Background:** WebGL shader (Simplex noise)
- **Deploy:** Cloudflare Pages

## Estrutura

```
src/
├── components/        # Componentes .astro
│   ├── AboutQuote.astro
│   ├── BentoPricing.astro
│   ├── ContactCard.astro
│   └── Feature.astro
├── layouts/
│   └── BaseLayout.astro
├── pages/
│   ├── index.astro           # Homepage (scroll horizontal)
│   ├── features.astro        # Funcionalidades
│   ├── pricing.astro         # Preços
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

```bash
pnpm build
# deploy via cloudflare
```

## Licença

MIT.
