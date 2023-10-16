# julio-gpt-style

Pre diseño de la app movil JulioGPT [JulioGPT MAUI Blazor App](https://github.com/kedatech/julio-gpt-maui-app)

## Requisitos 
- VsCode (Tailwind Extencion)
- Node.js

## Tailwind

Instalar dependencias:

`npm install`

Ejecutar watch de tailwind

`npx tailwindcss -i ./src/input.css -o ./src/output.css --watch`

## Deploy

Para deployar un proyecto con tailwind es recomendable usar un archivo minificado para esto ejecuta:

`npx tailwindcss -i ./src/input.css -o ./src/output.css --minify`