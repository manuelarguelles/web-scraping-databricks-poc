# 🕸️ Web Scraping con Databricks + PySpark: Casos Prácticos

Este repositorio demuestra cómo realizar **web scraping** en un entorno **Databricks**, utilizando Python (`requests`, `BeautifulSoup`) para extraer datos de páginas web y transformarlos en **DataFrames de PySpark** para su posterior análisis.

---

## 🎯 Objetivo

Explorar técnicas de scraping ejecutables directamente desde notebooks en Databricks, sin necesidad de renderizado JavaScript o herramientas como Selenium. Ideal para entornos de datos donde se requiere automatizar la captura de contenido web estructurado.

---

## 📚 Casos incluidos

### 🔹 Versión 1: Scraping HTML estático
- **Sitio web:** [quotes.toscrape.com](https://quotes.toscrape.com)
- **Descripción:** Extrae frases de ejemplo desde una página HTML simple y las carga como DataFrame.
- **Tecnologías:** `requests`, `BeautifulSoup`, `PySpark`

### 🔹 Versión 2: Scraping desde Google Sheets pública
- **Fuente:** Google Sheets publicada como HTML
- **URL:** [Ver hoja de ejemplo](https://docs.google.com/spreadsheets/d/e/2PACX-1vQzWjN8VvkgwCAffEnVvtt-otYKC3NCUKmWtC47CmKc-r9TJKjNfnkacij9C2wE_A/pubhtml)
- **Descripción:** Extrae filas de una hoja pública en Google Sheets y las convierte en un DataFrame.

---

## 🧪 Tecnologías utilizadas

- **Databricks (entorno notebook)**
- **Python 3**
- `requests` – para obtener el HTML de las páginas web  
- `beautifulsoup4` – para parsear y extraer datos del HTML  
- `PySpark` – para transformar los datos en DataFrames y visualizarlos

---

## ⚙️ Instalación de dependencias

Ejecuta en una celda de tu notebook Databricks:

```python
%pip install requests beautifulsoup4
