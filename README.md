# EDA-Vinilos
**INTRODUCCIÓN**

La industria musical ha sido testigo, a lo largo de los años, de diversos cambios en el formato de sus productos. Pero el formato que siempre parece permanecer inquebrantable es el vinilo. Desde su primera aparición, a mediados de la década de los años 50 del siglo pasado, es un formato apreciado y románticamente casi considerado como de culto.

Para los amantes de la música, siempre ha estado más o menos clara la elección, pero veamos si somos capaces de analizar a partir de los datos de lanzamiento de productos musicales en diversos formatos a lo largo de más de un siglo, si es cierto que independientemente de las modas y de la aparición de otros formatos, el vinilo no ha dejado de producirse ni de comprarse. Y para ello nos vamos a servir de un Análisis Exploratorio de Datos (o EDA, por sus siglas en inglés) usando Python.

**FUENTE DE LOS DATOS**

La plataforma *DISCOGS* alberga información y bases de datos acerca de la música, e intenta recopilar toda la información acerca de los discos comerciales, promocionales, y discos no oficiales, tal y como ellos mismos se definen. Precisamente de esta plataforma, hemos obtenido una riquísima base de datos, con más de 17 millones de registros, sobre todos los discos publicados desde 1860 en adelante, en función de su año de publicación, país, género y formato. 

**Desarrollo del trabajo de análisis**

+ En primer lugar, hemos llevado a cabo una limpieza de los datos, en cuanto a valores faltantes, valores con comas o espacios en blanco, y convirtiendo los tipos de datos allá donde fuera necesario a fin de poder analizarlos correctamente.

+ A continuación, hemos agrupado los datos en función de lo que queríamos estudiar comparándolos entre sí y aplicando diversos métodos de correlación y comparación.

+ Por último, hemos implementado las gráficas necesarias para una visualización óptima del análisis.


Dada la enorme cantidad de registros que tenía esta base de datos, y teniendo en cuenta los fines de este EDA, se decidió limitar el estudio a los 5 países con mayor producción musical, los 5 estilos musicales más producidos y los 5 formatos más utilizados. De esta forma, analizamos los datos desde un punto de vista más macro hasta nuestro objetivo, que es confirmar la hipótesis de un formato en particular.

**CONCLUSIONES**

Después de bucear por los datos y sacar la foto en algunos de los aspectos más generales, nos centramos en el formato de nuestra hipótesis y vemos claramente que, a pesar de que los diversos formatos fluctúan sea por modas o por variaciones en su aparición y descubrimiento, el vinilo se mantiene a lo largo del tiempo entre los formatos más publicados. Por lo que podríamos decir que **nuestra hipótesis queda confirmada tras analizar los datos**.
