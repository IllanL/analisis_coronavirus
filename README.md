# analisis_coronavirus
ANÁLISIS DIFUSIÓN CORONAVIRUS

Este repositorio contiene un script en Python dedicado a analizar la curva de la difusión del coronavirus entre la población española.

En base a dicho análisis se realizan proyecciones de la misma para predecir tanto el número de infectados totales como el número de muertos en los próximos 5 días.

Como fuente de los datos, a falta de una mejor, se toman los volcados en la siguiente página:

https://www.rtve.es/noticias/20200316/mapa-del-coronavirus-espana/2004681.shtml

Que recoge los datos que vuelca el Ministerio de Sanidad español. La hora de los contagios en el día de dicho informe puede variar, por lo que la diferencia entre un día y otro puede ser mayor o menor de 24 horas, pero a priori se asumirá que la hora del informe de todos los días es la misma, por falta de referencias.

El modelo que emplearemos no será más que una sencilla aproximación por una exponencial, no se emplea el modelo SIR. Se considera que, dada la fracción de la población infectada, los efectos de descontar a la población ya contagiada son de segundo orden y por lo tanto, en primera aproximación, pueden despreciarse sin pérdida de significancia en los resultados.
