<p align="center">
  <img src="images/logo_unipacifico.png" width="180">
</p>

<h1 align="center">📊 Análisis de Consumo Energético en una Industria</h1>

<h3 align="center">
Universidad del Pacífico <br>
Programa de Ingeniería de Sistemas <br>
Inteligencia Artificial
</h3>

<p align="center">

![Python](https://img.shields.io/badge/Python-3.x-blue)
![NumPy](https://img.shields.io/badge/NumPy-Scientific_Computing-green)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical_Analysis-red)

</p>

---

# 📖 Descripción del Proyecto

Este proyecto tiene como finalidad realizar un análisis exploratorio de datos sobre el consumo energético de una industria mediante la generación de datos sintéticos y la aplicación de técnicas de análisis estadístico y visualización de datos utilizando las librerías **NumPy**, **Matplotlib** y **Seaborn**.

A partir de una simulación de **500 registros diarios**, se estudian las relaciones entre la producción industrial, las horas de operación, la temperatura ambiente y el consumo energético, con el objetivo de identificar patrones, tendencias y oportunidades de optimización.

---

# 🎯 Objetivos

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

# 👨‍💻 Integrantes

| Nombre |
|----------|
| Kelly Jhoana Mosquera Urbano |
| Anyela Katerine Rentería Cumana |
| Juan Alejandro Roldán |

---

# 👨‍🏫 Información Académica

| Información | Detalle |
|------------|---------|
| Universidad | Universidad del Pacífico |
| Programa | Ingeniería de Sistemas |
| Asignatura | Inteligencia Artificial |
| Docente | Wilman Andrés Quiñónez V. |
| Semestre | Octavo Semestre |
| Año | 2026 |

---

# 📂 Variables del Dataset

El conjunto de datos está conformado por las siguientes variables:

| Variable | Descripción | Tipo |
|------------|------------|------------|
| Día | Identificador del día registrado | Numérica |
| Producción_Diaria | Cantidad producida por día | Numérica |
| Horas_Operacion | Horas de funcionamiento de la planta | Numérica |
| Consumo_Energetico | Energía consumida (kWh) | Numérica |
| Temperatura_Ambiente | Temperatura registrada | Numérica |

---

# 🛠️ Herramientas Utilizadas

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook
- Google Colab
- GitHub

---

# 📊 Análisis Estadístico con NumPy

Se calcularon las principales métricas descriptivas del consumo energético:

- Consumo promedio.
- Consumo máximo.
- Consumo mínimo.
- Distribución de valores.
- Comportamiento general de la variable objetivo.

---

# 📈 Visualizaciones con Matplotlib

## Serie Temporal del Consumo Energético

Permite observar la evolución del consumo energético a lo largo del tiempo.

### Resultado

<p align="center">
<img src="images/serie_temporal.png" width="800">
</p>

---

## Histograma del Consumo Energético

Permite analizar la distribución de frecuencias del consumo energético.

### Resultado

<p align="center">
<img src="images/histograma_consumo.png" width="800">
</p>

---

## Gráfico de Dispersión

Relación entre la producción diaria y el consumo energético.

### Resultado

<p align="center">
<img src="images/dispersion_consumo.png" width="800">
</p>

---

# 🔥 Análisis Exploratorio con Seaborn

## Heatmap de Correlación

Permite identificar relaciones entre las variables numéricas.

### Resultado

<p align="center">
<img src="images/heatmap.png" width="800">
</p>

---

## Pairplot

Visualización simultánea de relaciones entre variables.

### Resultado

<p align="center">
<img src="images/pairplot.png" width="800">
</p>

---

## Regplot

Permite observar tendencias y relaciones lineales.

### Resultado

<p align="center">
<img src="images/regplot.png" width="800">
</p>

---

# 🔎 Resultados del Análisis

Después de analizar los datos obtenidos se identificó que:

✅ La producción diaria presenta una relación directa con el consumo energético.

✅ Las horas de operación influyen significativamente en el gasto energético.

✅ Existen días con consumos superiores al promedio que pueden considerarse anomalías.

✅ La temperatura ambiente presenta una influencia moderada sobre el consumo.

---

# ❓ Preguntas del Taller

## ¿Qué variables afectan el consumo?

Las variables que presentan mayor influencia son:

- Producción diaria.
- Horas de operación.
- Temperatura ambiente.

---

## ¿Existen días anómalos?

Sí. Algunos registros muestran consumos significativamente superiores al promedio general.

---

## ¿Cómo podría reducirse el gasto energético?

- Optimizando horarios de operación.
- Implementando mantenimiento preventivo.
- Sustituyendo equipos ineficientes.
- Monitoreando continuamente los indicadores energéticos.

---

# 💡 Propuesta de Optimización Energética

Con base en los resultados obtenidos se propone:

1. Implementar un sistema de monitoreo energético en tiempo real.
2. Optimizar la programación de la producción.
3. Reducir tiempos muertos de operación.
4. Realizar mantenimiento periódico de maquinaria.
5. Aplicar modelos predictivos para anticipar consumos elevados.

---

# 📁 Estructura del Proyecto

```text
📦 Analisis_Consumo_Energetico
│
├── 📂 data
│   └── datos_industria.csv
│
├── 📂 images
│   ├── serie_temporal.png
│   ├── histograma_consumo.png
│   ├── dispersion_consumo.png
│   ├── heatmap.png
│   ├── pairplot.png
│   └── regplot.png
│
├── 📂 notebooks
│   └── Taller_NumPy_Matplotlib_Seaborn.ipynb
│
├── requirements.txt
│
└── README.md
```

# 🚀 Instalación

```bash
git clone https://github.com/TU_USUARIO/TU_REPOSITORIO.git
```

```bash
pip install numpy pandas matplotlib seaborn
```

---

# ▶️ Ejecutar Proyecto

```bash
jupyter notebook
```

o abrir directamente en Google Colab.

---

# 📜 Licencia

Proyecto desarrollado con fines académicos para la asignatura de Inteligencia Artificial de la Universidad del Pacífico.

---

<p align="center">
<b>Universidad del Pacífico</b><br>
Ingeniería de Sistemas<br>
Buenaventura - Valle del Cauca<br>
2026
</p># Analisis_Consumo_Energetico_IA
