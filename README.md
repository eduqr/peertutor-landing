# Astro + Tailwind

Este proyecto usa [Astro](https://docs.astro.build/en/getting-started/) y [Tailwind](https://tailwindcss.com/docs/installation).

## 🐛 ¿Cómo empezar a trabajar?

1. Clona el proyecto en la ruta de tu elección

```bash
git clone https://github.com/eduqr/bibliopolis-nodejs.git
```

2. Entra a la carpeta

```bash
cd bibliopolis-nodejs/
```

3. Abre el proyecto en Visual Studio Code

```bash
code .
```

4. Abre una terminal en vscode

- Teclados en español: <kbd>Ctrl</kbd> + <kbd>ñ</kbd>
- Teclados en inglés: <kbd>Ctrl</kbd> + <kbd>`</kbd>

5. Instala las dependencias del proyecto

```bash
npm install
```

6. Inicia el servidor de desarrollo

```bash
npm run dev
```

## 🪣 Extensiones importantes

Dentro de Visual Studio Code ve al apartado de Extensiones e instala las siguientes:

- [Tailwind CSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss): Sirve para ver los estilos CSS que aplica Tailwind.
- [Astro](https://marketplace.visualstudio.com/items?itemName=astro-build.astro-vscode): Te da resaltado de sintaxis para los archivos .astro.
- [Error Lens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens): Resaltado de erroes (opcional).
- [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode): Formateador de código (lo ordena, opcional).
- [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme): Iconos de archivos (opcional).

## 🖍️ Colores

Para agregar los colores personalizados que necesites ve al archivo ´tailwind.config.mjs´ y agrégalo debajo del ginda (es de ejemplo), dale un nombre y su código de color.

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── Card.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
