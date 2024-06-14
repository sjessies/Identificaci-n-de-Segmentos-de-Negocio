# Identificación de Segmentos de Negocio Potenciales mediante Modelos de Clasificación Multi-Etiqueta

## Descripción
En el dinámico entorno empresarial actual, la diversificación hacia nuevos segmentos de negocio se ha convertido en una estrategia esencial para el crecimiento y la resiliencia de las organizaciones. Este proyecto aborda el desafío de identificar segmentos de negocio prometedores mediante técnicas de aprendizaje automático y análisis de datos avanzados.

## Planteamiento del Problema
La diversificación hacia nuevos segmentos de negocio es crucial para el crecimiento y resiliencia de las organizaciones en el entorno empresarial actual. Sin embargo, identificar de manera efectiva estos segmentos potenciales representa un desafío, dado el complejo entramado de los ecosistemas empresariales y la escasez de datos e interpretaciones adecuadas. Los enfoques tradicionales de diversificación a menudo resultan limitados al enfocarse en expandir lo existente, perdiendo oportunidades de innovar.

## Justificación
La diversificación corporativa se ha convertido en una estrategia central para el crecimiento y la sostenibilidad de las organizaciones. Sin embargo, identificar nuevos segmentos de negocio potenciales para diversificar sigue siendo un desafío. Este proyecto busca contribuir al ámbito de la diversificación empresarial mediante la identificación de nuevos segmentos de negocio mediante técnicas de aprendizaje automático.

## Objetivos
### Objetivo General
Crear un sistema de identificación de territorios de interés empresarial utilizando clasificadores multi-etiqueta, con el fin de analizar y evaluar segmentos de negocio potenciales que promuevan la diversificación corporativa.

### Objetivos Específicos
- Recopilar y preparar conjuntos de datos relevantes que incluyan información sobre la empresa, su mercado y variables relacionadas con la identificación de segmentos de negocio.
- Seleccionar, analizar y comparar algoritmos de Machine Learning para identificar patrones, tendencias y segmentos de negocio prometedores.
- Evaluar la eficacia y precisión de los modelos de Machine Learning desarrollados en la identificación de segmentos de negocio con potencial para la diversificación empresarial.

## Estructura del Repositorio
- **data/**: Contiene los conjuntos de datos.
  - **raw/**: Datos sin procesar.
    - **Forbes_2000_2023_all_companies.xlsx**: Archivo Excel con información de las compañías.
    - **df_for_EDA_full_tickers.xlsx**: Archivo Excel con tickers para EDA.
  - **processed/**: Datos procesados.
    - **companies_base_1763.csv**: Archivo CSV con datos procesados de las compañías.
    - **df_datos_financieros_final.csv**: Archivo CSV con datos financieros finales después de la imputación.
    - **df_segmentos.csv**: Archivo CSV con los segmentos de negocio.
    - **datos_finales.csv**: Archivo CSV con datos finales para modelos de clasificación.
  - **external/**: Datos de fuentes externas.
    - **Diccionario de datos.xlsx**: Archivo Excel con el diccionario de datos para seleccionar características.
    - **Homologación Segmentos.xlsx**: Archivo Excel para homologar nombres y datos de los segmentos.
- **notebooks/**: Notebooks de Jupyter.
  - **exploratory/**: Análisis exploratorio de datos.
    - **companies_info_scraping_notebook.ipynb**: Notebook para scraping de información usando Beautiful Soup.
    - **EDA_Imputacion_Datos.ipynb**: Notebook para EDA y la imputación de datos nulos.
  - **final/**: Notebooks finales con resultados principales.
    - **clasificación_multietiqueta.ipynb**: Notebook para el modelo de clasificación multi-etiqueta.
    - **clasificación_simple.ipynb**: Notebook para el modelo de clasificación simple.
- **reports/**: Reportes y figuras generadas.
  - **figures/**: Imágenes y gráficos.
- **ticker_data_1760/**: Carpeta para guardar la información descargada usando yfinance.
- **docs/**: Documentación del proyecto.
  - **additional_docs/**: Documentación adicional.

## Instalación y Configuración
Instrucciones para configurar el entorno y ejecutar el proyecto.

## Uso
Ejemplos de cómo usar el proyecto.

## Contribución
Guía para contribuir al proyecto.

## Licencia
Este proyecto está licenciado bajo la Licencia MIT - ver el archivo LICENSE para más detalles.