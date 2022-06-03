# Detección de enfermedad de Alzheimer mediante resonancia magnética y Deep Learning, para asistir el proceso de diagnóstico.

**Daniela Meléndez Mejía**
- **03 de junio del 2022**


## Indice

- Introducción del proyecto
- Desarrollo
- Resultados 
- Conclusiones
- Link de un video explicativo

## Introducción

La demencia es el término dado al deterioro de la memoria, el comportamiento, el intelecto, la razón y la capacidad para realizar actividades. El número de personas con demencia a nivel mundial crece desproporcionalmente y esta es una de las principales causas de discapacidad y dependencia entre las personas mayores a nivel global. La enfermedad de Alzheimer (EA) es una de las mayores causas de demencia, con un total de 60% a 80% de casos.

El temor que se le tiene a esta enfermedad es que no tiene cura en ninguna de sus etapas y la mayoría de sus tratamientos no son efectivos, esto se da debido a la etapa del diagnóstico de la enfermedad, es decir que, si se detectara a tiempo los síntomas de ésta, se podrían hacer grandes cambios, ya que, su tratamiento sería a lo mejor más efectivo y posiblemente lograr mejores resultados. En este trabajo se desarrollará un sistema que probablemente pueda detectar la EA mediante imagen diagnóstico de resonancia magnética (RM) y Deep Learning (DL). Esto podría servir de ayuda en su diagnóstico previo de modo que el tratamiento sea más eficiente.

Las imágenes mencionadas para realizar el entrenamiento y validación son tomadas del Dataset de ADNI, el cual se solicito permiso mencionando el trabajo que se desea realizar y dio acceso a las imágenes que se usaron para todo el proceso de este proyecto. Este Dataset cuenta con más de 3000 archivos de RM las cuales sus etiquetas se redujeron a un resultado binario de tiene o no tiene Alzheimer. Para sus características, de cada archivo se tomó una imagen directamente de la parte temporal del cerebro, donde dio un tamaño de 40x40, y mediante la función reshape se dejó cada imagen con 1 fila y 1600 columnas (características). Cada imagen que se obtuvo se guardó en un pickle que a través de su librería _pickle y algunas de sus funciones como dump y de este modo optimizar el proceso. 

## Desarrollo


