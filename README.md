# Dashboard Inmobiliario — React + Vercel

App de análisis de mercado inmobiliario construida en React, con gráficos interactivos y módulos financieros.

## Stack
- **React 18** (Create React App)
- **Recharts** — gráficos
- **SheetJS (xlsx)** — lectura de Excel directo desde GitHub
- **Vercel** — deploy gratuito

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
