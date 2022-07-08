# Base datos relacionales:
SQL server, MySQL, PostegSQL MariaDB, ORACLE, etc.

# Base de datos no relacionales:
Meshcash, MongoDB, casandra, etc.


# Video 2:
Edgar Frank "Ted" Codd creador del modelo relacional de datos para grande bancos de datos compartidos.

## Entidad:
Una **Entidad** es cualquier tipo de objero o concepto sobre el que se recoge informacion: cosa, persona, concepto abstracto o suceso. Por ejemplo: coches, casa, empleados, clientes, empresas, oficios, diseños de productos, conciertos, excursiones, etc. Las entidades se representan graficamente mediante rectangulos y su nombre aparece en el interior. Un nombre de entidad solo puede aparecer una vez en el esquema conceptual. Hay dos tipos de entidades: fuertes y debilies. Una entidad debil es una entidad cuya existencia depende de la excistencia depende de la existencia de otra entidad, Una entidad fuerte es una entidad que no es debil.

## Relacion
Es una correspondencia o asociacion entre dos o más entidades. Cada relacion tiene un nombre que describe su funcion. Las relaciones se presentan graficamente mediante rombos y su nombre aparece en el interior.

#### Tipos de relaciones:
Relaciones Binaria, Relaciones Ternaria, Relaciones n-arias, Relaciones dobles, Relacion reflexiva.

### Atributo:
Es una caracteristica de interes o un hecho sobre una entidad o sobre una relacion. Los atributos representan las propiedades basicas de las entidades y de las relaciones. Toda la informacion extensiva es protada por los atributos.
Graficamente, se representan mediante elipses que cuelgan de las entidades o relaciones a las que pertenecen. Cada atributo tiene un conjunto de valores asociados denominado dominio. Puede haber varios atributos definidos sobre un mismo dominio.

##### Tipos de Atributos:
- Atributo Compuesto: Este atributo esta compuesto por otros atributos, si tomamos el ejemplo anterior, el atributo fecha inicio estaria compuesto por otros tres atributos: dia, mes y año.
- Atributo Multiple: Pueden tomar varios valores, por ejemplo un Alumno puede tener varios telefonos, por lo tanto este seria un atributo multiple. Cabe destacar que debe tener una cardinalidad minima de 1 y maxima de n.
- Atributo Opcional: Lo son sin pueden tener valor nulo. Siguiendo el mismo ejemplo anterior si quisieramos que el telefono fuera un atributo no  obligatorio, podriamos marcar una cadinalidad minima de 0 y una maxima de n.

# Video 3:

### Definicion de los requerimientos del cliente
- Nos ayudara a comprender la problematica y saber por donde emperzar.
		        Analizar --> Modelar --> Programar

Diagrama: lenguaje UML es un conjunto de diagramas para modelizar POO.


#### Analisis - Modelado - Programacion

##### Analisis:
- Observar
- Leer
- Entender
##### Diseño:
- En papel
- UML (Caso de uso etc.
- Modelo Relacional (Base de datos)
##### Codificacion:
- Trasladar a codigo (Mediante un lenguaje)
- Desarrollo y programacion
