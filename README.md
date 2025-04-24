Guía para instalar MIMIC IV en PostgreSQL utilizando contenedores de Docker en Windows
=================

### Autores

| Autor                      | Origen                               |
| -------------------------- | ------------------------------------ |
| Emmanuel Gutiérrez Jiménez | Universidad del Norte                |
| José Duván Márquez Díaz    | Universidad del Norte                |

### Créditos

Este tutorial es adaptado del entregado por los creadores de MIMIC-IV en: https://mimic.physionet.org/tutorials/

### Resumen

Este repositorio proporciona una guía práctica y reproducible para la instalación del conjunto de datos clínicos MIMIC-IV en una base de datos PostgreSQL utilizando Docker. Está diseñado para facilitar el despliegue local del entorno de análisis, especialmente para investigadores, científicos de datos y profesionales de la salud interesados en explorar información crítica de pacientes hospitalizados. La guía incluye la configuración del contenedor de base de datos, la carga automatizada de los archivos CSV de MIMIC-IV y recomendaciones para el acceso eficiente a los datos desde herramientas analíticas como Python, R o Jupyter. El objetivo principal es acelerar la preparación del entorno de trabajo para investigaciones en salud, machine learning y análisis clínico reproducible.

### Estado del trabajo 

| Estado            | Descripción                          |
| ----------------- | ------------------------------------ |
| <img src="https://img.shields.io/badge/Study%20Status-Design%20Finalized-brightgreen.svg" alt="Study Status: Design Finalized"> | Trabajo finalizado. | 

### Palabras claves

- `MIMIC-IV`
- `PostgreSQL`
- `Docker`
- `Dataset Patients`
- `Predictive Models`
- `CSV`

### Paso 1. Descargar los archivos csv desde el sitio oficial de MIMIC-IV

### Paso 1. Instalar docker en Windows

### Paso 2. Instalar contenedores de Postgres y Jupyter

#### Paso 2.1. Crear workspace en Visual Studio Code
#### Paso 2.2. Crear Docker-Composer.yml
#### Paso 2.3. Ejecutar creación de contenedores desde Visual Studio Code

#### Paso 3.1. Conectarse a la base de datos con usuario Postgres
#### Paso 3.2. Crear base de datos: mimiciv
#### Paso 3.3. Crear schema: mimiciv

### Paso 3. Configuración de la base de datos

#### Paso 3.1. Conectarse a Postgres
#### Paso 3.2. Crear base de datos: mimiciv
#### Paso 3.3. Crear schema: mimiciv
#### Paso 3.4. Crear tablas dentro del schema: mimiciv

### Paso 4. Importar CSV en tablas de la base de datos

#### Paso 4.1. Importar tablas de CORE
#### Paso 4.2. Importar tablas de ICU
#### Paso 4.2. Importar tablas de HOSP

### Paso 5. Crear indices en las tablas de la base de datos para mejorar el desempeño de las consultas a la base de datos

### Paso 6. Verificar el contenido de las filas en cada una de las tablas











