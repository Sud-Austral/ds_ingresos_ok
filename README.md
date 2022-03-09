
Tenemos los 4 ingresos fundamentales de las Casen agrupados como tablas de contingencia,
bajo alfabetismo, sexo, etnia(o inmigración) y comuna,
tanto para personas como para hogares:

# El código

El código está en:\
ttcc_ing_etnia_migra_per.Rmd

# El producto

## Por personas

ingresos_migra/ingresos_por_migra_con_codigos\
ingresos_etnia/ingresos_por_etnia_con_codigos

## Por hogares

ttcc_ing_etnia_migra_hog.Rmd (pendiente)

Sólo es necesario reemplazar las mismas variables que consideran a las personas por las que consideran hogares.

![Ingresos](Low-Income-Children.jpg)

## Un análisis metodológico

1 En los cálculos de las ttcc se han ignorando los valores 0, haciéndonos sospechar que se han sobreestimado los ingresos,


El promedio del ingreso DEBE considerar los ingresos ceros dentro de las categorias
sexo, alfabetismo y etnia.

2 El coeficiente de gini no tiene sentido de calcular pues se aplica sobre una muestra.

3 La frecuencia es la suma de los factores de expansión de las personas encuestadas.

4 Se debe aplicar el factor de expansión a los ingresos. Para ello la metodología será
multiplicar el valor de los 4 ingresos de los encuestados de la tabla construída por el factor de expansión
expansión del encuestado y dividirlo por el número de habitantes de la comuna.






