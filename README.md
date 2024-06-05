# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh


# Deploy Vercel

## Instalação global do vercel-cli

```shelll
npm i -g vercel
```

```shell
vercel
```

## Configurando as rotas
Fonte: https://stackoverflow.com/questions/64815012/why-does-react-router-not-works-at-vercel

```json
{
  "rewrites":  [
    {"source": "/(.*)", "destination": "/"}
  ]
}
```