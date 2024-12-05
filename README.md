# WEB COLABORATIVA PARA TIENDA ONLINE - PAGAM(e)
## Contenido de la web
- Sección principal: Información detallada sobre el producto. 
- Sección "Servicios de ayuda": Descripción detallada de los servicios.
- Sección "Cómo trabajamos": Descripción detallada de los servicios
- Sección "Top productos": Destacando nombre del producto y precio.
## Objetivos
- Consolidar conocimientos: HTML, CSS, diseño responsive, GitHub pages, Sass, grid, Vite.
- Uso del control de versiones (GIt/GitHub).
- Implementar Scrum para el desarrollo del producto, siguiendo valores Aguile (puntos clave trabajo en equipo, mejora continua).
- Comunicación interna (miembros grupo).
- Comunicación externa (presentaciones: Sprint Review y presentación final proyecto).
## Especificaciones
### Tecnologías
- HTML y CSS (Sass). 
- Uso mediaqueries y diseño responsive.
- Git y GitHub para control de versiones mediante ramas.
- Publicación en GitHub Pages.
- Uso de Vite y NodeJS.
### Características de la página web:
Páginas de la web:
- Página principal:
  Home (index.html): Información principal sobre la aplicación.
- Página secundaria:
  Contacto (contacto.html): Información de contacto y formulario.
- Ambas páginas: header y footer.
- Header. Fijo parte superior al hacer scroll. 
Páginas de la web en diseño móvil:
- Menú navegación (Hamburguesa).
- Página principal: Diseño vertical de los servicios y productos.
- Página secundaria: Diseño vertical de los elementos.
  Contacto (contacto.html): Información de contacto, formulario y mapa.
- Footer: Logo Adalab. Iconos redes sociales.
Páginas de la web en diseño tablet:
- Menú navegación (Home, Nosotros, Contáctanos).
- Página principal:
  Sección principal: Introducción de mockup y botones al diseño.
  Sección "Servicios de ayuda": Distribución en zig-zag del diseño de los servicios.
  Sección "Cómo trabajamos" y "Top productos": Distribución horizontal.
- Página secundaria: Diseño horizontal de los elementos.
  Contacto (contacto.html): Información de contacto, formulario y mapa.
- Footer: Logo Adalab. Iconos redes sociales. Otro menú navegación (Inicio, Nosotros, Contáctanos).
### Tamaño responsive de las páginas:
Móvil, por debajo de 768px. (@media screen and (max-width: 768px)
Tablet, desde 768px en adelante.(@media screen and (min-width: 768px)
### Componentes
Diseño siguiendo guía de estilo en Zeplin.
-Logo, icono y tipografías: 
 Logo Adalab.
 Imágenes.
 Iconos.
-Tipografías Google Fonts:
 Roboto
### Planificación
Crear tablero del proyecto.
Definir tareas principales.
Working agreements.
### Historias de usuario
Primera. Versión móvil de la web.
- Desarrollo versión para móvil (página principal) con HTML y CSS.
- Creación contenido web: textos e imágenes.
- Creación infraestructura necesaria: repositorio GitHub (acceso todos los miembros).
Segunda. Versión responsive de la web.
- Diseño de la web para el resto de tamaños (tablet).
Tercera. Mejora de tecnología.
- Integración con Vite para automatización de tareas.
- División HTML en partials.
- Migración CSS a Sass (usando partials).
Cuarta.Formulario de contacto
- Realización del formulario de contacto para todos los dispositivos.
## INSTALACIÓN
Dentro del archivo de trabajo abrir una terminal BASH y clonar el repositorio de github.
Comprobar que la ruta del directorio es la adecuada. Posteriormente instalar las dependencias "node_modules" para la ejecución del framework Vite, e iniciar el proyecto. 
Clonar repositorio:
$ git clone https://github.com/MelsCrest/project-promo-B-module-1-team-2.git
Ruta directorio:
$ cd ../path/to/the/file
Instalación dependencias:
$ npm install
Iniciar proyecto:
$ npm start
## PUBLICACIÓN 
Primero generar la página para producción. En la terminal BASH introducir los comandos:
$ npm run build
A continuación subir la carpeta `docs/` que se acaba de generar a el repositorio. 
En la pestaña `settings` del repositorio ir al apartado de GitHub Pages y activar la opción **master branch /docs folder**.