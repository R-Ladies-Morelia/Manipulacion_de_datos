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


## Maria de los Angeles - Aguacata


## Evelia Coss - Marvel vs DC comics

Ejecicio :  [Marvel vs DC comics](https://github.com/EveliaCoss/Rladies-Morelia/tree/main/G1_AnalisisDeDatos/Parte1_Marvel_vs_DCcomics)

Datos: [dataframes](https://github.com/EveliaCoss/Rladies-Morelia/tree/main/G1_AnalisisDeDatos/Parte1_Marvel_vs_DCcomics/data)



