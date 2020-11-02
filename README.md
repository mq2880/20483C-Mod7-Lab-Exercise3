# Module 7: Accessing a Database

## Lab: Retrieving and Modifying Grade Data

1. **Nombres y apellidos:** Francisco Javier Moreno QUevedo
2. **Fecha:** 02/11/2020
3. **Resumen del Ejercicio:**  Crear clases parciales y añadirles validaciones
4. **Dificultad o problemas presentados y como se resolvieron:** Ninguna

- Ejercicio 3: Extending the Entity Data Model to Validate Data

  - Creamos la clase parcial Teacher en el proyecto dataModel
    - Esta clase controla el numero de alumnos maximos y si se alcanza lanza una excepcion
    - Tambien conttrola que el alumno no este asociado a otro profesor
  - Creamos la clase parcial Grade en el proyecto dataModel
    - Controla que la fecha fecha de asignacion no sea superior a hoy
    - Controla que las notas no sean superiores o inferiores a las permitidas
  
