# **Análisis Macroeconómico de América Latina (1970 - 2023)**

## Dataset

Datos obtenidos desde el *Banco Mundial (World Bank API)* para 8 países de América Latina y el Caribe: Chile, Argentina, Brasil, Perú, Colombia, México, Uruguay y Puerto Rico. La variables analizadas incluyen inflación, crecimiento del PIB, desempleo y deuda externa, con cobertura temporal de 1970 a 2023.

## Preguntas analíticas

1. ¿La inflación extrema/maxima registrada en el dataset fue un fenómeno aislado de un solo país, o fue compartido por la región? ¿Que países se vieron afectados y en que período?
2. ¿Existe una correlación entre la deuda externa y el desempleo, o se trata de variables independientes?
3. ¿El valor mínimo de crecimiento del PIB corresponde al impacto del COVID-19 en 2020 o fue por otro motivo? Y si fue por el COVID-19, ¿Fue una caída homogénea o hubo diferencias significativas entre países de la región?

## Principales hallazgos

- La hiperinflación de fines de los 80 y principios de los 90 fue un fenómeno aislado, pero que afectó a varios países de la región por causas similares. Basicamente, todos los países de la región pasaban por problemas similares, pero la hiperinflación de Perú, Brasil y Argentina fue producido por sus políticas internas.
- La correlación entre la deuda externa y el desempleo resultó debil, fue del *0.249*, lo que rechaza la hipotesis de la relación directa (si están relacionados, pero indirectamente). Esto mismo ocurre con la correlación PIB-desempleo, la cual tuvo una correlación de *-0.238*.
- El mínimo del PIB corresponde al año 1989, en Perú, sin embargo, el COVID-19 produjo la caída de la región completa, pasando de un promedio de 1% de PIB en 2019 al -6% del PIB en 2020. Aun que, como información importante, no fue una caída tan homogénea, ya que Perú tuvo la bajada mas alta, registrando un ~*-10.6%* de PIB en 2020, mientras que Brasil tuvo la bajada más "tranquila", registrando un ~*-3.9%* de PIB, una diferencia de casi 7 puntos porcentuales en la misma región.
- Contrario a lo esperado, el estallido social chileno en 2019 no generó una caida distinguible en el crecimiento anual del PIB de Chile.

## Estructura del repositorio

- Notebooks
    - datos_latam.csv (Datos de API)
    - Solemne1.ipynb (Análisis completo con ejecutable)
- .gitignore (Codigo que limita a git lo que guarde)
- requirements.txt (librerías utilizadas)
- README.md