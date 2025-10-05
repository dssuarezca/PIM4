# 🦠 LATAM_COVID-19

El principal propósito del proyecto es según el análisis, los gráficos y los insights
descubiertos, encontrar las diferentes áreas prioritarias que necesiten de nuestros
servicios para tener la posibilidad de expandirnos con el objetivo de bajar los casos
confirmados y aumentar el número de casos recuperados de los países más afectados
por esta pandemia.

---
## 📚 Tabla de contenidos

- [📌 Objetivo](#-objetivo)
- [🌎 Alcance Geográfico](#-alcance-geográfico)
- [📊 Datos Utilizados](#-datos-utilizados)
- [🧰 Herramientas y Tecnologías](#-herramientas-y-tecnologías)
- [📁 Estructura del Repositorio](#-estructura-del-repositorio)
- [📈 Visualizaciones Destacadas](#-visualizaciones-destacadas)
- [🚀 Cómo ejecutar el proyecto](#-cómo-ejecutar-el-proyecto)
- [📊 Visualizacion del Informe en Power BI](#-visualizacion-del-informe-en-power-bi)
- [🧠 Posibles mejoras](#-posibles-mejoras)
- [📥 Fuente de datos](#-fuente-de-datos)
- [📜 Licencia](#-licencia)
- [✒ Autor](#-autor)

---

## 📌 Objetivo

    • Aplicar técnicas de carga, filtrado, limpieza y transformación de datos
    utilizando Python.
    • Aplicar herramientas avanzadas de análisis estadístico y visualización, tales
    como histogramas, gráficos de barras y mapas de calor para realizar análisis
    exploratorio.
    • Emplear técnicas avanzadas de pandas y numpy, explorando series temporales,
    identificando tendencias a largo plazo como pueden ser patrones estacionales.
    • Por ultimo entender como exportar los datos a la herramienta power bi, donde
    se diseñaran dashboard interactivos, con el fin de que el cliente pueda
    comprender mejor la información y pueda interactuar con ella, consiguiendo una 
    experiencia agradable al usuario y poder mostrar los insgiths más valiosos de
    la problemática planteada.

---



## 🌎 Alcance Geográfico

Se analizan principalmente los siguientes países de América Latina:

- Argentina
- Brasil
- Chile
- Colombia
- México
- Perú

---

## 📊 Datos Utilizados

Los datos provienen de fuentes públicas y confiables, incluyendo:

- [Google drive HENRY](https://drive.google.com/file/d/18FGvT2x1nqA5TQ22P5FyJ5eLXlHprqzj/view)
- [Johns Hopkins CSSE](https://github.com/CSSEGISandData/COVID-19)
- [Ministerios de Salud locales]

Los datasets se encuentran en la carpeta [`./Data`](./data/), tanto los datos crudos como procesados

---

## 🧰 Herramientas y Tecnologías

- Python 3.12
- pandas, numpy
- matplotlib, seaborn
- Jupyter Notebook
- Power BI
---

## 📁 Estructura del Repositorio

```
BYOGENESIS/
├── Data/
│   └── processed/
├── Informes/
│   ├── README.md 
│   ├── Imagenes/
│   └── Graficos/
├── Notebook/
│   └── processed/
├── powerbi/
│   └── informe_covid_latam.pbix
└── README.md

```
powerbi

---

## 📈 Visualizaciones Destacadas

Este proyecto incluye un conjunto de visualizaciones interactivas desarrolladas en Power BI que permiten explorar la evolución del COVID-19 en América Latina desde múltiples dimensiones.

Entre las más destacadas se encuentran:

- Evolución diaria de casos confirmados y muertes
- Tasas de vacunación por país
- Comparación regional del crecimiento de contagios
- Mapas de calor y tendencias acumuladas

➡️ Podés explorarlas en detalle en el archivo `informe_covid_latam.pbix` y en el informe completo ubicado en la carpeta [`informe/`](./informe/).


---

## 🚀 Cómo ejecutar el proyecto

Este proyecto se ejecuta en notebooks de Jupyter, por lo que es recomendable contar con un entorno Python configurado con las siguientes librerías:

- pandas
- numpy
- matplotlib
- seaborn
- scipy

### 1. Clonar el repositorio

```bash
git clone https://github.com/eremohn/LATAM_COVID-19.git
cd LATAM_COVID-19
```
---

## 📊 Visualizacion del Informe en Power BI

Además del informe detallado disponible en formato Markdown dentro de la carpeta [`informe/`](./informe), existe una visualización interactiva en Power BI que permitirá explorar de forma dinámica los principales indicadores relacionados con el impacto del COVID-19 en Latinoamérica.

🔹 Esta visualización permitirá:
- Filtrar por país y año.
- Comparar tasas de mortalidad, vacunación, y casos confirmados.
- Visualizar relaciones entre variables socioeconómicas, sanitarias y demográficas.

📁 El archivo `.pbix` estara disponible en la carpeta [`powerbi/`](./powerbi), o será publicado a través de Power BI Service con un enlace directo aquí.


---
## 🧠 Posibles mejoras
- Implementar una app interactiva con Streamlit o Dash

- Incorporar modelos predictivos (SIR, ARIMA, Prophet)

- Automatizar limpieza de datos con notebooks reutilizables

- Agregar visualizaciones geográficas

---

## 📥 Fuente de datos

Debido al tamaño del archivo crudo (2.4 GB), no se encuentra almacenado directamente en el repositorio.

Puedes acceder y descargar el dataset desde el siguiente enlace:

- [📊 Dataset de COVID-19 (Google Drive)](https://drive.google.com/file/d/1asTXNEx_IGFDheRIDqPteII12Iz7Ghj2/view?usp=drive_link)

Una vez descargado, colocá el archivo dentro del directorio `data/raw/`.

---

## 📜 Licencia

Este proyecto se publica bajo la licencia [MIT](LICENSE).

---

## ✒ Autor

Daniel Suarez – [GitHub](https://github.com/dssuarezca)  
Egresado bootcamp Henry Data Analytics | Analista de Datos |

---