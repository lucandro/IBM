# IBM
SpaceX Falcon-9 First stage landing prediction
Descripción del Estudio de Caso

En este estudio de caso, nos enfocaremos en predecir si la primera etapa del cohete Falcon 9 de SpaceX aterrizará con éxito. SpaceX ofrece lanzamientos de Falcon 9 a un costo de 62 millones de dólares, en comparación con otras empresas que pueden cobrar hasta 165 millones por lanzamiento. Gran parte de estos ahorros provienen de la capacidad de SpaceX para reutilizar la primera etapa del cohete. Por lo tanto, ser capaces de pronosticar el éxito del aterrizaje de esta primera etapa nos permitirá estimar de manera más precisa el costo de un lanzamiento. Estos datos serán especialmente útiles si una empresa desea competir con SpaceX en el ámbito de lanzamientos de cohetes.
Metodología

 1.  **Recopilación de Datos:** Se obtendrán datos a través de una API pública de SpaceX y de otras fuentes, como páginas web relevantes.

 2.  **Preparación de Datos:** Asegurar que los datos estén en el formato correcto para el análisis, incluyendo la limpieza y la normalización de los mismos.

 3.  **Análisis Exploratorio:** Realizar un análisis exploratorio de datos (EDA) para entender mejor las variables involucradas y su relación con el éxito del aterrizaje.

 4.  **Modelado Predictivo:** Desarrollar modelos de aprendizaje automático que puedan predecir el éxito del aterrizaje basado en las características recopiladas.

  5.  **Validación y Evaluación:** Validar los modelos utilizando métricas adecuadas y evaluar su rendimiento en conjuntos de prueba.

  6.  **Visualización:** Crear paneles de control y visualizaciones interactivas para representar los resultados y facilitar la interpretación.

Esta metodología nos permitirá no solo desarrollar un modelo efectivo, sino también proporcionar información valiosa para cualquier empresa que busque competir con SpaceX en la industria de lanzamientos espaciales.

# Desarrollo
---

| Modulo 1                                                                                                                               |                                   |
| -------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------- |
| [Manejo_de_Datos.ipynb](https://github.com/lucandro/IBM/blob/3b00a27346c7475a9e2b14fa89904711a9599de7/Manejo_de_Datos.ipynb)           | Data wrangling                    |
| [Api](https://github.com/lucandro/IBM/blob/c148166e82a80eba98c2f7e2f7f2720de11e1ac9/Recogida_de_Datos.ipynb)                           | Data Collection Api               |
| [Web Scraping](https://github.com/lucandro/IBM/blob/c148166e82a80eba98c2f7e2f7f2720de11e1ac9/Recogida_de_Datos_con_Web_Scraping.ipynb) | Data Collection with Web Scraping |

---

| Modulo 2                                                                                                                        |                   |
| ------------------------------------------------------------------------------------------------------------------------------- | ----------------- |
| [EDA Sql](https://github.com/lucandro/IBM/blob/3f13c2add835bffc5309d4ada0251a386fba4c31/EDA_Sql.ipynb)                          | EDA  SQL          |
| [EDA Visualización](https://github.com/lucandro/IBM/blob/ee243619c52c9ac26af164d328dcbd3b61e032ea/EDA_Visualizaci%C3%B3n.ipynb) | EDA Visualization |

---


| Modulo 3                                                                                                                        |                   |
| ------------------------------------------------------------------------------------------------------------------------------- | ----------------- |
| [Análisis visual interactivo con Folium](https://github.com/lucandro/IBM/blob/95f6b10e01242f9cafc58e143630ba84b04fdc4b/An%C3%A1lisis_visual_interactivo_con_Folium.ipynb)                          | Interactive visual analysis with Folium          |
| [Cuadro de mando](https://github.com/lucandro/IBM/blob/e7bda23df9d2c54e253cb03170a83c3ea4736821/Cuadro_de_Mando_Interactivo_con_Ploty_Dash.ipynb) | Interactive Dashboard with Plotly Dash  |


---


| Modulo 4 |     |
| -------- | --- |
| [Predicción de aprendizaje automático](https://github.com/lucandro/IBM/blob/c2e86019e088e1d411cf03fb5876b1eab2cd722b/Predicci%C3%B3n_de_aprendizaje_autom%C3%A1tico.ipynb)     | Machine learning prediction    |



