# Creación de un corpus de poemas

Este proyecto consiste en la extracción automática de poemas desde la web para construir un corpus textual, el cual es posteriormente limpiado y analizado estadísticamente.

El objetivo principal es estudiar la estructura de los poemas (versos, estrofas, palabras) y explorar su relación con métricas como la popularidad.

---

## Objetivos
Aplicar técnicas de web scraping y procesamiento de texto para:
- Construir un corpus de poemas.
- Agregar metadatos.
- Limpiar y normalizar los textos.
- Analizar estadísticamente sus características estructurales.

---

## Tecnologías
- Python  
- Pandas  
- re  
- nltk  
- spacy  
- BeautifulSoup  
- requests  
- string  
- urllib  
- Matplotlib  
- seaborn  
- Google Colab  

---

## Estructura
CorpusPoemas/
│
├── Web_scraping.ipynb
├── Analisis_estadistico.ipynb
├── README.md
└── data/
└── poemas_completo.csv

- `Web_scraping.ipynb`: notebook para la extracción automática de poemas desde la web.  
- `Analisis_estadistico.ipynb`: notebook para el análisis estadístico del corpus.  
- `data/poemas_completo.csv`: dataset con el corpus de poemas extraídos con metadata.

## Uso
1. Clona el repositorio:
   ```bash
   git clone https://github.com/CSarabia-000/CorpusPoemas.git
2. Abre el archivo Analisis_estadistico.ipynb en Google Colab o Jupyter.
3. Ejecuta las celdas en orden.

## Autor
Carlos Sarabia



