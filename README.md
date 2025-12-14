# Análisis de Nacimientos en Argentina (2023)

Este proyecto realiza un análisis exploratorio de los datos de **nacidos vivos registrados en la República Argentina**, utilizando el dataset `nacimientos2023.csv` proporcionado por el **Ministerio de Salud – Dirección de Estadística e Información en Salud (DEIS)**.  

El objetivo principal es identificar patrones relacionados con la **maternidad adolescente**, el **nivel educativo de las madres** y la **distribución geográfica de los nacimientos**.

---

## Tecnologías y librerías utilizadas

- Python 3  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Google Colab

---

## Estructura del proyecto

| Carpeta / Archivo        | Descripción                                           |
|--------------------------|-------------------------------------------------------|
| notebooks/               | Notebook principal (`analisis_nacimientos.ipynb`).   |
| data/                    | Dataset original (`nacimientos2023.csv`).            |
| images/                  | Gráficos exportados.                                  |
| README.md                | Descripción del proyecto.                             |


## Contenido del análisis

1. **Preparación del dataset**  
   - Expansión de registros según la columna `nacimientos_cantidad` para que cada fila represente un nacimiento individual.  
    

2. **Exploración de datos**  
   - Distribución de edad de las madres.  
   - Frecuencia de nivel educativo por edad.  
   - Identificación de posibles errores en la carga de datos (ej. madres adolescentes con nivel universitario completo).  

3. **Insights principales**  
   - **Inconsistencias menores:** Se identificaron 92 casos (~0,3 %) de madres de 15 a 19 años con nivel universitario completo, posiblemente debido a errores administrativos.  
   - **Maternidad adolescente por provincia:** Las tasas más altas se observan en provincias del NEA y NOA, particularmente Formosa, Misiones y Chaco.  
   - **Relación con nivel educativo:** A menor nivel educativo, mayor es la probabilidad de maternidad adolescente. Mujeres sin secundaria completa presentan ~20 % de probabilidad, mientras que quienes completaron estudios terciarios o universitarios casi no presentan maternidad adolescente.  

4. **Visualizaciones**  
   - Histogramas de edad de madres.  
   - Barras de nivel educativo de madres adolescentes.  

---

## Cómo reproducir el análisis

1. Abrir el notebook `notebooks/analisis_nacimientos.ipynb` en **Google Colab** o Jupyter.  
2. Subir el archivo `nacimientos2023.csv` a la carpeta `/data/`.  
3. Ejecutar las celdas en orden: limpieza → exploración → visualizaciones → insights.  


