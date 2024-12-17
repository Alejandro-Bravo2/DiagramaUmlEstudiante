# DiagramaUmlEstudiante


## Identificación de la Actividad
- **ID de la Actividad:** Práctica Diagrama Uml de Clase
- **Módulo:** PROG
- **Unidad de Trabajo:** UD 5 Diagrama UML
- **Fecha de Creación:** 17/12/2024
- **Fecha de Entrega:** 
- **Alumno(s):** 
  - **Nombre y Apellidos:** Alejandro Bravo Calderón
  - **Correo electrónico:** abracal@g.educaand.es
  - **Iniciales del Alumno/Grupo:** abc

## Descripción de la Actividad
Se ha desarrollado la actividad usando listas para realizar la actividad.

## Desarrollo de la Actividad
### Descripción del Desarrollo
Se ha realizado la actividad intentando minimizar el código y optimizarlo, usando list compresion y formateadores.


## Conclusiones
Me ha encantando aprender a usar list compresion.


1. Interepreta el significado del diagrama de clases
  1. Relación entre clases. Significdo, type y multiplicidad.
   En un curso en concreto puede haber 1 o más estudiantes.
     En curso el nombre es una string ya que serán nombres y sin importar si es numero o letra. Codigo es una string pero realmente podría llegar a ser un entero ya que solamente lo usaremos para identificar de forma única ese curso.
     En estudiante el nombre es string ya que serán nombres y sin importar si es numero o letra. Dni es una string ya que contendrá un conjunto de números y letras.
    Multiplicidad: para un curso en concreto puede haber como mínimo 1 estudiante y como máximo n estudiantes y para un estudiante en concreto podrá estar como mínimo en 1 curso y como máximo en 1 curso. 
  2. Elementos de la clase. Tipos y proposito.
     Los atributos de ambas clases son string y los metodos lo que hacen es:
     agregaralumno = lo que hace es añadir alumno a una lista con los nombres de los alumnos que participan a ese curso
     inscribirse = lo que hace inscribirse es añadir el nombre del alumno en la lista del curso deseado.
     mostrarInscrito = lo que hace es mostrar el curso en el que está inscrito el alumno.
  3. Significado del método agregarAlumno:
     agregaralumno: añadirá el nombre del alumno a la lista de alumnado del curso especifico.
2. Generación de código a partir del diagrama de clases
   1. Crea clases
   2. Relaciones
   3. Crea main para probar el sistema
