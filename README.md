# 📊 Proyecto Bimestral – Análisis de Datos Académicos con KNIME

## 📌 Introducción
Este proyecto tiene como objetivo aplicar un proceso completo de análisis de datos utilizando múltiples fuentes y formatos, abarcando desde la carga y limpieza de datos hasta el análisis estadístico y visualización de resultados, haciendo uso de la herramienta KNIME.
El estudio se enfoca en el rendimiento académico de estudiantes de último año de una escuela secundaria donde califican entre 0-100, analizando variables como calificaciones, horas de estudio, ausencias y condiciones laborales.
---
## 🎯 Objetivos
### Objetivo general
Analizar el rendimiento académico de estudiantes a partir de múltiples fuentes de datos mediante técnicas de limpieza, consolidación, análisis estadístico y visualización.
### Objetivos específicos
- Cargar datos desde diferentes fuentes (CSV, JSON, SQLite y MongoDB).
- Limpiar los datos eliminando duplicados y corrigiendo valores inconsistentes.
- Consolidar todas las fuentes en un único conjunto de datos.
- Analizar los estadísticos del estudio.
- Visualizar gráficas relevantes para la toma de decisiones.
- Documentar todo el proceso del proyecto.

---

## 🧪 Caso de estudio
El caso de estudio analiza información académica de estudiantes, incluyendo:
- Calificaciones por materia
- Horas de autoestudio
- Ausencias
- Trabajo de medio tiempo
- Aspiraciones profesionales
- Actividades extracurriculares, etc.

---

## 📂 Fuentes de datos
Se utilizaron múltiples fuentes de datos en diferentes formatos:

- 📄 CSV: Registros académicos
- 📄 JSON: Información completa de los estudiantes
- 🗄️ SQLite: Base de datos relacional local
- ☁️ MongoDB: Base de datos NoSQL en la nube

---

## ⚙️ Proceso del proyecto
### 1️⃣ Carga de datos
Los datos fueron cargados en KNIME utilizando nodos como:
- CSV Reader
- JSON Reader
- DB Reader (SQLite)
- MongoDB Reader

---
### 2️⃣ Consolidación
Las distintas fuentes fueron concatenadas para obtener una vista global del conjunto de datos, permitiendo detectar duplicados entre orígenes.

---

### 3️⃣ Limpieza de datos
Se realizó limpieza posterior a la consolidación:
- Eliminación de duplicados
- Corrección de tipos de datos
- Tratamiento de valores nulos
- Estandarización de columnas

---

### 4️⃣ Análisis de datos
Se calcularon estadísticas descriptivas:
- Media
- Mínimo
- Máximo
- Mediana
- Desviación estándar
- Porcentaje de valores sucios

Además, se creó una columna de promedio general por estudiante.

---

### 5️⃣ Visualización
Se generaron las siguientes gráficas:
- Gráficas de barras (promedios por materia)
- Line plot (distribución de género por materia con un nodo que muestra las 5 primeras filas de datos)
- Diagramas de dispersión (Promedio total por estudiante)
- Box Plot (Notas por materias, en este caso seleccionamos 4 categorias y detección de outliers)
- Pie chart (Análisis por carrera y la suma de faltas)
- Stacked area chart (Conteo de personas dentro de una carrera)


## 🚀 Despliegue
El proyecto fue desarrollado en KNIME y los resultados se presentan mediante visualizaciones generadas dentro del entorno.  
El repositorio GitHub contiene los workflows, datasets y documentación del proyecto. Además, se implementó dos metodos del despliegue:
- El primero fue por medio dle KNIME con un nodo llamado Report HTML writer que permite importar un archivo html para posteriormente realizar el despliegue en otra aplicación:
- El segundo fue mediante descargas del las graficas y adjuntado a un codigo html y desplegarlo a un servidor. Link del proyecto realizado manualmente: [https://analisis-graficos.netlify.app/](https://analisis-graficos.netlify.app/)

---

## 🧠 Conclusiones
El proyecto permitió aplicar un flujo completo de análisis de datos, fortaleciendo conocimientos en carga, limpieza, consolidación, análisis estadístico y visualización de información utilizando KNIME.

---

## 🔮 Recomendaciones y trabajos futuros
- Automatizar la carga de datos desde APIs.
- Desplegar las visualizaciones en una aplicación web interactiva.
- Aplicar técnicas de Machine Learning para análisis avanzado.
- Implementar IA para faciliatr la limpieza de datos.

---

## 👥 Integrantes del grupo
- Santiago Vargas
- Alejandro Proño
- Kyara Altamirano
