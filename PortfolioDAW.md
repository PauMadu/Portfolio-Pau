# Tema 1 - Ubuntu / Github / MarkDown.
**Empezamos** el portafolio y tras 2 semanas de clase, mi sensación es que no tengo control ni conocimiento sobre la _terminal de Linux_, y esa es una de mis mayores preocupaciones.  
Por otra parte hemos visto un poco de _Github_, que básicamente sirve para almacenar nuestro código, y poder compartirlo con otras personas. Seguro que tiene infinidades de herramientas pero de momento apenas conozco estas utilidades.

**El 26 de Septiembre:** Hemos visto el lenguaje de _MarkDown_, que sinceramente me ha gustado mucho porque no tiene ninguna dificultad, además Dani nos ha dado una guía, que le hemos hecho perfectamente y muy rápida. Además después de la guía también hemos hecho un ejercicio sobre chiquito donde usamos todos los contenidos de _MarkDown_ y además de practicar, ha sido muy divertido de hacer.  
Dani también ha propuesto que cada equipo prepare 2 temas por parejas, para el 30 de septiembre. Los tenemos que estudiar y prepararnos para el siguiente 7 de octubre, donde los explicaremos en clase. Lo tengo que hacer con Manu, y los temas que tenemos que preparar son:
>1- Modelos de arquitecturas web.  
 2- SSH.

# Tema 2 - Presentaciones
**3 de Octubre:** Junto con mi compañero Manu, estuvimos en esta clase haciendo un resumen de los 2 temas que teníamos que explicar este viernes, además de resumir, una tarea muy importante era entre los 2 entender el contenido y si uno no entendía alguna cosa, el otro trataba de explicárselo.  
También dividimos los 2 temas para que cada uno ya pudiera empezar a estudiar, y lo hicimos de tal forma que dentro de cada tema habláramos un apartado cada uno, para darle frescura a la presentación y hacerla un poco más entretenida para los oyentes.

**7 de Octubre:** Ha llegado el día de la presentación, Manu y yo lo tenemos bastante claro, pero aun así los nervios siempre están presentes. Pero para afrontarlos hemos decidido ser los primeros.  
Una vez acabada la presentación, ha salido tal y como esperábamos, muy bien. Para toda la información que teníamos la hemos hecho en 20 minutos, esperamos que no se haya hecho muy pesada, y se haya entendido todo. Además Dani me ha hecho un par de preguntas y también  las he respondido correctamente así que espero que tengamos buena nota, y sobre todo que los compañeros hayan aprendido, que en fin es lo más importante.  
Respecto a la opinión personal es un trabajo diferente a lo que estamos acostumbrados, y el hecho de hacer trabajos por grupos para mi se hace más ameno, además que haya sido una presentación también es buena idea ya que tenemos que ir acostumbrándonos a exponer nuestro contenido a un público. La única pega es que este trabajo también tiene una responsabilidad muy grande ya que depende de ti mismo que los compañeros puedan aprender, o si algún grupo no se lo toma en serio somos los demás los que también nos vemos perjudicados.

# Tema 3 - Apache.
**10 de Octubre:** Los compañeros que faltaban, hoy han terminado las presentaciones de sus trabajos.  
Además hemos empezado con la introducción e instalación de Apache, primeramente hemos leído una página donde explicaba muy bien los pasos a seguir y posteriormente lo hemos llevado a la práctica mediante nuestra terminal de Linux.  
Una vez realizada la instalación y verificación de ella, el siguiente paso ha sido hacer unas memorias de lo que hemos realizado, siguiendo unas pautas ya marcadas por Dani.  
El trabajo de las Memorias me parece muy útil pero la verdad me ha costado bastante seguir los pasos indicados. Entiendo que es para que sea una redacción más profesional, pero a la hora de que nosotros las utilizamos por ejemplo para estudiar, yo tengo una forma de redactar diferente, y estoy viendo que no me es nada cómodo ni efectivo.

**14 de Octubre:** Hemos seguido con el entorno Apache ya que el último día solo vimos la introducción e instalación. 
Pero hoy vamos a continuar con ello, y una vez acabado pasaremos a la configuración de Apache, y de nuestro sitio web, así como crearlo y poner información dentro de él.  
Primeramente como ya hicimos el día anterior, tenemos una página donde están todos los pasos a seguir, una vez leídos pasamos a la práctica. Donde me surgió un problema y tuve que indagar un poco para buscar la solución, pero Dani ya estaba previsto de que esto pasaría y nos dejó otra web donde ponía como solucionar el problema, por último tenemos que redactar unas memorias sobre la configuración.

**18 de Octubre** 
En la clase de hoy, yo no tenia ningun trabajo atrasado y nada por hacer, así que en vez de estar perdiendo el tiempo, (ya que mis compañeros sí que tenían cosas retrasadas por hacer), me he puesto a hacer JavaScript, ya que como estas dos asignaturas las imparte Dani le podía preguntar cualquier duda o problema que me surgiera.  
No es que fuera un dia super productivo porque no avanzamos nada sobre esta materia (DAW), pero por lo menos no he perdido el tiempo y he hecho cosas que si no las hubiera hecho tendría que hacerlas en casa...

## Tema 3.2 - Tomcat.
**21 de Octubre:** El día de hoy Dani nos ha introducido Tomcat; que es básicamente un contenedor para almacenar los servidores de una página web (o incluso videojuegos), y este incluso se puede usar para compilar y ejecutar aplicaciones web realizadas en Java.  
El trabajo ha consistido en instalar Tomcat en Linux, mediante los comandos de la terminal, una vez hecho, también hemos tenido que crear un usuario para así poder entrar a la página web de Tomcat, donde podremos ver todos nuestros servidores.  
La instalación ha sido muy sencilla, **excepto** (en el paso 1.2 de la Creacion de un Usuario, donde ha saltado un error pero para arreglarlo únicamente tenemos que poner lo siguiente):  
```
< role rolename = "admin-gui" />  
< role rolename = "manager-gui"/>  
< usuario nombre de usuario = "tomcat" contraseña = "aprobar" roles = "admin-gui,manager-gui" />
```

**24 de Octubre:** 
Hoy no he podido asistir a clase ya que tenía un viaje previsto y por eso no he podido asistir. Igualmente me he informado de lo que han hecho y como iba bastante adelantado no me he perdido nada nuevo. Únicamente tengo que realizar el trabajo por parejas que nos pondremos a trabajar el próximo viernes 28.

# Tema 4 - SSH.
**28 de Octubre:** 
Dani ha propuesto hacer una práctica de SSH por parejas, la cual consiste en que; uno de la pareja con su ordenador hará de _“Servidor”_, y el otro de _“Cliente”_, por lo tanto en nuestro caso Manu hará de Servidor por lo tendrá que:
- Crear un nuevo usuario -> solo para esta práctica.
- Y también tendrá que **activar el servidor SSH**.

 Esto para que yo, desde el ordenador que ejerce de cliente pueda: 
- Entrar al otro ordenador mediante el SSH
- Instalar Apache en el servidor.
- Pasa una web a algún lugar del servidor.
- Crea un virtualhost.
- Modifica los host del local para que con la dirección elegida vaya a la ip del servidor.
- Comprueba que puedes conectarte a la página.
- Abre en el servidor un browser a la página.

**31 de Noviembre:** 
El día de hoy hemos hecho la parte del servidor, y los dos primeros apartados del cliente, de momento bien, únicamente ha sido seguir los pasos que ya estaban indicados en la información que nos ha dado Dani y ejecutarlos en la terminal.
Ha sido un dia un poco raro porque es lunes y mañana martes es fiesta así que hemos trabajado un poco pero después nos hemos puesto a hablar y la clase se ha hecho más llevadera.

**4 de Noviembre:** 
Sinceramente hoy no ha sido un dia para nada productivo, más que nada porque seguimos Manu y yo con las prácticas por parejas, y hemos llegado a un punto donde no entendemos lo que nos pide hacer el ejercicio, así que pedimos ayuda a Dani, pero TODA la clase tenía dudas y justamente nosotros nos hemos quedado toda la clase sin tener una respuesta a nuestro problema.
Por lo menos hemos adelantado y redactado todo lo posible hasta donde hemos llegado.

**7 de Noviembre:** 
PORFIN!! Después del último día donde no pudimos hacer prácticamente nada, ya que estábamos bloqueados con una duda, hoy Dani si que ha podido venir a explicarnos lo que teníamos que hacer y hemos podido continuar con el trabajo.  
Al finalizar la clase apenas nos quedaban los dos últimos apartados del trabajo. Además de avanzar en el trabajo, mientras íbamos ejecutando el código en la terminal estábamos haciendo la guía del ejercicio y adjuntando imágenes, para que sea más visual.

**11 de Noviembre:** 
Finalmente, hoy hemos acabado el trabajo de SSH, al empezar me parecía mucho más difícil de lo que en verdad era, una vez hecho he entendido los pasos que estábamos siguiendo y para qué sirven. Así que aunque no sea mi asignatura favorita, ni la que mejor se me da, con este trabajo cada vez voy viendo cosas nuevas y para qué sirven.

**14 de Noviembre:** 
Hoy no hemos hecho clase, ya que el examen de DWC se ha alargado y hemos estado las 4 horas haciendo el examen...
La parte positiva es que era el primer examen del curso y personalmente he salido con buenas sensaciones.  
En cuanto a esta asignatura el examen lo tenemos el Viernes y sinceramente estoy bastante preocupado ya que me veo muy mal respecto al control del linux y también sobre los contenidos como Apache y SSH.

**18 de Noviembre:** 
**Dia del Examen,** estaba con mucho miedo por la falta de control, pero finalmente tenía muy bien preparados todos los apuntes y links para buscar la información que iba a necesitar.  
Personalmente estoy contento con el examen ya que ni yo mismo pensaba que podría hacer tanto con linux. Respecto a la dificultad del examen no es que fuera muy complicada. (Aunque no se como descargar una imagen mediante terminal), también he perdido mucho tiempo en pequeños errores que no sabía como solucionar. Además de que siento que soy el que más perdido va de toda la clase en esta asignatura, pero es totalmente normal porque nunca había tocado linux ni su terminal, aparte de MarkDown, Apache y SSH.
Finalmente creo que por lo menos sí que podré aprobar.  

**21 de Noviembre:** 
Semana de Examenes.

**25 de Noviembre:** 
Semana de Examenes.

# Tema 5 - LAMP.
**28 de Noviembre:** 
Tras realizar todos los examenes del Primer Trimestre, nos disponemos a empezar rapidamente el Segundo Trimestre. Y rapidamente porque el tema 5 es sobre LAMP, el dia de hoy Dani nos lo ha introducido, y nos ha dado un documento con información y un pequeño ejemplo práctico.  
Tambien nos ha propuesto dar este tema de forma rápida pero intensa ya que si lo hacemos asi podremos hacer el examen antes de Navidad y ya no tendremos que hacer ningun examen sobre esta asignatura, esto personalmente me beneficia mucho ya que Despliegue de Aplicaciones no es mi punto fuerte y si me lo puedo quitar de encima cuanto antes mucho mejor.

**2 de Diciembre:** Hoy he empezado a leerme el documento que es bastante extenso(acabaré de leerlo en casa, más tranquilamente, porque habia mucho ruido en clase) y he realizado el mini ejercicio, pero era mas practica sobre PHP que otra cosa, asi que muy fácil.
