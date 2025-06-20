# 📈 Final Stock Analysis: Tesla & GameStop

Este proyecto fue desarrollado como parte de una actividad práctica del curso de análisis de datos de IBM. El objetivo es aplicar herramientas de Python para obtener, limpiar y visualizar datos reales del mercado de valores.

---

## 🧰 Tecnologías utilizadas

- **Python 3**
- **yfinance** – para extraer datos históricos del mercado.
- **BeautifulSoup** y **requests** – para hacer web scraping de ingresos trimestrales.
- **pandas** – para limpiar, transformar y analizar datos.
- **plotly** – para graficar series temporales interactivas.

---

## 📊 Qué hace este código

- Extrae precios históricos de las acciones de Tesla (`TSLA`) y GameStop (`GME`).
- Extrae ingresos trimestrales desde páginas HTML mediante web scraping.
- Limpia los datos financieros eliminando comas, signos de dólar y filas vacías.
- Grafica en un solo panel el precio de la acción y los ingresos para ambas compañías usando `plotly`.

---

## 🧪 Cómo correrlo

1. Instalá las dependencias:
   ```bash
   pip install yfinance beautifulsoup4 pandas plotly
