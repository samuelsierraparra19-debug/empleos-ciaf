# Bolsa de Empleo CIAF

Plataforma de empleo para estudiantes de la Corporación Instituto de Administración y Finanzas (CIAF), Pereira.

## Tecnologías

- React 18
- Vite 5
- Fuentes: Syne + DM Sans (Google Fonts)

## Desarrollo local

```bash
npm install
npm run dev
```

## Publicar en Vercel

### Opción 1 — Vercel CLI

```bash
npm install -g vercel
vercel login
vercel --prod
```

### Opción 2 — GitHub + Vercel Dashboard

1. Sube el proyecto a GitHub.
2. Entra a [vercel.com](https://vercel.com) → **New Project**.
3. Importa el repositorio.
4. En **Framework Preset** selecciona **Vite**.
5. Deja las configuraciones por defecto → **Deploy**.

Vercel detecta automáticamente Vite. El `vercel.json` incluido maneja el enrutamiento de la SPA.

## Estructura

```
bolsa_empleo_ciaf/
├── public/
│   └── favicon.svg
├── src/
│   ├── App.jsx       ← componente principal
│   └── main.jsx      ← punto de entrada React
├── index.html
├── package.json
├── vite.config.js
└── vercel.json
```
