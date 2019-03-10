# Instrucciones a seguir para una correcta colaboración
Para practicar con un repositorio y hacer una contribución.

## 1.- Haciendo fork del repositorio

Seleccionamos el repositorio que queramos utilizar para añadir nuestra contribución, en este caso, podemos hacerlo con este repositorio mismo. 

Una vez que ya tengamos seleccionado un proyecto con el cual contribuir, nos dirigimos a la página de ese repositorio o proyecto y dale clic al ícono que aparece en la parte superior derecha que dice: **“Fork”**. A continuación puedes ver el icono en la siguiente imagen:

![Fork image](https://raw.githubusercontent.com/npm-udemy-course/users-course-npm/master/fork-repository-01.png)

En la siguiente imagen, podemos ver el proceso del fork:

![Fork image](https://raw.githubusercontent.com/npm-udemy-course/users-course-npm/master/fork-repository-02.png)

Una vez completado el fork tendremos una copia exacta del repositorio en nuestro propio perfil. Se trata de dos repositorios diferentes e independientes, pero que están "conectados". El nuestro es como si fuese una rama del anterior, aunque no lo sea.

![Fork image](https://raw.githubusercontent.com/npm-udemy-course/users-course-npm/master/fork-repository-03.png)

## 2.- Modificamos la copia para añadir nuestras aportaciones

Para poder aportar nuestras contribuciones tenemos que crear una rama que sea diferente a las ramas que existan en el repositorio original.

Por poner un ejemplo, podemos crear una rama con **nuestro usuario github> + "-contribution"** donde nuestro usuario podrías ser por ejemplo **mugan86**, quedando el nombre de la rama **mugan86-contribution**

Para crear la rama teniendo en cuenta eñ nombre del branch, hacemos lo siguiente:
```
git checkout -b mugan86-contribution
```
En este caso, simplemente es coger el fichero CONTRIBUTING.MD y añadir nuestro nombre-apellidos, enlace al repositorio de Github y si tenemos algún proyecto en el que recibamos colaboraciones, pues añadimos el enlace o enlaces en el caso de ser más de uno.
