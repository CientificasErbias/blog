---
title: "Música y física: dando la nota"
header:
  image: /assets/images/CientificasErbias_reducida.jpg
  caption: "Créditos: [**@Chir_ii**](https://www.instagram.com/chir_ii/?hl=en)"
  og_image: /assets/images/posts/2021-04-02-MusicaYFisicaDandoLaNota/cover.jpg 
categories:
  - Lo cotidiano es ciencia
comments: true
author_profile: true
tags:
  - Física
  - Música
date: 2021-04-02 15:30:00 +0200
--- 

El ser humano conoce la música desde el origen de los tiempos. Da igual la cultura, la religión o el lugar donde nos encontremos los humanos, la música estará o estuvo presente. En la antigüedad usábamos instrumentos bastante rudimentarios y hoy en día podemos crear nuevas canciones con nuestros ordenadores sin la necesidad de ningún instrumento. Podemos disfrutar de la música sin saber tocar un instrumento, cantar una letra sin conocer su significado y ponernos tristes o contentos cuando escuchamos una canción que nos hace recordar el pasado. La música es universal y esconde entre sus melodías una ingente cantidad de matemáticas y de física. Hoy, la música y la física van de la mano en este post.

¿Por qué un tambor emite sonido cuando lo golpeamos? ¿Por qué las cuerdas de un violín suenan al hacerlas vibrar? ¿Por qué dos notas suenan distintas? Hay muchas preguntas que se nos pasan por la cabeza, pero empecemos por algo más básico: ¿qué tiene que ver la música con la física? La música la percibimos como un sonido, es decir, ondas que se propagan al chocar unas moléculas de aire contra otras transmitiendo una vibración. Si hablamos de ondas, la física entra en juego.
 
Cuando escuchamos un sonido, generalmente lo podemos clasificar por cómo de alto o bajo lo oímos y si es grave o agudo. Asociando esto con un lenguaje un poco más técnico, el sonido es una onda que se propaga por el aire, si el volumen es alto/bajo significa que la amplitud de la onda es grande/pequeña, mientras que si es agudo/grave diremos que la frecuencia es alta/baja. Por ejemplo, un sonido de 18 <a style="color:lightslategray" href="https://cientificaserbias.github.io/blog/lo%20cotidiano%20es%20ciencia/MusicaYFisicaDandoLaNota/index.html#target">kHz</a> de frecuencia lo percibimos como algo muy agudo, mientras que un sonido de 200 Hz es muy grave. Cada sonido tiene una frecuencia asociada, por lo que también cada nota musical tiene una frecuencia que podríamos decir que es su carné de identidad. Por ejemplo, el La4 tiene una frecuencia de 440 Hz mientras que el Do4 tiene una frecuencia de 262 Hz, es decir, que la amplitud de La varía más rápidamente que la de Do como se puede ver en la siguiente figura. Además, vemos que para la misma <a style="color:lightslategray" href="https://cientificaserbias.github.io/blog/lo%20cotidiano%20es%20ciencia/MusicaYFisicaDandoLaNota/index.html#target">frecuencia</a>, el máximo y el mínimo de la <a style="color:lightslategray" href="https://cientificaserbias.github.io/blog/lo%20cotidiano%20es%20ciencia/MusicaYFisicaDandoLaNota/index.html#target">amplitud</a> pueden ser distintos, lo que significa que podemos escuchar la misma nota con más o menos volumen.

<figure>
	<img src="{{ site.url }}{{ site.baseurl }}/assets/images/posts/2021-04-02-MusicaYFisicaDandoLaNota/ondas.png"/>
</figure>

Cuando tocamos un instrumento hacemos que el aire vibre y estas oscilaciones llegan a nuestros oídos y las percibimos como un sonido. Pero, ¿por qué las distintas notas no suenan igual? Vayamos al paso inicial, entendamos cómo vibran las cuerdas de un instrumento. Cuando tocamos con nuestro dedo la cuerda de una guitarra o el martillo percute en las cuerdas de un piano, estas empiezan a vibrar y emiten un sonido, que como ya sabemos tendrá una frecuencia y una amplitud asociadas. La amplitud de la onda dependerá de cómo de fuerte toquemos esa cuerda, mientras que la frecuencia está determinada por las características de la cuerda, en particular por su longitud, cómo de tensa esté y cómo de densa sea, es decir, cuánta masa tiene por cada unidad de longitud. A esta frecuencia la llamaremos frecuencia fundamental. Como a los físicos les gusta poner a las matemáticas siempre de por medio, escribamos la ecuación que nos da la frecuencia a la que vibrará una cuerda de longitud L, tensión T y densidad <font face="Symbol">m</font>:


<figure>
	<img src="{{ site.url }}{{ site.baseurl }}/assets/images/posts/2021-04-02-MusicaYFisicaDandoLaNota/eq1.jpg"/>
</figure>

Lo que esta ecuación nos dice es:
1. Que cuanto más densa sea la cuerda su frecuencia será menor (más grave).
2. Que cuanto más tensa esté la cuerda su frecuencia será mayor (más agudo).
3. Que cuanto más larga sea la cuerda menor será su frecuencia (más grave).

¿Cómo podemos comprobar si todo esto es cierto o no? Pensemos en un instrumento que nos es familiar más o menos a todos. Una guitarra tiene 6 cuerdas, todas de la misma longitud. Siendo un poco observadores nos damos cuenta de que las cuerdas están hechas de dos materiales distintos, unas son de nylon (1, 2 y 3 en la imagen) y otras están recubiertas de metal (4, 5 y 6) y tienen distintos grosores, la cuerda 6 es la más gruesa y la 1 es la más fina. Estas diferencias hacen que la densidad de las cuerdas sean distintas, siendo la cuerda 6 la más densa, y por tanto más grave, y la cuerda 1 la menos densa y la que suena más agudo. ¡Hemos comprobado el punto 1 de nuestra ecuación!

<figure>
	<img src="{{ site.url }}{{ site.baseurl }}/assets/images/posts/2021-04-02-MusicaYFisicaDandoLaNota/guitarra.png"/>
</figure>

Cuando un instrumento está desafinado, simplemente significa que el sonido tiene una frecuencia distinta a la que debería tener, por lo que hay que hallar la frecuencia correcta. De vez en cuando podemos ver como los guitarristas afinan sus guitarras moviendo las clavijas de la parte superior de la guitarra tensando o destensando las cuerdas. En otras palabras, los guitarristas cambian la tensión de las cuerdas para que la frecuencia de vibración sea la de la nota adecuada.

Bueno, solo nos queda por comprobar el punto número 3 y la verdad que parece complicado cambiar la longitud de las cuerdas de la guitarra. Si bien es cierto que no podemos hacer las cuerdas más largas, sí que tenemos un truco para hacer que efectivamente sean más cortas: presionarlas con nuestros dedos contra el mástil. De esta manera, la cuerda ahora solo puede vibrar entre el dedo y el anclaje inferior, por lo que su longitud es menor y la guitarra emite un sonido que es más agudo que si no ponemos ningún dedo. Por lo tanto, a medida que nuestros dedos estén más abajo en el mástil la cuerda será más corta y el sonido será más agudo. La próxima vez que tengáis una guitarra en vuestras manos comprobad cómo cambia la frecuencia del sonido en función de la tensión, la longitud y la densidad de la cuerda.

Aquí hemos visto el caso de la guitarra, pero la fórmula anterior es válida para cualquier instrumento de cuerda. Como cada nota de la escala musical tiene una frecuencia asociada, podemos elegir L, T y <font face="Symbol">m</font> en una cuerda para obtener la nota que queramos. Por ejemplo, si tomamos una cuerda de 1 metro de largo, una densidad de 1 gramo por metro y una tensión de 70 Newtons, esta cuerda vibrará a 440 Hz, es decir, que será un La. Sin embargo, podemos encontrar otros valores para que la frecuencia sea la misma, por lo tanto podemos obtener la misma nota con un violín y con una guitarra. Pero, un momento, si tanto la cuerda del violín como la cuerda de la guitarra emiten el sonido exactamente en la misma frecuencia, esto significa que suenan exactamente igual. Sin embargo, somos capaces de diferenciar si un sonido proviene de una guitarra, un piano o un violín. ¿Qué es lo que está pasando?

Hasta ahora solo hemos hablado de la frecuencia fundamental, que es la frecuencia más baja a la que puede vibrar una cuerda. En cambio, la cuerda puede vibrar a frecuencias más altas que la frecuencia fundamental, emitiendo sonidos más agudos, que son los que hacen que la misma nota suene distinta en cada instrumento. Pero esto lo veremos en el siguiente post sobre música y física. 


&nbsp;  
&nbsp;

<span style="font-size:1.5em"><a id="target" style= "color:black"><b>Glosario</b></a></span>
&nbsp;   
<span style="font-size:1.25em">
**Hercio**: el hercio es la unidad de medida de la frecuencia y su abreviatura es Hz. Cuando decimos que algo vibra con 10 Hz de frecuencia significa que en un segundo completa 10 oscilaciones. Al igual que 1 kg son 1000 gramos, 1 kHz son 1000 Hz.
<br>
**Amplitud y frecuencia**: como hemos mencionado, la amplitud y la frecuencia de una onda definen cómo de alto o bajo es un sonido y como de grave o agudo lo escuchamos, respectivamente. La frecuencia es el número de oscilaciones que una partícula realiza en un segundo. En cambio, la amplitud de oscilación es la distancia entre los entre los dos puntos más alejados de la partícula cuando vibra.  <br>
</span>
{: .notice--primary}   

---
**Para saber más**
* Anteriormente hemos escrito la ecuación que nos da la frecuencia fundamental en función de la longitud de la cuerda, su tensión y su densinsidad lineal. Esta expresión no es completamente exacta, puesto que no contiene otros parámetros que también afectan a dicha frecuencia; sin embargo, da un resultado bastante preciso para el objetivo de este post. 

* Para más información sobre cómo vibra una cuerda de una guitarra: [link](http://citharaworld.blogspot.com/2017/03/ecuacion-para-una-cuerda-de-guitarra.html){:target="_blank"}

* [Matemáticas, música y Pitágoras](https://www.palermo.edu/ingenieria/downloads/CyT6/6CyT%2003.pdf){:target="_blank"}

* Como podéis ver en esta [tabla de Wikipedia](https://es.wikipedia.org/wiki/Frecuencias_de_afinaci%C3%B3n_del_piano){:target="_blank"}, cada nota tiene asociada una frecuencia con mucha precisión.
