# Análisis de Nacimientos en Argentina (2023)

Este proyecto analiza los nacimientos registrados en Argentina a partir de datos oficiales, con el objetivo de explorar patrones asociados a la edad materna, el nivel educativo y la distribución territorial. El trabajo combina técnicas de Análisis Exploratorio de Datos (EDA) y Ciencia de Datos, incorporando un enfoque de clustering para identificar perfiles maternos diferenciados.

## Objetivos

Analizar la distribución de los nacimientos según edad materna y nivel educativo.

Estudiar la maternidad adolescente desde una perspectiva territorial y educativa.

Calcular tasas y proporciones que permitan comparar provincias más allá de los valores absolutos.

Identificar perfiles maternos mediante técnicas de clustering no supervisado.

---
## Fuente de datos

Los datos utilizados provienen de registros administrativos oficiales de nacimientos en Argentina (DEIS – Ministerio de Salud). Cada registro original representa una agregación de nacimientos con características comunes.

Para los análisis territoriales y visualizaciones geográficas se utilizó un shapefile de las provincias argentinas, empleado para la correcta representación espacial de los indicadores calculados (tasas y distribuciones provinciales).

---
## Principales insights

Las provincias con mayor población concentran la mayor cantidad absoluta de nacimientos, pero las tasas más altas de maternidad adolescente se observan en provincias del NEA y NOA.

Existe una asociación negativa clara entre nivel educativo y maternidad adolescente: a mayor nivel educativo, menor probabilidad de maternidad antes de los 20 años.

Los perfiles maternos identificados mediante clustering muestran una progresión consistente entre edad y educación, desde maternidades tempranas con educación media hasta maternidades tardías con educación superior consolidada.



---


## Estructura del proyecto

| Carpeta / Archivo        | Descripción                                           |
|--------------------------|-------------------------------------------------------|
| notebooks/               | Notebook principal (`analisis_nacimientos.ipynb`).    |
| data/                    | Dataset original (`nacimientos2023.csv`).             |
|                          | provincias_shapefile/                                 |                       
| images/                  | Gráficos exportados.                                  |
| reports/                 | `Informe_Analisis_Nacimientos.pdf`                      |
| README.md                | Descripción del proyecto.                             |


---

## Tecnologías y librerías utilizadas

- Python 3  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Google Colab
- scikit-learn
 
---

## Autor

**Valentino Lorenzati**

Proyecto desarrollado con fines academicos y de portafolio en analisis y ciencia de datos.




