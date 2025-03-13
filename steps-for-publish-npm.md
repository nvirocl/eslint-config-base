# Pasos para publicación del package en npm

1. Inicia sesión en tu cuenta de npm usando el comando:
  ```sh
  npm login
  ```

2. Asegúrate de que el nombre del package en `package.json` sea `@nviro/eslint-config-base`.

3. Incrementa la versión del package según corresponda:
  ```sh
  npm version <tipo-de-versión>
  ```
  Reemplaza `<tipo-de-versión>` con `patch`, `minor` o `major`.

4. Publica el package en npm:
  ```sh
  npm publish --access public
  ```

5. Verifica que el package se haya publicado correctamente viendo la versión en la [web](https://www.npmjs.com/package/@nviro/eslint-config-base)
