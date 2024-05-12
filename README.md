# DIU24
Prácticas Diseño Interfaces de Usuario 2023-24 (Tema: .... ) 

Grupo: DIU1_01AABB.  Curso: 2023/24 
Updated: 11/2/2024

Proyecto: 
>>> CompArte

Descripción: 

>>> Talleres artísticos donde el objetivo es más bien desconectar y divertirse, además de aprender algo nuevo.

Logotipo: 
>>> <img src="https://github.com/Shadink/DIU-huevosrotos/assets/116192882/4d37ed32-2b86-49b2-a929-afe2e47bcaae" width="25%"><br>
>>> <figure><img src="https://github.com/Shadink/DIU-huevosrotos/assets/116192882/5e6f5ca9-b879-4b94-b323-b2b385d17d1c" width="25%"> <br><figcaption>Logo sin nombre para versión web</figcaption></figure>

Miembros
 * Antonio Haro Arriaza     
 * Mario Vílchez Romero

----- 




# Proceso de Diseño 

## Paso 1. UX User & Desk Research & Analisis 


![Método UX](img/Competitive.png) **1.a User Reseach Plan**
-----

>>> Informar y ser claros con el usuario, además de tener un buen rendimiento en la página web.

![Método UX](img/Competitive.png) 1.b Competitive Analysis
-----

>>> Arte de comer sano: Un proyecto Sevillano de nutrición y talleres con una página web muy estilizada y bonita, aunque es un poco difícil de navegar.
    Sabores: Proyecto Barcelonés que realiza cursos de cocina. Aunque el estilo de su página es más simple, es muy fácil navegar por ella y reservar talleres.
    Granada Cooking: Proyecto Granadino de cursos de cocina. Aunque su página de inicio es bonita, su navegación es bastante complicada, con muchos carruseles que no tienen sentido en la página de inicio y cuyo calendario se ralentiza mucho, a veces ni siquiera se carga la información.
    Hemos elegido Sabores como el mejor proyecto porque nos parece muy llamativo y el que más hace crecer el interés por los cursos. Incluso a nosotros nos interesó bastante y estuvimos un rato mirando la página. Además, tienen una visita virtual, que permite a quien pretenda reservar un curso investigar cómo va a ser el espacio que van a utilizar, además de aumentar el interés, ya que están dispuestos a mostrar el lugar entero.


![Método UX](img/Persona.png) 1.c Persona
-----

>>> Hemos seleccionado a estas personas porque representan dos tipos diferentes de usuarios que pueden estar interesados en estos proyectos. Fernando puede representar al mercado más joven y Federico al más adulto, cada uno con experiencias de cocina diferentes. Además, el hecho de que Fernando sea informático hace que pueda tener opiniones más técnicas sobre la página, mientras que Federico, que es una persona más mayor y escritor, no tiene ni idea de estas tecnologías y tiene una visión más “inocente”.

![Método UX](img/JourneyMap.png) 1.d User Journey Map
----


>>> Hemos escogido estas experiencias porque nos parecen cosas realistas que podrían querer estas Personas: Fernando, para llevar un estilo de vida más saludable en su vida independiente; Federico, para hacerle un regalo a su mujer. Estos dos deseos tienen su diferencia: uno es una persona que se está asentando en la vida, el otro ya se ha asentado hace tiempo, y es interesante ver los puntos de vista de cada uno.

![Método UX](img/usabilityReview.png) 1.e Usability Review
----
>>>  Revisión de usabilidad: (toma los siguientes documentos de referncia y verifica puntos de verificación de  usabilidad
>>>> SE deben incluir claramente los siguientes elementos
>>> - Enlace al documento: https://github.com/Shadink/DIU-huevosrotos/blob/master/P1/UsabilityReviewP1.pdf
>>> - Valoración final (numérica): 69
>>> - El principal problema de la página elegida (Granada Cooking) es lo que consideramos más importante: la dificultad generada para navegarla. Esta página está llena de botones y apartados que no llevan a ninguna parte, y algunas veces no muestran lo que dicen que se muestra según el título. La única forma de revisar los talleres en un orden específico o con algún criterio es mediante el calendario, y el mismo carga muy lento, a veces ni se muestra.


## Paso 2. UX Design  


![Método UX](img/feedback-capture-grid.png) 2.a Reframing / IDEACION: Feedback Capture Grid / EMpathy map 
----


>>> Comenta con un diagrama los aspectos más destacados a modo de conclusion de la práctica anterior,


 Interesante | Críticas     
| ------------- | -------
  La forma de captar al usuario. | El sitio era muy confuso de navegar.
  Los calendarios son una buena forma de organizar una página web que ofrece este tipo de servicios. | El rendimiento del sitio, sobre todo en los calendarios, su aspecto más importante, era malo.

  
>>> a. Hacer talleres más colaborativos, con la intención principal de pasárselo bien.
>>> b. Incentivar a la gente a repetir y llevar amigos con descuentos, promociones y un sistema de puntos.



![Método UX](img/ScopeCanvas.png) 2.b ScopeCanvas
----
>>> Lo que hace a nuestro proyecto diferente de otros es el sistema de puntos y cupones que implementamos, con el cual se incentiva la participación en varios talleres al entregar puntos a los usuarios registrados por taller completado. Con esos puntos, después, se pueden pagar cupones exclusivos para miembros. De esta forma logramos crear una comunidad que vaya aumentando poco a poco y sea fiel a nuestro producto.

![Método UX](img/Sitemap.png) 2.b User Flow (task) analysis 
-----

>>> Nuestros user flow diferencian entre una reserva por parte de alguien que no tiene cuenta y una reserva por parte de alguien con cuenta en nuestra web.


![Método UX](img/labelling.png) 2.c IA: Sitemap + Labelling 
----

Término | Significado     
| ------------- | -------
Buscar | Desde cualquier punto de la página, se puede buscar un taller concreto indicando el nombre y otros filtros.
Cuenta	| Lleva al perfil del usuario, donde se puede ver su información, sus puntos y promociones canjeables.
Contacto | Lleva a la página de contacto y permite enviar un mensaje a la organización directamente, además de mostrar información sobre la misma.
Iniciar Sesión/Registrarse | Lleva a una página donde el usuario puede iniciar sesión o crear una cuenta para poder disfrutar de los privilegios de los miembros.
RRSS | Un apartado que muestra las RRSS de la organización, como Twitter, Instagram o Facebook, en una vista previa.
Calendario | Lleva al calendario, que ordena por fecha en una cuadrícula cada taller de forma que el usuario ve la información de forma más fácil.
Promociones | Lleva a la página de promociones, donde el usuario puede ver promociones disponibles para los talleres.
Inicio | Lleva a la página de inicio.
Cupones | Indican promociones disponibles para todo el mundo.
Ver local en 3D | Permite al usuario ver con detalle dónde se realizará el taller mediante una vista 360º.
Pagar | Lleva a la página de pago, donde se piden los datos pertinentes y se realiza la acción.
Previa Taller | Previsualización que, al ser pinchada, lleva a la página del taller. Incluye nombre y una descripción corta del taller.
Cupones Exclusivos | Indican promociones únicamente canjeadas por usuarios, disponibles para usar en un pago.
Formas de pago | Desplegable desde el que el usuario elige la forma de pago antes de pagar (PayPal, Tarjeta, Bizum, etc)
Puntos | Puntos disponibles con los que se pueden obtener los cupones exclusivos. Solamente para usuarios registrados.


![Método UX](img/Wireframes.png) 2.d Wireframes
-----

>>> Utilizamos el plugin breakpoints para permitir el cambio de tamaño de la pantalla. Nuestra filosofía es unir en columnas los elementos si están separados horizontalmente.


## Paso 3. Mi UX-Case Study (diseño)


![Método UX](img/moodboard.png) 3.a Moodboard
-----


>>> Plantear Diseño visual con una guía de estilos visual (moodboard) 
>>> Incluir Logotipo
>>> Para el logotipo hemos buscado logos en [Tailor Brands](https://www.tailorbrands.com/es/logo-maker) como inspiración y lo hemos recreado en paint.net usando iconos de pinceles en internet. La idea es que los dos pinceles representan dos personas pintando juntas, lo cual creemos que refleja los ideales de la organización: desarrollar la creatividad y la cultura en grupos de gente con la intención de socializar mediante el arte.


![Método UX](img/landing-page.png)  3.b Landing Page
----


>>> Plantear Landing Page 

![Método UX](img/guidelines.png) 3.c Guidelines
----

>>> Estudio de Guidelines y Patrones IU a usar 
>>> Tras documentarse, muestre las deciones tomadas sobre Patrones IU a usar para la fase siguiente de prototipado. 

![Método UX](img/mockup.png)  3.d Mockup
----

>>> Layout: Mockup / prototipo HTML  (que permita simular tareas con estilo de IU seleccionado)


![Método UX](img/caseStudy.png) 3.e ¿My UX-Case Study?
-----


>>> Publicar my Case Study en Github..
>>> Documente y resuma el diseño de su producto


## Paso 5. Exportación & evaluación con Eye Tracking 

Exportación a HTML/Flutter
-----

![Método UX](img/eye-tracking.png))  5.b Eye Tracking method 

>>> Indica cómo diseñas experimento y reclutas usuarios (uso de gazerecorder.com)  

Diseño del experimento 
----

>> Uso de imágenes (preferentemente) -> hay que esablecer una duración de visualización y  
>> fijar las áreas de interes (AoI) antes del diseño. Planificar qué tarea debe hacer el usuario (buscar, comprar...) 


![experimento](img/experimentoET.png)  
>> cambiar img por tu diseño de experimento  

>> Recordar que gazerecorder es una versión de pruebas: usar sólo con 3 usuarios para generar mapa de calor (recordar que crédito > 0 para que funcione) 

Resultados y valoración 
-----



>> Cambiar por tus resultados
![Resultado](img/resultadoET.png)  



## Paso 4. Evaluación 


![Método UX](img/ABtesting.png) 4.a Caso asignado
----


>>> Breve descripción del caso asignado con enlace a  su repositorio Github


![Método UX](img/usability-testing.png) 4.b User Testing
----

>>> Seleccione 4 personas ficticias. Exprese las ideas de posibles situaciones conflictivas de esa persona en las propuestas evaluadas. Asigne dos a Caso A y 2 al caso B
 

| Usuarios | Sexo/Edad     | Ocupación   |  Exp.TIC    | Personalidad | Plataforma | TestA/B
| ------------- | -------- | ----------- | ----------- | -----------  | ---------- | ----
| User1's name  | H / 18   | Estudiante  | Media       | Introvertido | Web.       | A 
| User2's name  | H / 18   | Estudiante  | Media       | Timido       | Web        | A 
| User3's name  | M / 35   | Abogado     | Baja        | Emocional    | móvil      | B 
| User4's name  | H / 18   | Estudiante  | Media       | Racional     | Web        | B 


![Método UX](img/Survey.png) 4.c Cuestionario SUS
----

>>> Usaremos el **Cuestionario SUS** para valorar la satisfacción de cada usuario con el diseño (A/B) realizado. Para ello usamos la [hoja de cálculo](https://github.com/mgea/DIU19/blob/master/Cuestionario%20SUS%20DIU.xlsx) para calcular resultados sigiendo las pautas para usar la escala SUS e interpretar los resultados
http://usabilitygeek.com/how-to-use-the-system-usability-scale-sus-to-evaluate-the-usability-of-your-website/)
Para más información, consultar aquí sobre la [metodología SUS](https://cui.unige.ch/isi/icle-wiki/_media/ipm:test-suschapt.pdf)

>>> Adjuntar captura de imagen con los resultados + Valoración personal 


![Método UX](img/usability-report.png) 4.d Usability Report
----

>> Añadir report de usabilidad para práctica B (la de los compañeros)



>>> Valoración personal 





5.) Conclusion de EVALUACION (A/B testing + usability report + eye tracking) 
----


>> recupera el usability report de tu práctica (que es el caso B de los asignados a otros grupos) 
>> con los resultados del A/B testing, de eye tracking y del usability report:
>>  comentad en 2-3 parrafos cual es la conclusion acerca de la realización de la práctica y su evaluación con esas técnicas y que habéis aprendido






## Conclusión final / Valoración de las prácticas


>>> (90-150 palabras) Opinión FINAL del proceso de desarrollo de diseño siguiendo metodología UX y valoración (positiva /negativa) de los resultados obtenidos  













