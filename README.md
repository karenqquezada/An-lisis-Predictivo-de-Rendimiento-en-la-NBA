
# Análisis Predictivo de Rendimiento en la NBA

Proyecto Final – Data Analytics

---

## Caso de Negocio

###  Industria y Contexto
La **NBA** es una liga profesional de baloncesto que genera una gran cantidad de datos por partido.  
Analizar esta información permite identificar **métricas clave que impactan el rendimiento colectivo de los equipos** y mejorar las estrategias de juego.

###  Descripción del Problema
Actualmente, los equipos tienen dificultades para determinar de forma objetiva **qué jugadores y estadísticas influyen más en la probabilidad de victoria**.  
Esto limita la capacidad de los entrenadores y analistas para tomar decisiones tácticas basadas en datos.

###  Objetivo Principal
Evaluar y predecir cómo el **rendimiento de los jugadores impacta en la probabilidad de victoria del equipo**, identificando las **métricas estadísticas más relevantes**.

###  Resultados Esperados e Impacto
- Dashboard interactivo con **KPIs de jugadores y equipos**.  
- **Modelo predictivo (Regresión Lineal/Logística)** que estime la probabilidad de victoria.  
- Identificación de **jugadores y métricas clave** para la toma de decisiones estratégicas.  
- **Mejora en la toma de decisiones** basada en evidencia estadística.

---

## 👥 Integrantes del Equipo
- **Soto Quezada, Karen Quetzali** – Data Analyst   
- **González Pacheco, Esther Isabel** – Data Analyst  


---

## Fuentes de Datos

Los datos provienen del dataset público de Kaggle:  
🔗 [Basketball Dataset (NBA) – Wyattowalsh](https://www.kaggle.com/datasets/wyattowalsh/basketball)

Principales archivos:
- `common_player_info.csv`: Información general de jugadores.  
- `draft_combine_stats.csv`: Resultados físicos y técnicos del Draft Combine.  
- `draft_history.csv`: Historial de selecciones del Draft.  
- `game.csv`: Resultados y estadísticas de partidos.  
- `team.csv`, `team_details.csv`, `team_history.csv`: Datos de equipos.  
- `other_stats.csv`, `play_by_play.csv`: Estadísticas avanzadas y jugadas.  

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

##  Modelado Predictivo
- Aplicación de **Regresión Lineal y Logística** con *Scikit-learn*.  
- Identificación de variables con mayor influencia en la probabilidad de victoria.  
- Simulación de escenarios de rendimiento y comparación de resultados.

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

## 🧠 Tecnologías Utilizadas
| Etapa | Herramientas |
|--------|----------------|
| Limpieza y ETL | Python (Pandas, NumPy) |
| Base de Datos | SQL Server |
| Análisis y Modelado | Scikit-learn |
| Visualización | Power BI |
| Control de Versiones | Git + GitHub |

---

## 🔄 Flujo de Datos
