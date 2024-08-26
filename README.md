#### Criando o projeto
npm create vue@latest app-01

cd app-01
npm install
npm run dev

#### Dependências
npm i json-server
npm i axios

#### rodar o projeto
npm run dev

#### TailwindCSS
https://tailwindcss.com/docs/guides/vite#vue

npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p

* tailwind.config.js
```
/** @type {import('tailwindcss').Config} */ <br>
export default { <br>
  content: [ <br>
    "./index.html", <br>
    "./src/**/*.{vue,js,ts,jsx,tsx}", <br>
  ], <br>
  theme: { <br>
    extend: {}, <br>
  }, <br>
  plugins: [], <br>
} <br>
```

#### link ref.
https://www.youtube.com/watch?v=JpWWecMpaNI