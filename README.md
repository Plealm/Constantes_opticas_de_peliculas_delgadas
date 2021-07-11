# Constantes ópticas para una pelicula delgada

Este repositorio fue creado para guardar los códigos realizados en python y MatLab para el desarrollo del informe 
"Determinación de constantes ópticas  para una película delgada por el método de Swanepoel". Existen dos partes:

## Códigos
En la carpeta codigos se encuentran 6 codigos python que se usaron para el procedimiento de los datos.

1.1  datos.py En este programa se toman los datos que fueron dados por el profesor y se encuentran los maximos 
y minimos relativos de la transmitancias.

1.2 TM.py Se encarga de realizar un ajuste sigmoidal de los valores maximos encontrados, aunque este ajuste es excelente
se decidio no tomarlo para el informe por su tendencia constante al final.

1.3 Tm.py Se encarga de realizar un ajuste sigmoidal de los valores minimos encontrados, aunque este ajuste es excelente
se decidio no tomarlo para el informe por su tendencia constante al final.

1.4 Envolentes.py  se juntan las longitudes de onda de maximos y minimos y se calcula segun las regresiones
encontradas anteriormente

1.5  regresioncauchy.py  Se realiza la regresión según la función de cauchy entre los n y las longitudes de onda

1.6 Tauc.py se usa para calcular la energía de banda por el método de diagrama de Tauc

1.7 espectro.m es el código de MatLab empleado para hallar las envolventes del espectro de transmisión de la película delgada, además que determina los valores máximos y mínimos locales de dicho espectro, i.e., los T_M y T_m que fueron usados en el informe y en el cálculo de las demás constantes ópticas.

1.8 wavelenht.data es un array de los datos de longitud de onda proporcionados, los cuales son usados en el código anterior.

1.9 transmitancia.data es un array de los datos de transmitancia proporcionados de la película delgada, los cuales también se usan en el código de MatLab. 



## Imagenes
 En Imagenes se encuentran las imagenes que se desarrollaron por medio de los programas contenidos en códigos.
