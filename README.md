# Zoo TapTap

Zoo TapTap es una aplicación que busca involucrar a niños con un rango de edad de 6 a 10 años con los animales del zoológico Nacional de Chile. Esta aplicación ofrece a los niños misiones fotográficas y desafíos, para que a través del juego aprendan sobre sus animales favoritos. Al descubrir los secretos sobre los animales y completar los desafíos los niños ganan medallas de recompensa, para que adquieran un rol de líder dentro de la actividad. 

![zootap1](https://user-images.githubusercontent.com/32286870/37943549-66812cfa-314e-11e8-8433-224aef7409c2.jpg)

## Desarrollado para 
[Zoologico Nacional de Chile](https://marvelapp.com/638g87g/screen/39836666)

![](/img/zooapp-img-1.png)


## Problem statement |
Los niños necesitan involucrarse de manera interactiva con los animales del zoológico para aprender sobre sus animales favoritos.

- **Usuario primario:** Niños entre la edad de 6 a 10 años.
- **Usuario secundario:** Padres o profesores a cargo del usuario primario. 

## How Might We? |
- ¿Cómo podríamos hacer que los niños aprendan sobre los animales del zoológico de manera divertida, educativa y significativa?
- ¿Cómo podríamos incentivar a los niños a descubrir la mayor cantidad de animales y las diferentes hábitats dentro del zoológico?
- ¿Cómo podríamos ayudar a a los niños a reconocer en qué parte del zoológico se encuentran ellos y sus animales favoritos? 

## What if… | 
- Qué pasaría si a través del juego creamos misiones para que los niños fotografíen a los animales del zoológico.
- Qué pasaría si los niños al sacar fotografías a los animales, se desplegará información de manera didáctica sobre sus características y el hábitat donde se encuentran.
- Qué pasaría si después de cada explicación sobre los animales, existieran desafíos para verificar si los niños entendieron la información. 
- Qué pasaría si los niños obtuviera recompensas o un feedback positivo después de cada desafío respondido correctamente.
- Qué pasaría si usamos un mapa GPS para mostrar dónde están los niños y dónde está el animal que buscan.

![zooapp-img-2](https://user-images.githubusercontent.com/32286870/37931982-acfed118-311d-11e8-8697-a70c6a4009c4.png)

***

## Antecedentes |
1. Conclusiones entrevistas a profesoras y ex guía del Buin Zoo.
Se hizo una guía de entrevista para profesores y/o guías de zoológicos con el objetivo de averiguar cómo es el aprendizaje de los alumnos de primero a cuarto básico, cuando van al zoológico u otro paseo educativo. En esta ocasión se entrevistó a Claudia Vera (profesora de inglés de niños de 4 a 10 años), Francisca Pardo (profesora de educación general básica del colegio Seminario Padre Hurtado) y a Gabriel González (ex guía Buin Zoo). 

Luego de realizar las entrevistas **se pudo concluir lo siguiente:**
- Al enseñar contenido nuevo a los niños por medio de libros y/o textos, estos suelen aburrirse y desconcentrarse. Una buena forma es enseñarles por medio de cosas de su vida cotidiana que les guste y llame la atención  (por ejemplo: Pokemon, Youtube y Videojuegos) para así meterles contenido sin que se den cuenta.
- El repetir una acción o palabra hace que el aprendizaje de lo que se le está enseñando a los niños sea más rápido.
- El feedback positivo, cuando el niño hace alguna actividad bien, genera confianza en el.
- La motivación que les causa el salir de lo común, favorece mucho el aprendizaje.
- Las salidas duran como máximo 3 horas incluyendo el traslado.
- A través del juego y la comparación de características de los animales, resulta una buena manera para evaluar lo que aprendieron y lo que recuerdan los niños.

2. Observación en terreno:
Visité el zoológico Nacional de Chile, el día Domingo 11 de Marzo del 2018, para observar el comportamiento de los niños en zoológico, realizar entrevistas a niños y sacar fotografías, además de participar del recorrido como una espectadora más y así Investigar los puntos de conflicto (paint points) de niños de 6 a 10 años, en la experiencia de ir al zoológico e identificar puntos de mejora durante su visita, obteniendo de esta manera insights para poder comenzar a conceptualizar e idealizar el proyecto. 

![zooapp-img-3png](https://user-images.githubusercontent.com/32286870/37932091-fdc79c7e-311d-11e8-8ef9-2ef3afe605b9.png)

Puntos de conflicto, **conclusiones:**
- Los niños de entre 5 a 9 años, se pierden de ver a muchos animales, ya sea porque estos se encuentran durmiendo o porque se encuentra a mayor altura que la de su campo de visualización. Esto les frustra y suelen decirle a sus padres: ¿Dónde están los animales?, ¿Pucha oh no veo ningún animal?.  
- Los niños no andan con celular, pero le suelen pedir el celular a sus padres para sacarle fotografías a los animales.
- Los animales que más recuerdan los niños son los que pudieron ver más de cerca.
- Los niños no leen la descripciones de los animales de los tótem, porque no están a su nivel de visión y no es algo divertido de hacer.
- El zoológico a pesar de ser un panorama enfocado en los niños, no está pensado para que ellos descubran por sí mismos y sean los protagonistas de la actividad.

***

## Usuario primario - Bastian |
![zooapp-img-4](https://user-images.githubusercontent.com/32286870/37933475-b7ae45d6-3121-11e8-83b8-513bde04daf9.png)

## User Journey Map |
Se realizó un mapa de viaje, para identificar los puntos críticos de los usuarios en las diferentes etapas cuando van al zoológico y así conseguir oportunidades de mejora.
![zooapp-img-5](https://user-images.githubusercontent.com/32286870/37934352-4533480a-3124-11e8-84a4-14cbf4fbd5ff.png)

## Arquitectura de la información
Se realizo una arquitectura de la organización, para organizar, etiquetar y diseñar el contenido que tendrá la aplicación Zoo TapTap. Esto me permite dar estructura, completar objetivos y dar sentido a la información.
![zooapp-img-6](https://user-images.githubusercontent.com/32286870/37934776-b7c19470-3125-11e8-91a5-6271a986b2ff.png)

***

## User flow y Testing 
Se utilizó user flow para determinar el trayecto que realizarán los diferentes usuarios para realizar diferentes tareas dentro de la aplicación. Luego se testearon los wireframes y se anotaron las observaciones con post-it. Las primeras pruebas de usabilidad se realizaron en prototipos de papel. Las tareas que debian hacer los usuarios eran: 
- Hacer doble tap sobre pingui y aceptar la misión.
- Sacar fotografía y descubrir el secreto sobre el animal fotografiado.
- Aceptar desafío, responder preguntas y obtener medalla.

![zoo-wireframes](https://user-images.githubusercontent.com/32286870/38185007-29de82d8-3622-11e8-9831-c9fc3f2cf8c7.jpg)

![zoo-wireframes2](https://user-images.githubusercontent.com/32286870/38185009-29fd84ee-3622-11e8-93f9-3f1a6552a693.jpg)

## Prototipos de alta fidelidad
Las observaciones hechas en el testing fueron corregidas, para así mejorar la experiencia del usuario al momento de ocupar la aplicación. Este nuevo prototipo fue hecho con la herramienta Marvelapp.
