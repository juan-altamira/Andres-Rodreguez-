sv

Todo lo que necesitás para crear un proyecto Svelte, impulsado por sv
.

Crear un proyecto

Si estás viendo esto, probablemente ya hiciste este paso. ¡Felicidades!

# crear un nuevo proyecto en el directorio actual
npx sv create

# crear un nuevo proyecto en “my-app”
npx sv create my-app

Desarrollo

Una vez que creaste un proyecto e instalaste las dependencias con npm install (o pnpm install o yarn), iniciá un servidor de desarrollo:

npm run dev

# o iniciá el servidor y abrí la app en una nueva pestaña del navegador
npm run dev -- --open

Compilación

Para crear una versión de producción de tu aplicación:

npm run build


Podés previsualizar la compilación de producción con npm run preview.

Para desplegar tu aplicación, puede que necesites instalar un adaptador
 para tu entorno de destino.
