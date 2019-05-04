![logo_completo](https://user-images.githubusercontent.com/8356912/57099764-d4328480-6ce2-11e9-8313-c1192cdbdb35.jpg)

# Prueba de programación para Busescool 

Bienvenidos a Busescool.

En este repositorio se encuentra una prueba que pretende demostrar su conocimiento en desarrollo de software.

## Instrucciones 

La prueba consiste en el desarrollo (front y back-end) de una sencilla aplicación Web, utilizando valores del día a día de la base de datos de Busescool.

En este repositorio encontrara el archivo `/database/students.json` el cual contiene pares `key`-`value` de tipo `string`, representando información personal sobre estudiantes que operan con Busescool. Cada entrada de la base de datos esta organizada de la siguiente manera:

```
//  Key     :                   Data
"studentID" : "studentId; fullName; studentGroup; amBus; pmBus; names; lastNames; gender"  
```

### Tareas a desarrollar
1. Exhibir la información de los estudiantes en la tabla principal (con id: `students_table`) del archivo `main.html`. Las entradas deben poder ordenarse por id (De menor a mayor) o por apellido (alfabeticamente), una vez el usuario de click en la casilla de titulo de las columnas `Id` o `Apellidos`.
![Screen Shot 2019-04-30 at 12 29 30 AM](https://user-images.githubusercontent.com/8356912/56942221-0a9fb200-6adf-11e9-9dd6-c75aade952ba.png)

2. Permitir al usuario filtrar las entradas exhibidas en la tabla principal por sexo (masculino, femenino o ambos), ordenando los resultados como se explico en el punto 1.
![Screen Shot 2019-04-30 at 12 23 52 AM](https://user-images.githubusercontent.com/8356912/56942115-6ddd1480-6ade-11e9-84b9-771712524e1a.png)

Se recomienda utilizar el script `/scripts/main.js` como archivo principal para contener el codigo a desarrollar, Sin embargo el desarrollador podra crear cuantos scripts, modulos, clases y funciones como encuentre necesario.

### Bonus 
Configurar la herramienta de autocompletar, también conocido como buscador, para facilitar la búsqueda de estudiantes particulares.

En dado caso que el usuario seleccione un estudiante especifico en el buscador, la tabla principal deberá actualizarse para mostrar únicamente este estudiante, y el botón de eliminar filtros (paso 2) deberá revertir este comportamiento.

![Screen Shot 2019-04-30 at 12 39 51 AM](https://user-images.githubusercontent.com/8356912/56942468-864e2e80-6ae0-11e9-82c4-09d49e416c75.png)


Información sobre este paso se encuentra [aquí] (https://materializecss.com/autocomplete.html)

---------------------

# Recomendaciones 
1. Programar en el idioma ingles.
2. Utilizar git apropiadamente en el desarrollo.
3. Seguir las guias de programación de [google](https://google.github.io/styleguide/jsguide.html).
4. Optimizar memoria, complejidad de algoritmos, y tiempo de operación.
5. Es valido utilizar recursos de [JQuery](https://jquery.com/) y [Materialize](https://materializecss.com/). Aunque no son necesarios.
