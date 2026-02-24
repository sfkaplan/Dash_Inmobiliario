# Dashboard Inmobiliario — React + Vercel

App de análisis de mercado inmobiliario construida en React, con gráficos interactivos y módulos financieros.

## Stack
- **React 18** (Create React App)
- **Recharts** — gráficos
- **SheetJS (xlsx)** — lectura de Excel directo desde GitHub
- **Vercel** — deploy gratuito

---

## Deploy en Vercel (gratis, ~3 minutos)

### Opción A — GitHub (recomendado)
1. Subí esta carpeta a un repositorio GitHub.
2. Entrá a [vercel.com](https://vercel.com) y creá una cuenta gratuita.
3. Hacé clic en **"Add New Project"** → importá el repo.
4. Vercel detecta automáticamente que es Create React App. Dejá todo por defecto.
5. Hacé clic en **Deploy**. ✓

Cada `git push` redespliega automáticamente.

### Opción B — Vercel CLI
```bash
npm install -g vercel
cd inmobiliaria-app
npm install
vercel --prod
```

---

## Correr localmente
```bash
npm install
npm start
# → http://localhost:3000
```

---

## Estructura
```
inmobiliaria-app/
├── public/
│   └── index.html
├── src/
│   ├── index.js
│   └── App.jsx       ← toda la lógica y UI
├── package.json
├── vercel.json
└── README.md
```

## Datos
Los archivos Excel se leen directamente desde GitHub:
- `departamentos.xlsx`
- `casas.xlsx`

Si cambiás las URLs, modificá el objeto `URLS` al inicio de `App.jsx`.
