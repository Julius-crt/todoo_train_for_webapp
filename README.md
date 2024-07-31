# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

todoo_train_for_webapp
├── README.md
├── LICENSE -> 'klärt wer was mit der Software anstelen darf'
├── index.html ->'Landingpage - vite injeziert hier gebaute app'
├── node_modules ->'runtergeladene dependencys'
├── package-lock.json ->'npm erstellt, zum exakten dependency managment' 
├── package.json ->'Projektmetadata, Dependency/Skriptmanagm, Versionierung, ci/cd managm'
├── public ->'contains static (need not build) assets'
│   └── vite.svg
├── src 'development happens here'
│   ├── App.css
│   ├── App.jsx ->'first app component'
│   ├── assets
│   │   └── react.svg -'website symbol in Browsertab'
│   ├── index.css
│   └── main.jsx
└── vite.config.js