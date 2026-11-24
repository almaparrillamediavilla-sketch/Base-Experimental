# app

Proyecto nuevo en React + TypeScript + Vite, dentro de Base-Experimental.
De momento solo tiene una página de inicio de ejemplo.

## Requisitos

Node.js 20.19 o superior (o 22.12+) y npm.

## Comandos

Todos se ejecutan desde esta carpeta (`app/`):

```bash
npm install       # instala las dependencias (la primera vez)
npm run dev       # servidor de desarrollo con recarga en caliente
npm run build     # comprueba tipos y genera la versión final en dist/
npm run preview   # sirve localmente lo generado en dist/
npm run lint      # revisa el código con Oxlint
```

## Estructura

```
app/
├── index.html        # página base que carga la app
├── public/           # archivos estáticos servidos tal cual (favicon)
└── src/
    ├── main.tsx      # punto de entrada de React
    ├── App.tsx       # componente principal: empieza aquí
    └── index.css     # estilos globales (modo claro y oscuro)
```
