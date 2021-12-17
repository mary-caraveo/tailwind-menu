# Tailwind: Healthy Food ☘

![overview](public/images/home.png)
## Librerias

* npm install tailwindcss autoprefixer postcss-cli

* npx tailwindcss init

* touch postcss.config.js

* npm install live-server -g

* live-server public

* npm run build

* npm install autoprefixer@'9.8.6'

* npx tailwindcss init tailwind.config.full.js --full

* npm i -D @fullhuman/postcss-purgecss

* npm install cssnano --save-dev

<h2>Directivas de Tailwind</h1>
Directiva es una instrucción que utiliza tailwind para insertar código en el archivo final de css que genera.

**@tailwind base**
Inyecta los estilos base de Tailwind y cualquier estilo base registrado por plugins.

**@tailwind components**
Inyecta las clases de componentes de Tailwind y cualquier clase de componente registrado por los plugins.

**@tailwind utilities**
Inyecta las clases de utilidad de Tailwind y cualquier clase de utilidad registrada por los plugins.


## Configuración
Tailwind es un framework para construir UI a la medida, por default, se tiene un archivo opcional llamado **tailwind.config.js** en la raíz de la carpeta, donde está el **package.json**.

#### Creando un archivo de configuración
Para generar un archivo de configuración para Tailwind, podemos usar el Tailwind CLI:

npx tailwind init
Se va a generar el siguiente archivo **tailwind.config.js**:

> module.exports = {
> theme: {},
> variants: {},
> plugins: [],
> }

Cada sección del archivo de configuración es opcional.

**La sección Theme**
Esta sección es donde definimos los aspectos relacionados con el diseño visual de nuestro sitio.

**La sección Variants**
Esta sección nos permite controlar el comportamiento de las utilidades core, como responsive variants y pseudo-class variants.

**La sección Plugins**
Esta sección nos permite registrar plugins de terceros con el objetivo de extender utilidades, componentes, estilos, etc.

Las propiedades de display son útiles para poder controlar las dimensiones o espacios. Las propiedades básicas de display son:

**Block →** Con esta configuración los bloques abarcan toda la pantalla.

**Inline-block →** Sólo ocupan el espacio necesario para mostrar lo que hay en su interior.

**Inline →** Sólo ocupan el espacio necesario para mostrar lo que hay en su interior y la altura del elemento es indiferente.

**Hidden →** El elemento en cuestión no se muestra.


