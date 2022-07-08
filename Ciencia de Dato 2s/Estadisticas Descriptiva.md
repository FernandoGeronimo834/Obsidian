# Tipos de datos:
Los tipos de datos que consideramos son los siguientes:

**Datos de tipo atributo, o cualitativos:** Expresan una cualidad del individuo.

**Datos ordinales:** Similares a los cualitativos, con la unica diferencia de que se puede ordenar de manera natural. Por ejemplo, las calificaciones en un control (suspenso, aprobado, notable, sobresaliente).

**Datos cuantitativos:** Se refieren a medidas, tales comoe dades, longitudes, etc.


  Nota: 
  Datos Cualitativos: Frencuencia con la que aparecen determinado valor.
  Datos Cuantativos: Se le pueden aplicar, medidas estadisticas como la media, la desviacion tipica, el minimo, el maximos, la mediana, etc.
  
# Trabajando con **Datos Cualitativos**

## Descripcion de datos cualitativos:
Los datos cualitativos corresponden a observaciones sobre cualidades de un objeto o individuo.
Suelen codificarse por mediod e palabras, pero tambien se pueden usar numeros que jueguen el papel de etiquetas.

### Que son los datos cualitativos?
Los datos cualitativos son aquellos que pueden ser iguales o diferentes, pero que no admiten ningun otro tipo de comparacio significativa.

Es decir, que no tenga ningun sentido preguntarse si uno es mas grande que otro, ni egectuar operaciones aritmeticas con ellos, aunque esten representados por numeros.

Por lo tanto, un mismo conjunto de datos puede ser cualitativo o de otro tipo, según el analisis que vayamos a hacer de él.

> Ejemplo:
> Si hemos anotado durante unos años los dias de la semana en los que ha llovido y queremos contar cuántas veces ha ocurrido el lunes, cuántas en martes, etc., esta lista de nombres (o números) serán de datos cualitativos. Si, en cambio, queremos estudiar cómo se comportan los dias de llubua según avanza la semana, y por lo tanto el orden de los días es relevante, serán datos ordinales.

**Variable cualitativa:** Lista de pbservaciones de un tipo de datos cualitativos sobre un conjunto concreto de objetos.

**Niveles:** Diferentes valores que pueden tomar estos datos, Por ejemplo, los dos niveles de una variable Sexo serian M (macho) y H (Hembra), o sinónimos.

### Estudio de Frecuencias
Dada una variable cualitativa, para cada uno de sus niveles podemos contar cuántos datos hay en ese nivel (frecuencia absoluta) y qué fraccion del total representan (frecuencia relativa).

> **Ejemplo**
>Supongamos que tenemos un tipo de datos cualitativos con niveles 
> $$l_1,l_2,\cdots,l_k$$ 
Efectuamos $n$ observaciones de este tipo de datos, y denotamos por 
> $$x_1,x_2,\cdots,x_n$$
los resultados que obtenemos con 
> $$x_j\in\{l_1, l_2,\cdots, l_k\}$$
Estas observaciones forman una variable cualitativa

Con estas notaciones:

La <l class="definition">frecuencia absoluta</l>, $n_j$, del nivel $l_j$ en esta variable cualitativa es el número de observaciones en las que $x_i$ toma el valor $l_j$.

La <l class="definition">frecuencia relativa</l> del nivel $l_j$ en esta variable cualitativa es la fracción 
$$f_j = \frac{n_j}{n}$$

Es decir, la frecuencia relativa del nivel $l_j$ es la fracción (en tanto por uno) de observaciones que corresponden a este nivel. 

La <l class="definition">moda</l> de esta variable cualitativa es su nivel, o niveles, de mayor frecuencia (absoluta o relativa).[[vertopal.com_Tema6]]

El resultado de una función `table()` es un objeto de datos de un tipo
nuevo: una tabla de contingencia, una `table` en el argot de R.
