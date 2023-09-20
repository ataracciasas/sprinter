# Descripción general:

Este proyecto es una Single Page Application que se basa en el diseño presentado y propuesto para la compañía Caribbean Sprinter.

# Visualizacion del proyecto:

Para visualizar el proyecto, se debe clonar el repositorio y ejecutar el siguiente comando en la terminal:

- Para instalar las dependencias del proyecto:
```bash
npm run install
```

- Para ejecutar el proyecto en modo desarrollo:
```bash
npm run start
```

- Para crear un build del proyecto:
```bash
npm run build
```

# Uso y arquitectura del proyecto:

El proyecto usa el siguiente stack:

- Javascript: Para funcionalidades, eventos, router..etc.
- Sass: Para estilos y reglas css.
- Bootstrap 5: Para estilos rápidos, responsive y visualización.
- Webpack 5: Para empaquetado

# Organización de carpetas:

- dist: Carpeta donde se almacena el proyecto empaquetado.

- src: Carpeta donde se almacena el proyecto.
  - src/assets: Carpeta donde se almacenan los recursos del proyecto.
  - src/controllers: Carpeta donde se almacenan los script de cada pagina del proyecto, contiene la lógica de funciones de cada botón, aparición o desaparición de elementos..etc.
  - src/router: Carpeta donde se almacenan las rutas de cada pagina del componente.
  - styles: Carpeta donde se almacenan los estilos del proyecto.
  - views: Archivos html de cada pagina del proyecto.
  - index.js: Archivo principal del proyecto, contiene la lógica de la SPA.
  - index.scss: Archivo principal de estilos del proyecto, contiene los estilos globales del proyecto.
  - index.html: Página principal del proyecto. Contiene el header donde se importan las fuentes y bootstrap por CDN. Aparte, contiene el hamburger menu para el menu responsivo y el formulario de login en su version mobile. También, contiene el footer que es el mismo para todas las paginas y el body que se va a ir remplazando según el hash de la url.
