<p align="center">
  <img width="148" height="148" alt="image" src="https://github.com/user-attachments/assets/6f4025d9-8d9e-4810-8ff6-7a3f49fcd139" />

</p>

<h1 align="center">
Análisis de Consumo Energético en una Industria
</h1>

<p align="center">
<strong>Universidad del Pacífico</strong><br>
Programa de Ingeniería de Sistemas<br>
Asignatura: Inteligencia Artificial
</p>

<p align="center">

![Python](https://img.shields.io/badge/Python-3.x-blue)
![NumPy](https://img.shields.io/badge/NumPy-Scientific_Computing-green)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical_Analysis-red)

</p>
---
<h2 align="center">📑 Tabla de Contenido</h2>

<p align="center">

<a href="#descripción-del-proyecto">Descripción del Proyecto</a> •
<a href="#objetivos">Objetivos</a> •
<a href="#integrantes">Integrantes</a> •
<a href="#información-académica">Información Académica</a><br>

<a href="#variables-del-dataset">Variables del Dataset</a> •
<a href="#herramientas-utilizadas">Herramientas Utilizadas</a> •
<a href="#análisis-estadístico-con-numpy">Análisis Estadístico</a><br>

<a href="#visualizaciones-con-matplotlib">Visualizaciones</a> •
<a href="#análisis-exploratorio-con-seaborn">Análisis Exploratorio</a> •
<a href="#resultados-del-análisis">Resultados</a><br>

<a href="#preguntas-del-taller">Preguntas del Taller</a> •
<a href="#propuesta-de-optimización-energética">Optimización Energética</a><br>

<a href="#conclusiones">Conclusiones</a> •
<a href="#aprendizajes-obtenidos">Aprendizajes</a> •
<a href="#trabajo-futuro">Trabajo Futuro</a><br>

<a href="#instalación">Instalación</a> •
<a href="#ejecución">Ejecución</a> •
<a href="#licencia">Licencia</a>

</p>

---

# Descripción del Proyecto

Este proyecto tiene como finalidad realizar un análisis exploratorio de datos sobre el consumo energético de una industria mediante la generación de datos sintéticos y la aplicación de técnicas de análisis estadístico y visualización de datos utilizando las librerías **NumPy**, **Matplotlib** y **Seaborn**.

A partir de una simulación de 500 registros diarios, se estudian las relaciones entre la producción industrial, las horas de operación, la temperatura ambiente y el consumo energético, con el objetivo de identificar patrones, tendencias y oportunidades de optimización.

---

# Objetivos

## Objetivo General

Analizar el comportamiento del consumo energético de una industria mediante herramientas de Ciencia de Datos e Inteligencia Artificial.

## Objetivos Específicos

- Generar datos sintéticos representativos de un año de operación industrial.
- Aplicar análisis estadístico utilizando NumPy.
- Construir visualizaciones con Matplotlib.
- Analizar correlaciones mediante Seaborn.
- Detectar posibles anomalías en el consumo energético.
- Formular estrategias para la optimización energética.

---

# Integrantes

| Nombre |
|----------|
| Kelly Jhoana Mosquera Urbano |
| Anyela Katerine Rentería Cumana |
| Juan Alejandro Roldán |

---

# Información Académica

| Información | Detalle |
|------------|---------|
| Universidad | Universidad del Pacífico |
| Programa | Ingeniería de Sistemas |
| Asignatura | Inteligencia Artificial |
| Docente | Wilman Andrés Quiñónez V. |
| Semestre | Octavo Semestre |
| Año | 2026 |

---

# Variables del Dataset

El conjunto de datos está conformado por las siguientes variables:

| Variable | Descripción | Tipo |
|------------|------------|------------|
| Día | Identificador del día registrado | Numérica |
| Producción_Diaria | Cantidad producida por día | Numérica |
| Horas_Operacion | Horas de funcionamiento de la planta | Numérica |
| Consumo_Energetico | Energía consumida (kWh) | Numérica |
| Temperatura_Ambiente | Temperatura registrada | Numérica |

---

# Herramientas Utilizadas

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook
- Google Colab
- GitHub

---

# Análisis Estadístico con NumPy

Se calcularon las principales métricas descriptivas del consumo energético:

- Consumo promedio.
- Consumo máximo.
- Consumo mínimo.
- Distribución de valores.
- Comportamiento general de la variable objetivo.

---

# Visualizaciones con Matplotlib

## Serie Temporal del Consumo Energético

Permite observar la evolución del consumo energético a lo largo del tiempo.

### Resultado

<p align="center">
<img width="1014" height="471" alt="image" src="https://github.com/user-attachments/assets/d590f9ff-cf82-49d6-bb59-6c7dfb2cbce0" />


</p>

---

## Histograma del Consumo Energético

Permite analizar la distribución de frecuencias del consumo energético.

### Resultado

<p align="center">
<img width="686" height="471" alt="image" src="https://github.com/user-attachments/assets/5e008ffe-cddb-4ccc-9548-81d280f5efde" />


</p>

---

## Gráfico de Dispersión

Relación entre la producción diaria y el consumo energético.

### Resultado

<p align="center">
<img width="704" height="471" alt="image" src="https://github.com/user-attachments/assets/30de2061-c15f-4201-994c-034a05f4d441" />



</p>

---

# Análisis Exploratorio con Seaborn

## Heatmap de Correlación

Permite identificar relaciones entre las variables numéricas.

### Resultado

<p align="center">
<img width="803" height="706" alt="image" src="https://github.com/user-attachments/assets/62285fb0-da07-4f8c-a7e3-7d0dbea118dc" />

</p>

---

## Pairplot

Visualización simultánea de relaciones entre variables.

### Resultado

<p align="center">
<img width="1231" height="1231" alt="image" src="https://github.com/user-attachments/assets/f7cd235d-1243-400b-9900-24cb7bd9846e" />


</p>

---

## Regplot

Permite observar tendencias y relaciones lineales.

### Resultado

<p align="center">
<img width="704" height="471" alt="image" src="https://github.com/user-attachments/assets/e11bef30-97e8-4da2-b8f0-cc27b102a117" />


</p>

---

# Resultados del Análisis

Después de analizar los datos obtenidos se identificó que:

- La producción diaria presenta una relación directa con el consumo energético.
- Las horas de operación influyen significativamente en el gasto energético.
- Existen días con consumos superiores al promedio que pueden considerarse anomalías.
- La temperatura ambiente presenta una influencia moderada sobre el consumo.

---

# Preguntas del Taller

## ¿Qué variables afectan el consumo energético?

Las variables que presentan mayor influencia son:

- Producción diaria.
- Horas de operación.
- Temperatura ambiente.

## ¿Existen días con comportamientos anómalos?

Sí. Algunos registros muestran consumos significativamente superiores al promedio general.

## ¿Cómo podría reducirse el gasto energético?

- Optimizando horarios de operación.
- Implementando mantenimiento preventivo.
- Sustituyendo equipos ineficientes.
- Monitoreando continuamente los indicadores energéticos.

---

# Propuesta de Optimización Energética

Con base en los resultados obtenidos se propone:

1. Implementar un sistema de monitoreo energético en tiempo real.
2. Optimizar la programación de la producción.
3. Reducir tiempos muertos de operación.
4. Realizar mantenimiento periódico de maquinaria.
5. Aplicar modelos predictivos para anticipar consumos elevados.

---

# Conclusiones

- Se logró generar y analizar un conjunto de datos sintéticos que representa el comportamiento energético de una industria durante un período de operación.

- El análisis estadístico permitió identificar tendencias generales del consumo energético, así como valores máximos, mínimos y promedios relevantes para la toma de decisiones.

- Las visualizaciones desarrolladas con Matplotlib facilitaron la comprensión del comportamiento de las variables y las relaciones existentes entre ellas.

- El análisis realizado con Seaborn permitió identificar correlaciones entre la producción diaria, las horas de operación, la temperatura ambiente y el consumo energético.

- Se evidenció que variables como la producción diaria y las horas de operación tienen una influencia significativa sobre el consumo energético de la industria.

- La detección de comportamientos atípicos demuestra la importancia del análisis de datos para optimizar procesos y reducir costos operativos.

---

# Aprendizajes Obtenidos

Durante el desarrollo de este proyecto se fortalecieron conocimientos relacionados con:

- Manipulación y análisis de datos utilizando la librería NumPy.
- Creación de gráficos estadísticos mediante Matplotlib.
- Desarrollo de análisis exploratorio de datos con Seaborn.
- Interpretación de métricas estadísticas para la toma de decisiones.
- Identificación de patrones y correlaciones entre variables.
- Aplicación de herramientas de Ciencia de Datos en contextos industriales.
- Uso de Python como herramienta para el análisis y visualización de información.

Asimismo, se comprendió la importancia de la analítica de datos dentro de los procesos industriales, permitiendo transformar datos en información útil para la optimización de recursos y la mejora de la eficiencia energética.

---

# Trabajo Futuro

Como trabajo futuro se propone:

- Implementar modelos predictivos de consumo energético mediante técnicas de aprendizaje automático.
- Incorporar más variables operativas para mejorar el análisis.
- Desarrollar tableros interactivos para el monitoreo en tiempo real.
- Evaluar diferentes estrategias de optimización energética basadas en los resultados obtenidos.

---

# Instalación

```bash
git clone https://github.com/TU_USUARIO/Analisis_Consumo_Energetico_IA.git
```

```bash
pip install numpy pandas matplotlib seaborn
```

---

# Ejecución

```bash
jupyter notebook
```

o abrir directamente en Google Colab.

---

# Licencia

Proyecto académico desarrollado para la asignatura de Inteligencia Artificial de la Universidad del Pacífico.

---

<p align="center">
<strong>Universidad del Pacífico</strong><br>
Programa de Ingeniería de Sistemas<br>
Buenaventura, Valle del Cauca - Colombia<br>
2026
</p>
