
Tenemos los 4 ingresos fundamentales de las Casen agrupados como tablas de contingencia,
bajo alfabetismo, sexo, etnia(o inmigración) y comuna,
tanto para personas como para hogares:

El código en GitHub está en:

ttcc_ing_etnia_migra_per.Rmd

/ingresos_migra/ingresos_por_migra_con_codigos

El la base de datos en GitHub está en:

/ingresos_etnia/ingresos_por_etnia_con_codigos

ttcc_ing_etnia_migra_hog.Rmd (pendiente)

Que en internet estan en:

https://rpubs.com/dataintelligence/ttcc_etnia_migra_hog (pendiente)

https://rpubs.com/dataintelligence/ttcc_etnia_migra_per 

![Ingresos](Low-Income-Children.jpg)

OBSERVACIONES IMPORTANTES

1 En cálculos anteriores se han sobreestimado los ingresos, ignorando los valores 0,
debido al desconocimiento técnico tanto de R como del Excel. El promedio del ingreso DEBE considerar los ingresos ceros dentro de las categorias
sexo, alfabetismo y etnia.

2 El coeficiente de gini no tiene sentido de calcular pues se aplica sobre una muestra.

3 La frecuencia es la suma de los factores de expansión de las personas encuestadas.

4 Se debe aplicar el factor de expansión a los ingresos. Para ello la metodología será
multiplicar el valor de los 4 ingresos de los encuestados de la tabla construída por el factor de expansión
expansión del encuestado y dividirlo por el número de habitantes de la comuna.






