# Prueba 2

# Enunciado

El cine ***CineContinent*** actualmente desarrolla sus sistemas de ventas a mano y por telefono para gestion de sus salas de cine. Debido a un proceso de transformación digital el cine desea transformar sus sistemas a componentes digitales. Para esto se ha encargado un sistema con arquitectura frontend - backend mediado por API REST. Usted es un conocido consultor de la industria de construcción de productos de software y se le ha encargado la fase 1 que consiste en la construcción de la plataforma frontend en Angular.

El sistema inicialmente debe tener una interfaz donde la administración sea capaz de agregar peliculas en cartelera, las cuales son asignadas a una sala de cine en un horario determinado. Cada sala de cine dispone de la cantidad maxima de asientos en ella, asi como las caractersiticas, "Sala 5D, Sala 3D, Sala Imax o Sala simple". Cada pelicula se dispone en distintos formatos que estan relacionados a las salas disponibles y sus caracteristicas, asi mismo las peliculas disponen de un nombre, idioma, edad establecida, etc. No se pueden colocar peliculas en horarios sobrepuestos. ***(Utiklizar Unix timestamp para las fechas para hacerlo mas simple)***

Asi mismo se debe disponer de un modulo donde los expectadores sean capaces de comprar entradas para las peliculas en cartelera, permitiendo elegir el asiento disponible (Asuma que los asientos son cubos con numeros pares en la cantidad total de asientos). El proceso termina con una entrada dibujada en pantalla (Escrita en html y SCSS). Ademas se deben a modo de cartelera desplegar las peliculas disponibles y las entradas disponibles, a modo de catalogo previo a seleccionar la pelicula.

Tambien se debe disponer de un modulo de caja, en donde el cine podra vender entradas en tiempo real para las peliculas en cartelera y los salas del cine. El proceso termina con las entradas dibujadas en pantalla (Escrita en html y SCSS)

Se debe proveer para la administración un modulo donde se permita deplegar la información de ventas de cada pelicula y sala de cine, permitiendo exhibir las ganacias y estadisticas.

Las preguntas a continuación seran las que aplican para este examen. Hay plazo hasta el martes a las 23:59 para entregarlo. Exito.

### Acotación 1

- Se debe usar SCSS, usando mixins, paletas, herencia, nested properties y archivos importados.
- Se prohibe usar bootstrap o un framework de diseño.
- Se debe utilizar GIT para entregar el proyecto, efectuando commits y push periodicos.

### Acotación 2

- Se debenutilizar modelos de datos.
- Utilizar servicios para mediar los datos.
- Se deben usar pipes para tratamiento de datos en HTML.
- Se deben utilizar directivas para otorgar funcionalidades a ciertas estructuras html.
- Se deben utilizar una estructura de proyectos definida y ordenada.
- Se utlizar Typescript.

### Acotación 3

- La aplicación final debe quedar dockerizada y entregada bajo una compilación Ahead on Time.
- Se evaluaran buenas practicas de codificación.
