<div style="display: flex; justify-content: space-between;">
  <p align="center">
    <a href="https://react.dev/" target="blank"><img src="public/react.svg" width="200" alt="React Logo"/></a>
  </p>
  
  <p align="center">
    <a href="https://vitejs.dev/" target="blank"><img src="public/vite.svg" width="200" alt="Vite Logo"/></a>
  </p>

  <p align="center">
    <a href="https://www.typescriptlang.org/" target="blank"><img src="public/typescript.svg" width="200" alt="TypeScript Logo"/></a>
  </p>
</div>

# Consulta del Clima - React + Vite + TypeScript + API

Aplicación creada con [React](https://react.dev/) y [Vite](https://vitejs.dev/) usando [TypeScript](https://www.typescriptlang.org/), la cual es una aplicación para Consultar el Clima actual de diferentes países del mundo, solo tienes que llenar en el formulario los campos de Ciudad y País, y la aplicación realizará una consulta a la API de [OpenWeather](https://openweathermap.org/), mostrando la información solicitada, la APP cuenta con validaciones en los campos del formulario, notificaciones personalizadas y uso de Spinners.

Algunos de los conceptos utilizados para la generación de ésta App, son:

1. Formularios.
2. Validaciones.
3. useState.
4. useEffect.
5. useMemo.
6. CSS Modules.
7. Hooks personalizados.
8. [Axios](https://www.npmjs.com/package/axios).
9. [Zod](https://www.npmjs.com/package/zod).
10. [Valibot](https://www.npmjs.com/package/valibot).
11. Uso de Spinners ([Spinkit](https://tobiasahlin.com/spinkit/)).
12. Y más.

# Nota

Al conectarse a una API, es necesario utilizar una API-Key, recuerda que tienes que generar una archivo llamado **.env.local** en la raíz del proyecto con la llave **VITE_API_KEY=** + tu propio API-Key.

# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default {
  // other rules...
  parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
  },
}
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
