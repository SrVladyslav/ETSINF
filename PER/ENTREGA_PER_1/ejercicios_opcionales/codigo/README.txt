Modificaciones respecto al c�digo original:

> pcaEXPERIMENT.m correspone a pca+knn-exp.m
> pcaTESTING.m corresponde a pca+knn-eva.m 

Hice estas modifiaciones porque el script original no me lo reconoc�a en Windows, 
incluso poniendo el PATH al binario de Octave. Por ello el script lo transforme en una funci�n 
la cual la llame desde Octave, previamente cargando los datasets con 'load()'. Por lo dem�s, no
han habido m�s cambios.

En el pcaEXPERIMENT y pcaTESTING est�n las implementaciones de c�digo para el uso con y sin Wilson, 
solo hay que descomentar el c�digo necesario.

En el KNN.m est�n comentadas las distintas distancias, para usarlas, hay que descomentar la necesaria. 