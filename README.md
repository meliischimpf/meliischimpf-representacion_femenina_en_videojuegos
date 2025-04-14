Tipo de Análisis:
Análisis de Contenido: Evaluar la representación de personajes femeninos en videojuegos, incluyendo la sexualización de los personajes. Esto podría involucrar un análisis de imágenes y descripciones de personajes en juegos.
Análisis de Opiniones de Usuarios: Recopilar opiniones y comentarios de usuarios sobre videojuegos específicos para comprender cómo perciben la representación de personajes femeninos y la sexualización en los juegos.
Análisis de Ventas y Recepción: Examinar las ventas y la recepción crítica de videojuegos con personajes femeninos sexualizados y compararlos con juegos que presentan representaciones más diversas y realistas de género.

OBJETIVO
●	Evaluar la relación entre la representación sexualizada de personajes femeninos en videojuegos y la percepción de los usuarios, incluyendo su impacto en las ventas y la recepción crítica.
●	Identificar patrones y tendencias en la representación de personajes femeninos en videojuegos a lo largo del tiempo y en diferentes géneros de juegos.
●	Proporcionar recomendaciones para la industria de los videojuegos sobre cómo mejorar la representación de género y reducir la sexualización innecesaria de personajes femeninos.

¿Qué problema/conflicto vamos a resolver?
El proyecto se enfoca en abordar problemas como la representación sexista o estereotipada de las mujeres en los videojuegos, la hipersexualización de personajes femeninos y cómo estos factores pueden influir en la percepción de género y la experiencia de juego de los usuarios.

¿Qué nuevas preguntas de investigación nos gustaría agregar?
¿Cuál es la percepción de los jugadores en cuanto a la representación de personajes femeninos en videojuegos y cómo influye en su experiencia de juego?
¿Cuáles son las implicaciones de la representación de género en los videojuegos en términos de igualdad de género en la sociedad?
¿En qué medida la inclusión de personajes femeninos más diversos y realistas impacta en las ventas y la recepción de los videojuegos?
¿Qué estrategias han adoptado las de desarrollo?
¿Cómo afecta la representación de género en los videojuegos a la percepción y elección?

Audiencia Destinataria del Análisis:
Jugadores y Comunidades de Jugadores de la plataforma “Steam”.

MODELO ETL
1.	RECOLECCIÓN DE DATOS (Extract)
Obtener datos relevantes de fuentes diversas, como comentarios de usuarios en redes sociales, reseñas de juegos en sitios web, datos de ventas de videojuegos y descripciones de personajes de videojuegos. Se pueden utilizar web scraping, API de redes sociales y fuentes de datos de ventas de videojuegos.
2.	TRANSFORM - 
Procesar los datos para que sean adecuados para el análisis. Esto incluye la limpieza de datos, la normalización de texto, la categorización de la sexualización de personajes y la agregación de datos para obtener métricas significativas.
3.	LOAD -
Almacenar los datos transformados en una base de datos o almacén de datos. Esto permitirá realizar análisis en profundidad y consultas sobre los datos procesados.

Modelo ER
![modeloER](https://github.com/user-attachments/assets/9763f2ff-42ed-4cb6-880a-c20b8c8be020)




Aplicando SQL:
El Dataset base utilizado en excel se encuentra al clickear este [Link](https://drive.google.com/file/d/1rgG8ml0J2Q3zyIq6yXEGzcQyMYnxYEDx/view?usp=drive_link)
https://drive.google.com/file/d/1rgG8ml0J2Q3zyIq6yXEGzcQyMYnxYEDx/view?usp=drive_link
Previamente se importó el archivo .csv a SQL como tabla, dentro de una base de datos llamada “Proyecto”. Posteriormente, se realizaron las siguientes consultas utilizando SQL:

-	Número de personajes femeninos:

![Image](https://github.com/user-attachments/assets/59230045-8692-416e-a4b1-f65e64d61bb9)

![Image](https://github.com/user-attachments/assets/d768668f-92eb-4701-a830-caa7143a3102)


-	Número de personajes masculinos:

![Image](https://github.com/user-attachments/assets/2ac1c1d0-602e-457a-93df-12d57009a366)

![Image](https://github.com/user-attachments/assets/7e441146-2bb3-4ccb-9881-65c9011a1686)


-	Número de personajes no binarios:

![Image](https://github.com/user-attachments/assets/01cfef05-fe43-4f59-8552-aca47d5ff8aa)

![Image](https://github.com/user-attachments/assets/c7b2d3a6-1bfa-4f76-9f4b-6cee8fab26bc)


-	Mayor número de personajes femeninos en un videojuego

![Image](https://github.com/user-attachments/assets/96e0dc3d-4546-4140-8b5b-e0d63448c129)

![Image](https://github.com/user-attachments/assets/0e185ea8-86d2-4374-8c15-b7adc51b3682)


-	Encontrar personajes femeninos adolescentes

![Image](https://github.com/user-attachments/assets/9676d4d1-2530-4e25-97d2-f058b7fe2780)

![Image](https://github.com/user-attachments/assets/57017dcc-4ec5-40c8-8a0a-ad89d4c6e3be)


-	Encontrar personajes femeninos que sean jugables:

![Image](https://github.com/user-attachments/assets/d2efd298-a00e-454b-b6ec-4a165eaf0a90)

![Image](https://github.com/user-attachments/assets/28ad4c2f-3574-4802-af53-c42ea85f8240)

![Image](https://github.com/user-attachments/assets/96c9eedb-e714-447c-82db-bf4fc690d166)


-	Encontrar personajes femeninos con un nivel alto de sexualización

![Image](https://github.com/user-attachments/assets/cba0a6cd-a52d-459a-b230-f9da70a28c20)

![Image](https://github.com/user-attachments/assets/3fdf2974-e8f1-4617-b7a6-099691b924d4)



POWER BI

[Link](https://app.powerbi.com/groups/me/reports/e30548fc-f773-4cab-a9b1-82c5567c4e5c/ReportSection?experience=power-bi) al Dashboard en Power BI:


Fuente de los datos:
[Characters.grivg](https://docs.google.com/spreadsheets/d/1ocTagpHKOQ7pY4ZPWMhzSEEYMx_-2N-epRS5w_CJAxs/edit#gid=1457270248&fvid=1118138477)



Logo:



Consultas:
¿Qué porcentaje de especies aparecen en los videojuegos?

¿Cuál es el porcentaje de género de los personajes que aparecen en los videojuegos?
¿Cuál es el porcentaje de género en la que los personajes en los videojuegos son jugables?
 
De estos videojuegos, ¿Cuál es la suma de sus niveles de sexualización en sus personajes?












Modelo Relacional:










Se utilizaron las siguientes funciones:
●	COUNT: Para contar el número de juegos con personajes femeninos sexualizados.
●	SUM: Para sumar el porcentaje de personajes de los distintos géneros.
●	DIVIDE: Para dividir dos valores y poder calcular el porcentaje de personajes jugables.
Se realizaron los siguientes cálculos en DAX:
●	Porcentaje de personajes femeninos jugables: Para calcular este porcentaje, se divide el número de personajes femeninos jugables por el número total de personajes jugables.
●	Porcentaje de juegos con personajes femeninos sexualizados: Para calcular este porcentaje, se divide el número de juegos con personajes femeninos sexualizados por el número total de juegos.
Transformaciones de datos:
●	Se eliminaron los registros duplicados.
●	Se formatearon las fechas y las horas.
●	Se crearon nuevas columnas a partir de los datos existentes.
Glosario de términos
●	Name: El nombre del personaje.
●	Gender: El género del personaje. Puede ser femenino, masculino, no binario o desconocido.
●	Game: El nombre del juego en el que aparece el personaje.
●	Age: La edad del personaje, en años (época de vida a los que no se conoce la edad exacta).
●	Age_range: El rango de edad del personaje, es decir, la etapa de vida de ese personaje.
●	Playable: Si el personaje es jugable o no. Puede ser 0 (no jugable) o 1 (jugable).
●	Sexualization: Si el personaje está sexualizado o no. Puede ser 0 (no sexualizado), 1 (poco sexualizado), 2 (sexualizado) o 3 (altamente sexualizado).
●	ID: Un identificador único para el personaje.
●	Species: La especie del personaje. Puede ser humano, alienígena, animal, robot u otro.
●	Side: El lado en el que está el personaje. Puede ser P (Protagonist), B (bad guy/girl), A (Ally).
●	Relevance: Cómo de relevante es el personaje para la trama del juego. Pueden ser: PA (Personaje principal), SC (Personaje secundario), MC (Personaje con impacto menor) o DA (Data). 
●	Romantic_Interest: Si el personaje tiene un interés romántico o no. Puede ser Sí o No.
