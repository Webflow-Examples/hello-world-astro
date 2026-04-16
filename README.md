# Astro + React + Webflow Cloud

Example [Astro](https://astro.build) app with React islands and the Cloudflare adapter, set up for [Webflow Cloud](https://webflow.com/cloud).

[![Deploy to Webflow](https://webflow.com/img/deploy-dark.svg)](https://webflow.com/dashboard/cloud/deploy?repo=https://github.com/Webflow-Examples/hello-world-astro)

## Project structure

```text
.
├── astro.config.mjs
├── package.json
├── package-lock.json
├── public/
│   ├── .assetsignore
│   ├── favicon.svg
│   └── webflow.svg
├── src/
│   ├── env.d.ts
│   ├── layouts/
│   │   └── Layout.astro
│   ├── lib/
│   │   └── counter.ts
│   ├── pages/
│   │   ├── api/
│   │   │   └── hello.ts
│   │   └── index.astro
│   └── styles/
│       └── global.css
├── tsconfig.json
├── webflow.json
├── wrangler.json
└── worker-configuration.d.ts
```

## Commands

| Command | Action |
| :------ | :----- |
| `npm install` | Installs dependencies |
| `npm run dev` | Starts the Astro dev server at `http://localhost:4321` |
| `npm run build` | Builds the production site |
| `npm run preview` | Runs `astro build` then `wrangler dev` for a local preview |
| `npm run deploy` | Deploys with `webflow cloud deploy` |
| `npm run astro` | Runs the Astro CLI (e.g. `astro add`, `astro check`) |
| `npm run cf-typegen` | Generates Wrangler TypeScript types (`wrangler types`) |

## Learn more

- [Astro documentation](https://docs.astro.build)
- [Webflow Cloud](https://webflow.com/cloud)
