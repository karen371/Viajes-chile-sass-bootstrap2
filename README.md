## Descripción del Proyecto

Este proyecto corresponde a la prueba del módulo 3, en el cual se ha creado una landing page para la agencia Viajes Chile. La página está diseñada utilizando Bootstrap, junto con algunos estilos personalizados en CSS y JavaScript. Los estilos personalizados se encuentran en el directorio `assets/sass/`. Puedes ver la maqueta utilizada para el diseño en el siguiente enlace:

[Maqueta de Diseño](./assets/img/maqueta.png)

### Instalacion de boostras 

Para instalar Bootstrap, sigue estos pasos utilizando la línea de comandos Cmd:

*Paso 1:* Crea la carpeta del proyecto con el siguiente comando:

`mkdir Portafolio-karen-godoy`

Luego, entra en la carpeta recién creada con:

`cd Portafolio-karen-godoy`

*Paso 2:* Inicializa un nuevo proyecto, para ello ulizamos el comando que se muestra a continuación, el cual es el proceso para crear un archivo package.json en el directorio del proyecto. Este archivo contiene información sobre el proyecto y sus dependencias:

`npm init -y`

*Paso 3:* Instala Bootstrap en la carpeta del proyecto con el siguiente comando:

`npm install bootstrap`

Este comando descargará Bootstrap y sus dependencias en la carpeta node_modules, que es necesaria para el correcto funcionamiento del proyecto.

Esta es la forma que a mi me funciono instalar de forma correcta bootstrap.

#### Variables de Bootstrap Modificadas

Se realizaron modificaciones en algunos colores de Bootstrap para adaptarlos a los requerimientos del proyecto. Los cambios se llevaron a cabo en la carpeta `abstracts/_variables` y consisten en los siguientes ajustes:

- **Color Primario**: `$primary: #fff;`
- **Color Secundario**: `$secondary: #0d0d0d;`
- **Color de Información**: `$info: #00aae4;`

Además, se actualizaron las variables de color para los tooltips:

- **Fondo del Tooltip**: `$tooltip-bg: $info;`
- **Color del Texto del Tooltip**: `$tooltip-color: $primary;`
