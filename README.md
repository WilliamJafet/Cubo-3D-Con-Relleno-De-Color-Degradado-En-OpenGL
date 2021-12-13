# Cubo 3D Con Relleno De Color Degradado En OpenGL

La práctica consiste en realizar un programa donde se muestra un cubo 3D con relleno de color degradado.
Para ello primero se explica el código fuente del programa realizado.
En principio se realiza la importación de librerías necesarias para realizar la práctica.

![image](https://user-images.githubusercontent.com/72232712/145738805-06616454-e8d0-442b-8783-2078135e1f1b.png)

El siguiente bloque de código es la declaración de variables necesarias para realizar distintas acciones.

![image](https://user-images.githubusercontent.com/72232712/145738815-b022f18e-7d99-478c-89df-1365e9d528ff.png)

La función principal es importante debido a que es en esta parte donde empieza a ejecutarse el programa. En este bloque se realizan diversas configuraciones de la ventana para que se muestre al usuario.

![image](https://user-images.githubusercontent.com/72232712/145738819-5e0b6fe9-abe4-4dde-a46c-bb30cc14bfc8.png)

La función init es parte de la librería OpenGL y se utiliza para inicializar los componentes del Canvas, este es un componente en el que se va a realizar el pintado del objeto.

En la función reshape se realizan las configuraciones necesarias para que se pueda mostrar el objeto.

![image](https://user-images.githubusercontent.com/72232712/145738832-4e999b02-1092-42e1-8dda-7e0f18ac519d.png)

La función display es una de las funciones más importantes porque es aquí donde se programan las instrucciones para que el programa pinte lo que le estamos indicando.
Para esta práctica se pintan los distintos cuadros que forman el cubo, para ello se tiene en cuenta las coordenadas de cada vértice del cuadrado. En total se pintan seis cuadrados para formar el cubo.
Para indicar el color degradado, simplemente definimos dos colores diferentes en cada cara del cubo y con esto se muestra un color degradado.

![image](https://user-images.githubusercontent.com/72232712/145738845-a857bc37-defb-4094-b3d3-c2ea9caa72e8.png)

![image](https://user-images.githubusercontent.com/72232712/145738850-57bea50f-a414-4d30-a8e2-4751cf3b2727.png)

La última función por el momento no se realiza ninguna acción.

![image](https://user-images.githubusercontent.com/72232712/145738860-8cb1b5be-ceb1-4d87-a22d-4459f36c47a3.png)

Ahora que se ha explicado el código fuente, la siguiente parte es mostrar el resultado.
Como resultado hemos obtenido lo que se muestra en la siguiente figura. 

![image](https://user-images.githubusercontent.com/72232712/145738873-0786e982-6810-48a8-a563-01dc457eb0c6.png)

