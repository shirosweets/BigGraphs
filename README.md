# GrafosGrandes

# Grafos grandes para testear velocidad y uso de memoria.
No es necesario que ustedes obtengan estos mismos tiempos pero si deben poder hacer 1100 Greedys con reordenes por bloques en 15 minutos para cada uno de ellos. (los tiempos que se detallan abajo son con 3000 reordenes, con unas maquinas de famaf de hace algun tiempo).

## 

> Este grafo tiene solo 3080 vertices pero 4 millones de lados (4303060 para ser exacto)

Es un grafo que les puede demorar mucho a pesar de la poca cantidad de vertices si no programan bien algunas cosas.
Greedy con orden natural: 339 colores
Greedy con WelshPowell: 264 colores
642 reordenes por bloques lo disminuye a 112.
Tiempo total para 3102 Greedys: 1m39.539s

## `n=2210104_m=8807410`

> Numero de vertices=2210104. Numero de lados=8807410

Greedy con orden natural: 5 colores
Greedy con WelshPowell: 2099 colores
Con algunos reordenes el coloreo se puede bajar a 4 colores.
Tiempo total para 3102 Greedys: 6m15.192s
Este grafo es importante para el manejo de memoria: si no la usan bien, puede provocar stack overflow.

## 

> Grafo comprimido, grande. Welsh Powell va a dar mucho más del X(G)

Este grafo es el "antecesor" del BxB1100... de arriba. Si les falla con el BxB1100... pero anda bien con este, entonces es muy plausible que tengan un stack overflow problem. Si los dos fallan entonces es mas plasusible que el error este en otro lado.

##

> Un grafo aleatorio con 1999999 vertices y 10123123 lados
> `R1999999_10123123_1`

ESTE GRAFO ES MUY IMPORTANTE:
Varios grupos podian trabajar con otros grafos grandes sin problemas, pero tenian un error especifico en Greedy que hacia que con este (y otros grafos similares) demorasen HORAS para hacer menos de 10 Greedys.
Sin embargo, si Greedy esta bien programado, deberia demorar muy pocos minutos.

## Numero de vertices=221651. Numero de lados=12528006

> `Gf12345_12111222_457_15`

Greedy con orden natural: 600 colores
Greedy con WelshPowell: 581 colores
3000 reordenes por bloque de colores lo baja a 523.
Tiempo total: 6m4.944s

## 

## bxb777_999_12

> Grafo comprimido, grande. Welsh Powell va a dar mucho mas del X(G)

Este grafo es el "antecesor" del BxB1100... de arriba. Si les falla con el BxB1100... pero anda bien con este, entonces es muy plausible que tengan un stack overflow problem. Si los dos fallan entonces es más plasusible que el error este en otro lado.

## 