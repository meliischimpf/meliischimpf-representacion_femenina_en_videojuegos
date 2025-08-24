

---

# 🎮 Análisis de Representación de Personajes Femeninos en Videojuegos

## 📊 Tipo de Análisis

1. **Análisis de Contenido:**  
   Evaluación de la representación de personajes femeninos en videojuegos, incluyendo su sexualización. Se analizan imágenes y descripciones de personajes.

2. **Análisis de Opiniones de Usuarios:**  
   Recopilación de opiniones y comentarios de usuarios sobre videojuegos para comprender cómo perciben la representación femenina y su sexualización.

3. **Análisis de Ventas y Recepción:**  
   Comparación de ventas y recepción crítica de juegos con personajes femeninos sexualizados vs. aquellos con representaciones más diversas y realistas.

---

## 🎯 Objetivos del Proyecto

- Evaluar la relación entre la representación sexualizada de personajes femeninos y la percepción de los usuarios.
- Identificar patrones en la representación de personajes femeninos según el tiempo y el tipo de juego.
- Proporcionar recomendaciones para mejorar la representación de género en la industria del videojuego.

---

## ❓ Problema a Resolver

Abordar la representación sexista o estereotipada de las mujeres en videojuegos, la hipersexualización de personajes femeninos, y su influencia en la percepción de género y experiencia de juego.

---

## 🧠 Nuevas Preguntas de Investigación

- ¿Cómo perciben los jugadores la representación femenina y cómo afecta su experiencia de juego?
- ¿Qué implicaciones tiene esto para la igualdad de género en la sociedad?
- ¿La inclusión de personajes más realistas influye en ventas y recepción crítica?
- ¿Qué estrategias adoptaron las empresas de desarrollo?
- ¿Cómo afecta la representación de género en la elección de los videojuegos?

---

## 🧑‍🤝‍🧑 Audiencia Objetivo

Jugadores y comunidades de jugadores de la plataforma **Steam**.

---

## 🛠️ Modelo ETL

1. **Extract - Recolección de Datos:**  
   Comentarios en redes sociales, reseñas, ventas y descripciones de personajes. Uso de web scraping y APIs.

2. **Transform - Transformación de Datos:**  
   Limpieza de datos, normalización, categorización de niveles de sexualización y agregación de métricas.

3. **Load - Carga:**  
   Almacenamiento en base de datos para análisis profundo y consultas SQL.

---

## 📐 Modelo Entidad-Relación

![Modelo ER](https://github.com/user-attachments/assets/9763f2ff-42ed-4cb6-880a-c20b8c8be020)

---

## 💾 Aplicación de SQL

🔗 Dataset base en Excel: [Descargar aquí](https://drive.google.com/file/d/1rgG8ml0J2Q3zyIq6yXEGzcQyMYnxYEDx/view?usp=drive_link)

Se importó el `.csv` a una base de datos llamada **"Proyecto"** y se realizaron las siguientes consultas:

### 📌 Número de personajes por género:

- Femeninos  
  ![Img](https://github.com/user-attachments/assets/59230045-8692-416e-a4b1-f65e64d61bb9)  
  ![Img](https://github.com/user-attachments/assets/d768668f-92eb-4701-a830-caa7143a3102)

- Masculinos  
  ![Img](https://github.com/user-attachments/assets/2ac1c1d0-602e-457a-93df-12d57009a366)  
  ![Img](https://github.com/user-attachments/assets/7e441146-2bb3-4ccb-9881-65c9011a1686)

- No Binarios  
  ![Img](https://github.com/user-attachments/assets/01cfef05-fe43-4f59-8552-aca47d5ff8aa)  
  ![Img](https://github.com/user-attachments/assets/c7b2d3a6-1bfa-4f76-9f4b-6cee8fab26bc)

### 🎮 Otros análisis:

- Videojuego con más personajes femeninos  
  ![Img](https://github.com/user-attachments/assets/96e0dc3d-4546-4140-8b5b-e0d63448c129)  
  ![Img](https://github.com/user-attachments/assets/0e185ea8-86d2-4374-8c15-b7adc51b3682)

- Personajes femeninos adolescentes  
  ![Img](https://github.com/user-attachments/assets/9676d4d1-2530-4e25-97d2-f058b7fe2780)  
  ![Img](https://github.com/user-attachments/assets/57017dcc-4ec5-40c8-8a0a-ad89d4c6e3be)

- Personajes femeninos jugables  
  ![Img](https://github.com/user-attachments/assets/d2efd298-a00e-454b-b6ec-4a165eaf0a90)  
  ![Img](https://github.com/user-attachments/assets/28ad4c2f-3574-4802-af53-c42ea85f8240)  
  ![Img](https://github.com/user-attachments/assets/96c9eedb-e714-447c-82db-bf4fc690d166)

- Nivel alto de sexualización  
  ![Img](https://github.com/user-attachments/assets/cba0a6cd-a52d-459a-b230-f9da70a28c20)  
  ![Img](https://github.com/user-attachments/assets/3fdf2974-e8f1-4617-b7a6-099691b924d4)

---

## 📊 Power BI

🔗 [Ver Dashboard en Power BI](https://app.powerbi.com/groups/me/reports/e30548fc-f773-4cab-a9b1-82c5567c4e5c/ReportSection?experience=power-bi)

### 📁 Fuente de los Datos

[Characters.grivg - Google Sheets](https://docs.google.com/spreadsheets/d/1ocTagpHKOQ7pY4ZPWMhzSEEYMx_-2N-epRS5w_CJAxs/edit#gid=1457270248&fvid=1118138477)

### 🔍 Consultas Power BI

- ¿Qué porcentaje de especies aparecen en videojuegos?  
  ![Img](https://github.com/user-attachments/assets/8012b540-31cb-4962-83d9-ad63b7deef92)

- ¿Cuál es el porcentaje de género de los personajes?  
  ![Img](https://github.com/user-attachments/assets/fe91a2be-6074-444f-afa7-435bac38c2f4)

- ¿Cuál es el porcentaje de personajes jugables por género?  
  ![Img](https://github.com/user-attachments/assets/80361115-4196-4e36-b1c2-691deea88c9c)

- Niveles de sexualización en personajes por videojuego  
  ![Img](https://github.com/user-attachments/assets/ae2d9fd2-d207-4838-bb6f-08110a9f16bb)

---

## 🧩 Modelo Relacional

![Modelo Relacional](https://github.com/user-attachments/assets/74864121-c8a8-4bcd-9f8a-c2d1b9d140d6)

---

## 🧮 Funciones y Cálculos Usados

### 📌 Funciones DAX:

- `COUNT`: Cuenta juegos con personajes sexualizados.
- `SUM`: Suma de porcentajes de géneros.
- `DIVIDE`: Cálculo de porcentajes de personajes jugables.

### 📈 Cálculos Realizados:

- **% Personajes femeninos jugables:**  
  Número de personajes femeninos jugables / Total de personajes jugables.

- **% Juegos con personajes sexualizados:**  
  Juegos con personajes sexualizados / Total de juegos.

### 🔄 Transformaciones de Datos:

- Eliminación de duplicados.
- Formateo de fechas y horas.

---

## 🖼️ Logo del Proyecto

![Logo](https://github.com/user-attachments/assets/54f57151-021d-4caf-a9a6-516505010225)

