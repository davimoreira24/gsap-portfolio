# Davi Moreira — Portfolio (3D)

Repositório do site **3D** (Three.js + webpack). O “OS” 2D dentro do monitor vive no repositório separado: [**inner-repo**](https://github.com/davimoreira24/inner-repo).

## Dev

```bash
nvm use 22
pnpm install
pnpm dev
```

## Inner (CRA) em paralelo

```bash
pnpm inner:install   # primeira vez
pnpm inner:dev       # http://localhost:3020
```

Em produção o iframe aponta para o deploy do inner (ex.: Vercel). Ver `src/Application/World/MonitorScreen.ts`.

## Build / produção

```bash
pnpm build
pnpm start
```
