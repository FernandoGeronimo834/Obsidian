## Aprendiendo SQL
### Comando **SELECT** :
- Seleccion de los campos (Columnas) para hacer el analisis o para sintetizar la tabla de origen.

### Clausulas:
- **FROM**: Tabla donde se almacena la informacion.
- **WHERE**: Especificar las condiciones.
- **GROUP BY**: Campos (columnas) de agrupacion.
- **ORDER BY**: Campos (columnas de ordenacion).


### Operadores Logicos:
- **AND**: Une varias condiciones que tienen que ser cumplidas paara obtener resultados.
- **OR**: Evalua dos o mas condiciones y obtienes resultados si una de ellas se cumple.
- **NOT**: Excluye un valor de la informacion a obtener.

### Funciones Agregadas:
- **AVG**: Promedio (average) de un campo (columna).
- **COUNT**: Recuento de valores de una columna.
- **DISTINCT**: Encontrar valores unicos.
- **SUM**: Suma de valores de una columna.
- **MAX**: Valor mas alto de una columna.
- **MIN**: Valor mas bajo de una columna.


## Aplicar tecnicas de Storytelling para convertir problemas de datos en historias.
Aprende a desagregar (extraer) un problema en una estructura logica.

## Estructura del problema
### Problema: 
**Algunos clientes contactan a soporte en exceso.**
- No los podemos identificar.
- No podemos prevenir este comportamiento.

### Solucion:
**Scrpt que ientifique y clasifique a los Top Offenders.**
- Enteder sus motivaciones - Calsificarlos
- Definir acciones para prevenir esta tendencia.

### Alcance
**LATAM con distincion por ciudades**.
- Clientes.
- Actualizacion mensual.


## Como estructurar un caso de negocio
Desglosar un problema de negocio en una hipotesis estructurada.
### Hipotesis / Storytelling
**QUÉ**
- Algunos clientes contactan a soporte en exceso.

**POR QUÉ**
- a) Motivaciones economicas.
- b) Preguntas
- c) Problemas tecnologicos
- d) Politica de empresa

**CÓMO**
1. Analisis cuantitativo.
2. Analisis cualitativo.
3. Matriz cuantitativa - cualitativa.
4. Definir acciones de prevencion.
5. Validacion.

## Analisis cuantitativo en un caso de negocio
Identificar las variables cuantitativas que nos ayudaran a resolver el ejercicio.

### Analisis Cuantitativo:
**DESCARGAR INFORMACION**
- Clientes >= 1 queja.
- Datos por un mes
- Madros por ciudad y mes


**IDENTIFICAR**
- Patrones de comportamiento
- Variables signficativas


     - Madurez (compras realizadas)
     - Quejas mensuales (Contactos)
     - Compras mensuales
     - Gasto mensual
     - Credito y dinero devuelto
     - Margen operativo neto


**DEFINIR**
- Segmentacion segun rentabilidad
- Theshold (limite) Top offender
- Threshold para cada categoria


- Clientes regulares (9 compras o menos).
- Clientes bronce (10-19 viajes).
- Clientes plata (20-39 viajes).
- Cliente dorados (40 viajes o más).



### Que es mineria de Texto?
### Como usarla para obtener informacion adicional?
Explorar nueva informacion a partir del texto.

#### Motivos de contacto
- Regular: 
    - Tarifa de devolucion
    - Tasa de envio
    - Como embalar para devolucion

- Bronce:
	- Tarifa de devolucion
	- Tasa de envio
	- Estado del producto

- Plata:
	- Tarifa de devolucion
	- Facturas
	- Estado del producto

- Oro:
	- Facturas
	- Estado del producto
	- Log in



### Variacion de comportamientos a partir de la geolocalizacion
Entender la relevancion de hacer uns distincion geografica para el estudio y validarla en el caso de negocio analizado.


### Tomar decisiones segun los resultados del analisis:
Convertir la informacion obtenida del analisis en una estrategia o toma de decisiones.


### Acciones derivadas del analisis:
**Algoritmos usados**
1. Mineria de datos para clasificacion de motivos de contacto.
2. Correlaciones y patrones de comportamiento.
3. Arboles de decision y teoria de juegos para predecir y tomar decisiones.
4. Validacion con bayesianos y MCMC.

**Acciones**
1. Taggear a los Top Offenders identificados mensualmente.
2. Advertilos.
3. Llamar usuarios.
4. Bloquear usuarios.
5. Validacion con A/B Test.


**Disminuyeron las quejas en un 30% a nivel de LatAm**