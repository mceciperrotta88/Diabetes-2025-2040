# Proyección de Diabetes en Argentina 2025-2040

## Objetivo

Proyectar la cantidad de personas con **diabetes diagnosticada** en Argentina para el año **2040**
considerando 3 escenarios: optimista, normal y pesimista, con datos **oficiales y validados**. Luego se compara
con datos Internacionales

##  Metodología

- Se construyo un **modelo de proyección epidemiológica simple**, basado en prevalencias observadas y supuestos de crecimiento poblacional.  
- Se definieron tres escenarios:  
  - **Optimista**  
  - **Normal**  
  - **Pesimista**  
- Los resultados se estratificaron por sexo (👩 ~52%, 👨 ~48%).  


##  Resultados principales

- **Optimista**: 4.41 millones de casos diagnosticados en 2040  
- **Normal**: 5.56 millones  
- **Pesimista**: 6.67 millones

**Distribución por edad (2040)**:

50-64 años: 19.3% prevalencia (mayor carga)
65+ años: 21.4% prevalencia
18-24 años: 5.9% prevalencia
El análisis completo está en el notebook completo https://github.com/mceciperrotta88/Diabetes-2025-2040/blob/main/proyectodiabetes.ipynb

 ##  Fuentes oficiales
- **Población**: [Censo 2022 - INDEC](https://www.indec.gob.ar/indec/web/Nivel4-Tema-2-9-135)
- **Prevalencia**: [ENFR 2018 - Ministerio de Salud](https://www.argentina.gob.ar/salud/enfr)
- **Proyección poblacional**: [INDEC](https://www.indec.gob.ar/indec/web/Nivel4-Tema-2-9-135)

##  Validación internacional
- **Compatible con OPS/OMS**: prevalencia ~10% ([fuente](https://www.paho.org/es/temas/diabetes))
- **Más realista que IDF**: porque solo incluye **casos diagnosticados**, no estimados ([IDF Diabetes Atlas](https://diabetesatlas.org))

## Limitaciones 

El modelo **no predice casos no diagnosticados** sino solo los registrados oficialmente  
Es un ejercicio exploratorio y académico, no una predicción definitiva 
No se aplicaron técnicas estadísticas avanzadas


## Importante

Este trabajo fue realizado con fines educativos y de práctica.
Los datos y resultados no deben utilizarse como fuente de verdad absoluta ni para tomar decisiones clínicas ni políticas.
El único objetivo fue aprender a analizar datos reales como parte de una practica estudiantil

Maria Cecilia Perrotta
