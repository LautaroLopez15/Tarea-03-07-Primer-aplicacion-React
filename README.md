# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Oxc](https://oxc.rs)
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/)

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.



--RESPUESTAS--
¿Para qué sirve el archivo package.json?
Este archivo tiene informacion de nuestra app React y los mas importante, es que tiene las dependencias que usa la aplicacion. El comando nmp install lee desde "package.json" y descarga las dependencias. Esto ahorra a los desarrolladores de tener que enviar la carpeta "node_modules" si queremos compartir el proyecto

¿Qué diferencia notaron entre ejecutar un archivo directamente con Node.js y levantar el servidor de React?
Ejecutar directamente con Node.js no permite que se actualice automaticamente si hay algun cambio en nuestro codigo. Al usar un servidor de React, se activa el sistema Hot Module Replacement que actualiza automaticamente el navegador cuando hay algun cambio en nuestro codigo.
