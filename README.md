# Análisis del Impacto de los Discursos de la FED en los Rendimientos de los del Bonos Tesoro de EE. UU  
### Realizado por: Arturo Velasco Valero, Enrique Muñoz Fernández y Marta Llanos Rodríguez
### Dirigido por: Gabriel Antonio Valverde Castilla

## 1. Introducción al trabajo
En este estudio se emplea Python como lenguaje de programación para desarrollar modelos de análisis de sentimientos y predicción de rendimientos de bonos del tesoro de EE. UU. Se aborda la influencia de discursos de representantes de la Reserva Federal en las predicciones financieras. La metodología se basa en la síntesis de estos modelos para mejorar la precisión de las predicciones económicas.

## 2. Fuentes de datos
- **Discursos:** Se han seleccionado los discursos en bruto de diferentes representantes de la Reserva Federal de los Estados Unidos desde el año 2010 al 2024. Han sido extraidos de la página oficial de la [Reserva Federal de los Estados Unidos](https://www.federalreserve.gov/newsevents/speeches.htm). Si se necesitase el fichero, puede enviar un correo a martallanos3@gmail.com. 
- **Datos de precios:** Los datos sobre rendimientos de bonos americanos a 10 años se obtienen de la web [Macrotrends](https://www.macrotrends.net/2016/10-year-treasury-bond-rate-yield-chart), una herramienta útil para analistas e inversores. También del 2010 al 2024. 

## 3. Análisis de texto
- [**Análisis inicial del dataset:**](Analisis_inicial_dataset.ipynb) Exploración y limpieza inicial de los discursos. 
- [**Modelo LDA:**](Analisis_de_texto_LDA.ipynb) Implementación del modelo de Latent Dirichlet Allocation (LDA) para la extracción de tópicos. 
- [**Análisis posterior:**](Análisis_final_palabras.ipynb) Análisis detallado de palabras y visualización de los resultados obtenidos del modelo LDA por mandato. 

## 4. Análisis de predicciones
- [**Modelos no lineales:**](USbonds_Modelos_prediccion.ipynb) Descripción y evaluación de los diferentes modelos no lineales empleados: LSTM, XGBOOST y RRN. 
- [**Modelo final:**](Modelo_variables_Exogenas.ipynb) Presentación y resultados del modelo final, incluyendo variables exógenas de los textos. 
