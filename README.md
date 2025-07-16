# Web Scraping POC with Databricks + PySpark

Este repositorio contiene un ejemplo simple de **web scraping** ejecutado desde un notebook en **Databricks**, usando Python con `requests` y `BeautifulSoup`, y transformando los resultados en un **DataFrame de PySpark**.

## 🚀 Objetivo

Demostrar cómo realizar scraping desde un clúster de Databricks sin necesidad de Selenium o renderizado JavaScript, ideal para sitios simples con HTML estático.

Se extraen frases públicas desde el sitio [quotes.toscrape.com](https://quotes.toscrape.com), una web creada para prácticas de scraping.

## 🧪 Tecnologías utilizadas

- Python 3 (en entorno Databricks)
- `requests`
- `beautifulsoup4`
- Apache Spark (a través de PySpark en Databricks)

## 📦 Instalación

Desde una celda en tu notebook de Databricks, ejecuta:

```python
%pip install requests beautifulsoup4
