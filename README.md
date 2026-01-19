# La Brecha Invisible: Análisis de Cuidados Infantil en España 🇪🇸

Este repositorio contiene el análisis de los microdatos de la **Encuesta de Empleo del Tiempo (INE)** para el proyecto Capstone del Certificado de Análisis de Datos de Google. El objetivo es visualizar la brecha de sexo en la conciliación y el impacto del servicio doméstico.

## 📊 Descripción del Proyecto
Este estudio utiliza R para procesar más de **2 millones de registros** de diarios de actividad, cruzándolos con datos de hogares y empleo para entender quién sostiene el cuidado de niños en la sociedad española.

### Hallazgos Clave:
- **Persistencia de la Brecha:** El sexo es la variable determinante; las mujeres asumen una carga horaria significativamente mayor, incluso en hogares con ayuda externa.
- **Doble Jornada:** Las mujeres trabajadoras enfrentan picos de actividad (baños, cenas, deberes) mucho más intensos que los varones.
- **Perfil Demográfico:** El análisis revela una fuerte presencia de mujeres de edad avanzada (abuelas), cruciales para la sostenibilidad del sistema.

## 🛠️ Tecnologías Utilizadas
- **Lenguaje:** R (Tidyverse, ggplot2, knitr)
- **Herramientas:** RStudio, R Markdown
- **Fuentes de Datos:** Microdatos del Instituto Nacional de Estadística (INE).

## 📁 Estructura del Repositorio
- `analisis_conciliacion.Rmd`: Script principal que realiza la limpieza, unión de tablas y generación de gráficos.
- `analisis_conciliacion.html`: Informe final exportado con los resultados y visualizaciones.
- `datos_maestros_capstone.csv`: Dataset procesado listo para ser utilizado en Tableau.

## 🚀 Cómo ejecutar el análisis
1. Descarga los archivos de microdatos del INE (`MHOGAR`, `DIARIO2`, `CINDIV`, `SD`).
2. Clona este repositorio.
3. Abre el archivo `.Rmd` en RStudio.
4. Asegúrate de actualizar las rutas de los archivos `.txt` en el código.
5. Haz clic en **Knit** para generar el informe.

## ✍️ Autora
**Olga Ocaña Mozos** - *Análisis y Visualización de Datos*
