# Grupo 1 .- Manipulacion de datos 

La manipulacion de datos incluye: modificaciones, filtrado, limpieza, seleccion y eliminaciones de dataframes.

Las funciones que usaremos seran del paquete dplyr:

```
select() : Seleccionar nombres de las columnas. --> select(dataframe, columna1, columna2, ... columnax)
filter() : Filtrar filas por una condicion especifica, apartir de la columna. --> filter(dataframe, columna1 == "condicion")
mutate() : Modificar o agregar columnas. --> mutate(dataframe, columna1 = "condicion")
group_by() : Agrupar informacion de acuerdo a un(as) columna(s) seleccionada(s). 
if_else() : Condicional. --> if_else(dataframe, codicion, si se acepta entonces, si se rechaza entonces)
arrange() : Acomodar los resultados, default de menor a mayor.
count(): Cuenta los valores de acuerdo a una variable.
left_join() : Unir dos dataframe con base en una misma columna en comun. --> left_join(dataframe1, dataframe2, by  = "Columna en comun, mismo nombre")
n_distinct() : Cuenta las filas unicas.
distinct() : Muestra las filas duplicadas.
```

La funcion empleada del paquete reshape2:

```
melt(): Modificacion el formato de un dataframe.
```

A continuacion te presentamos 3 ejemplos:

## Goretty - Pinturas

Datos: [Ejercicio_pronostico.csv](https://github.com/R-Ladies-Morelia/limpieza_datos/blob/51be679427e00a06f5bbb98798ca192a9cdb9139/Ejercicio_pronostico.csv)

Ejercicio: [pronostico.R](https://github.com/R-Ladies-Morelia/limpieza_datos/blob/15004be493557153ffd799a572a5b3ef925507bd/pronostico.R)

## Maria de los Angeles - Aguacata

Datos: [avocado.csv](https://github.com/R-Ladies-Morelia/Aguacate/blob/73b9319b445fdad7471595fa6d67ce84d12d868a/avocado.csv)

Ejercicio: [Aguacate_ejercicio.R](https://github.com/R-Ladies-Morelia/Aguacate/blob/73b9319b445fdad7471595fa6d67ce84d12d868a/Aguacate_ejercicio.R)

## Evelia Coss - Marvel vs DC comics

Datos: [dataframes.tsv](https://github.com/EveliaCoss/Rladies-Morelia/tree/main/G1_AnalisisDeDatos/Parte1_Marvel_vs_DCcomics/data)

Ejecicio :  [Marvel vs DC comics](https://github.com/EveliaCoss/Rladies-Morelia/tree/main/G1_AnalisisDeDatos/Parte1_Marvel_vs_DCcomics)



