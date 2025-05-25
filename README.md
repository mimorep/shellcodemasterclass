# Recursos de la masterclass de _"Shellcoding malware analysis"_

En este repositorio, podreís encontrar, todos los recursos/muestras empleados durante la masterclass. Si estas ahora mismo en ella y quieres seguirla puedes descargar las muestras en un entorno seguro y replicar lo que vemos en clase. Además os he dejado alguna muestra más a modo de reto (ya que no creo que me de tiempo de verlas en la clase), para que las vayaís haciendo.

## ¡¡¡Advertencia!!!

Todas las muestras que vas a ver aqui, son **MALWARE**, (ninguna de ellas te van a hacer nada, ya que estan 100% desarrolladas por mi) por lo que asegurate de tratarlas como tal y no las ejecutes en tu propio ordenador.

La contraseña de todos los zip es:

```
infected
```

## Ejercicios

### Muestra 1
Es el ejercicio principal que hemos visto en clase, por lo que parece es un malware, el cual parece lanzar un shellcode ¿Puedes analizarlo, extraer el shellcode y ver que es lo que realmente hace?

### Muestra 2
Este binario aunque parecido al anterior, parece emplear otra técnica diferente para la inyección, con el fin de evadir ser detectado. Analizalo e intenta extraer su shellcode, para saber que es lo que hace realmente.

### Muestra 3
El reto principal en este caso, es tratar de extraer y saber que shellcode esta lanzando este programa, si te quedas atascado puedes ejecutarlo y te llevarás una sorpresa, viendo que es realmetne lo que esta lanzando este shellcode.

Para este reto te recomiendo una vez logres extraer el shellcode, emplear herramientas tales como shellcode2exe:

```
https://github.com/accidentalrebel/shcode2exe
```

Ya que si no su análisis se complica, el principal objetivo de este reto es ser capaz de reconstruir la muestra, y ver la infinidad de posibilidades de inyección que se pueden lograr.


## Dudas
En caso de tener alguna duda, os recomiendo abrir una issue en el repo, de esta forma quedará publicada y así más gente podrá ver la resolución en caso de tener la misma duda.
