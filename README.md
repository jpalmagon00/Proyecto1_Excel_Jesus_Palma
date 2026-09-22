# Proyecto1_Excel_Jesus_Palma

## Análisis de Medidas Anatómicas de Pingüinos Antárticos

Proyecto de análisis de datos desarrollado en Microsoft Excel para estudiar las diferencias anatómicas entre distintas especies de pingüinos mediante herramientas de Business Intelligence.

## Objetivo

Analizar características anatómicas de las especies Adelie, Chinstrap y Gentoo, identificando diferencias relacionadas con la especie y el sexo mediante tablas dinámicas, gráficos y un dashboard interactivo.

## Proceso de trabajo

### 1. Preparación de datos (Power Query)

- Importación y transformación del dataset.
- Revisión de valores nulos y duplicados.
- Asignación de tipos de datos.
- Creación de intervalos para la longitud de la aleta.
- Generación de variables auxiliares para facilitar el análisis.

### 2. Modelado de datos (Power Pivot)

- Creación de tablas auxiliares de especies, sexo e islas.
- Establecimiento de relaciones entre tablas.
- Creación de medidas para calcular:
  - Peso medio.
  - Longitud media del pico.
  - Profundidad media del pico.
  - Longitud media de la aleta.

### 3. Análisis y visualización

- Creación de tablas dinámicas para resumir y comparar datos.
- Elaboración de gráficos dinámicos.
- Implementación de segmentadores para filtrar por especie, sexo e isla.
- Desarrollo de un dashboard interactivo para la exploración de los resultados.

## Principales conclusiones

- Los machos presentan un peso medio superior al de las hembras.
- La longitud y profundidad del pico son similares entre sexos.
- Adelie presenta la menor longitud media de pico.
- Gentoo posee las aletas más largas y el mayor peso medio.
- La distribución de la longitud de la aleta muestra una doble campana al analizar conjuntamente todas las especies. Esto se debe a las diferencias significativas entre las medidas de las diferentes especies.
- Analizando cada especie por separado, la longitud de la aleta sigue aproximadamente una distribución normal.

## Tecnologías utilizadas

- Microsoft Excel
- Power Query
- Power Pivot
- Tablas Dinámicas
- Gráficos Dinámicos
- Segmentadores (Slicers)

## Archivos

- `Pinguinos.xlsx`
- `dashboard.png`

## Autor

Jesús Palma González
