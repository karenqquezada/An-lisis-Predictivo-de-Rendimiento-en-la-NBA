<p align="center">
  <img src="https://github.com/karenqquezada/An-lisis-Predictivo-de-Rendimiento-en-la-NBA/blob/main/NBA-logo-baloncesto-historia-deporte-estados-unidos.jpg" width="300" alt="NBA Logo">
</p>

<h1 align="center">Análisis de Rendimiento en la NBA</h1>

<p align="center">
  <em>Proyecto de análisis de rendimiento y métricas de equipos y jugadores de la NBA, utilizando Python, SQL Server y Power BI.</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white"/>
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
  <img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white"/>
</p>

---

### Proyecto Final – Data Analytics

---

## Caso de Negocio

###  Industria y Contexto
La **NBA** es una liga profesional de baloncesto que genera una gran cantidad de datos por partido.  
Analizar esta información permite identificar **métricas clave que impactan el rendimiento colectivo de los equipos** y mejorar las estrategias de juego.

###  Descripción del Problema
Analizar el impacto de los equipos de la NBA en el resultado de los partidos. Identificando patrones que permitan analizar el rendimiento y apoyar decisiones estratégicas basadas en datos.

###  Objetivo Principal
Atendiendo a las necesidades del inversor deportivo interesado en adquirir o patrocinar un equipo profesional, que solicita un análisis de desempeño y proyección de equipos; considerando las variables claves del jugador como factor ccomplementario.

###  Resultados Esperados e Impacto
- Dashboard interactivo con **KPIs de jugadores y equipos**.  
- Identificación de **equipos y jugadores con métricas clave** para la toma de decisiones estratégicas.  
- **Mejora en la toma de decisiones** basada en evidencia estadística.

---

##  Integrantes del Equipo
- **Soto Quezada, Karen Quetzali** – Data Analyst   
- **González Pacheco, Esther Isabel** – Data Analyst  


---

## Fuentes de Datos

Los datos provienen del dataset público de Kaggle:  
🔗 [Basketball Dataset (NBA) – Wyattowalsh](https://www.kaggle.com/datasets/wyattowalsh/basketball)

Principales archivos:
- `dim_jugador.csv`: Información general de jugadores.  
- `dim_timepo.csv`: Resultados estacionales.  
- `dim_estadio.csv`: Historial de selecciones del estadio.  
- `fact_partidos.csv`: Resultados y estadísticas de partidos.  
- `dim_team.csv`: Datos de equipos.  
- `play_by_play.csv`: Estadísticas avanzadas y jugadas.  

---

##  Plan de Acción y Estrategia Analítica

### Sprint 1 – Implementación del Origen de Datos
- Creación del repositorio público en **GitHub** y estructura de carpetas.  
- Identificación de archivos relevantes y definición de modelo entidad–relación.  
- Creación de la base de datos en **SQL Server**.  
- Diseño de las tablas y carga inicial de los datos.  
- Validación de accesos y consultas del equipo.  
- Implementación de un flujo de **automatización para ingesta de nuevos datos**.

### Sprint 2 – Desarrollo del Informe
- Creación del archivo `.pbix` en **Power BI**.  
- Limpieza y transformación de los datos.  
- Creación de medidas, columnas calculadas y relaciones entre tablas.  
- Diseño de visualizaciones y KPIs.  
- Etapa de **pruebas de calidad del reporte**.

---

##  Análisis Exploratorio (EDA)
- Análisis de **patrones y tendencias** en rendimiento de jugadores y equipos.  
- Identificación de **correlaciones clave** entre métricas y victorias.  
- Análisis de **eficiencia ofensiva y defensiva**.  
- Uso de **Python (Pandas, NumPy, Seaborn, Matplotlib)**.

---


## Visualización de Resultados
Dashboard interactivo en **Power BI** con indicadores como:
- Puntos promedio por jugador y equipo  
- Asistencias promedio  
- Rebotes ofensivos y defensivos  
- Porcentaje de victorias  
- Eficiencia individual (PER)  
- Desempeño local vs visitante  

Incluye segmentadores, bookmarks y actualización automática.

---

## Tecnologías Utilizadas
| Etapa | Herramientas |
|--------|----------------|
| Limpieza y ETL | Python (Pandas, NumPy) |
| Base de Datos | SQL Server |
| Análisis y Modelado | Scikit-learn |
| Visualización | Power BI |
| Control de Versiones | Git + GitHub |

---

## Flujo de Datos del Proyecto NBA

| 🔹 **Fuente de Datos** | 🧩 **Procesamiento (ETL)** | 🗄️ **Almacenamiento** | 📊 **Visualización** | ⚙️ **Automatización** |
|:----------------------:|:--------------------------:|:----------------------:|:---------------------:|:---------------------:|
| 📁 **CSV (Kaggle)** | 🐍 **Python – Limpieza y Transformación (ETL)** | 💾 **SQL Server – Modelo Estrella** | 📈 **Power BI – Dashboard Interactivo** | 🔁 **Actualización automática de datos y KPIs** |



