
# Desarrollo de aplicaciones Frontend Trainee V2.0

## Modulo 3: Desarrollo de la interfaz de usuario Web

### Unidad 2: El modelo de cajas y el Layout - Dia 3: Desafío Evaluado: Cafetería Agere


>#### Requerimientos:
>- Separar logica visual del proyecto usando parciales, directivas @import y manifiesto.
>    - Crear manifiesto del proyecto Sass
>    - Crear archivos parciales necesarios para el proyecto
>    - Agregar parciales en manifiesto usando directiva ```@import```
>- Construir estructura HTML utilizando etiquetas semánticas
>    - Utilizar al menos 3 etiquetas semánticas de layout como ```<header>, <section>, <footer>, <nav>, <article>```
>- Crear clases semánticas utilizando nomenclatura de metodología BEM
>    - Agregar una clase bloque a la barra de navegación, a la navegación una clase de elemento y al botón una clase modificadora siguiendo la normas especificadas en la nomenclatura BEM.
>- Utilizar variables de Sass para reutilizar código CSS/SCSS. 
>    - Agregar variables de colores, fuentes, tamaño y grosor de fuentes siguiendo la guía de estilos
>    - Utilizar al menos 5 variables en el proyecto.
>- Crear estilos base del proyecto
>    - Agregar estilos reset al proyecto
>    - Agregar estilos base para tipografías del proyecto
>- Identificar elementos que constituyen la página del proyecto web
>    - Definir los estilos en la página.
>    - Crear parciales para la página
>    - Identificar colores de fondo usados en representación visual.
>    - Utilizar unidades de medidas relativas para que el layout sea fluido.
>    - Definir reglas a CSS/SCSS a utilizar en la página
>    - Utilizar reglas de posición en elementos e imágenes.
>    - Flotar contenedores en secciones header, navegación y contacto.
>    - Limpiar flotaciones usando clear
>- Crear estilos para componentes del proyecto web.
>    - Identificar componentes a dar estilos.
>    - Crear parciales para componentes.
>    - Definir reglas CSS/SCSS a utilizar componentes.

## Consideraciones para el uso de SASS
#### Estructura de carpetas
```
├───.vscode
└───assets
    ├───css
    ├───img
    └───scss
        ├───abstracts
        ├───base
        ├───components
        ├───layout
        ├───pages
        ├───themes
        └───vendors
```

*Puedes crear la estructura de carpetas completa utilzando el siguiente comando en tu terminal (debes tener creada la carpeta assets y dentro de esta, scss):*  
`mkdir -p assets/scss/{abstracts,base,components,layout,pages,themes,vendors}`  

#### Orden de importación en el manifiesto
En main.scss # Manifest file
**Recuerda usar el guión bajo antes de cada parcial**  
*Ejemplo: _reset.css*

1. abstracts
2. vendors
3. base
4. layout
5. components
6. pages
7. themes

#### Activación de Sass watcher
`sass --watch directorio/de/entrada directorio/de/salida`  

Otra forma de hacerlo sería:  
`sass --watch directorio/de/entrada:directorio/de/salida`

Ejemplo:  
`sass --watch assets/scss/main.scss:assets/css/main.css`

### Documentación:
- [Float](https://developer.mozilla.org/es/docs/Web/CSS/float)  
- [Float clear](https://developer.mozilla.org/es/docs/Web/CSS/clear)  
- [Float clearfix hack](https://www.w3schools.com/css/css_float_clear.asp)  
- [Posicionamiento:](https://developer.mozilla.org/es/docs/Web/CSS/position) static, fixed, relative, absolute, sticky  
- [Flexbox](https://developer.mozilla.org/es/docs/Learn/CSS/CSS_layout/Flexbox)  
- [Flex grow](https://developer.mozilla.org/es/docs/Web/CSS/flex-grow)  