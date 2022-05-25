# Examen segundo parcial POO

# Proyecto
Un estudio de arquitectura desea crear una base de datos para gestionar sus proyectos. Se dan las siguientes especificaciones: 
1. Cada proyecto tiene un código y un nombre. Un proyecto tiene uno y solo un jefe de proyecto y un jefe de proyecto sólo puede estar involucrado en un proyecto o en ninguno. Y tambien tiene arquitectos que trabajan en este proyecto. Ademas los proyectos tienen un estado (nuevo, en proceso, terminado, cancelado).
2. De cada jefe de proyecto y de los arquitectos se desean recoger sus datos personales (código, nombre, dirección y teléfono). Todos se identifica por un código. 
3. Un proyecto se compone de una serie de planos, pero éstos se quieren guardar de modo independiente al proyecto. Es decir, si en un momento dado se dejara de trabajar en un proyecto, se desea mantener la información de los planos asociados. 
4. De los planos se desea guardar su número de identificación, la fecha de entrega, los arquitectos que trabajan en él. 


# Instrucciones
- Realiza un diagrama de clases y añade los métodos necesarios para realizar la creacion de jefes, arquitectos, proyectos y planos, ademas de poder cambiar el estado de los proyectos
- Codifica en python el diagrama de clases que diseñaste
- Deberas subir al repositorio el diagrama de clases y el código que prueba que funciona el sistema.
  - Deberas probar que:
    - Registar Jefes, Arquitectos,  Proyectos y planos
    - Modificar el estado de los proyectos.

**NOTA: Toda la implementación puede ser en consola, no es necesario usar ni base de datos ni interfaz gráfica.**
**Sí usas BD e interfaz grafica podrias sumar puntos. Pero lo importante es el diagrama y que los metodos funcionen**
**Recuerda que necesitaras más que solo los métodos principales que se pide para probar**
