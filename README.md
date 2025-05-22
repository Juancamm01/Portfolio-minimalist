# Portfolio Minimalista

Estado: 🚧 En desarrollo 🚧

Este es un portafolio minimalista construido con [Astro](https://astro.build/), diseñado para ser rápido, sencillo y fácil de personalizar.

## Tecnologías utilizadas

- **Astro**: Framework principal para la generación de sitios estáticos.
- **TypeScript**: Tipado estático para mayor robustez y mantenibilidad.
- **Vite**: Bundler ultrarrápido utilizado por Astro.
- **pnpm**: Gestor de paquetes eficiente y rápido.
- **CSS**: Estilos personalizados para un diseño limpio y minimalista.
- **SVG**: Imágenes vectoriales para íconos y fondos.
- **Componentes Astro**: Estructura modular y reutilizable.
- **Esquema JSON de CV de [jsonresume.org](https://jsonresume.org/)**: Para estructurar y mostrar la información del currículum de forma estandarizada.

## Estructura del proyecto

```
Portfolio-minimalist/
├── public/
│   ├── favicon.svg
├── src/
│   ├── assets/
│   │   ├── astro.svg
│   │   ├── background.svg
│   ├── components/
│   │   ├── Welcome.astro
│   ├── layouts/
│   │   ├── Layout.astro
│   ├── pages/
│   │   ├── index.astro
├── .gitignore
├── astro.config.mjs
├── package.json
├── pnpm-lock.yaml
├── README.md
├── tsconfig.json
└── .vscode/
```

## Instalación

1. Clona el repositorio:
   ```sh
   git clone https://github.com/Juancamm01/Portfolio-minimalist.git
   cd Portfolio-minimalist
   ```

2. Instala las dependencias:
   ```sh
   pnpm install
   ```

3. Inicia el servidor de desarrollo:
   ```sh
   pnpm dev
   ```

4. Abre [http://localhost:4321](http://localhost:4321) en tu navegador.

## Créditos y agradecimientos

Este proyecto está fuertemente inspirado y basado en los repositorios de [midudev](https://github.com/midudev) y [Bartosz Jarocki](https://github.com/bartoszjarocki), así como en el esquema de CV de [jsonresume.org](https://jsonresume.org/). ¡Muchas gracias por compartir su trabajo y servir de inspiración para la comunidad!

- [Repositorio de midudev](https://github.com/midudev/minimalist-portfolio-json)
- [Repositorio de Bartosz Jarocki](https://github.com/BartoszJarocki/cv)
- [jsonresume.org](https://jsonresume.org/)

## Licencia

Este proyecto se distribuye bajo la licencia MIT.