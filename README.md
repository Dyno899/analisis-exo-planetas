# Análisis de Exoplanetas 🪐

Este proyecto consiste en un análisis riguroso sobre variables cuantitativas que determinan las características de exoplanetas (temperatura, densidad estelar, metalicidad, etc.). El análisis permitió verificar comportamientos, relaciones intrínsecas y reafirmar hipótesis de modelos astronómicos ya publicados.

##  Herramientas Utilizadas
- **Lenguaje:** R (ejecutado en Google Colab)
- **Librerías principales:** `tidyverse`, `readr`, `dplyr`, `ggplot2`
- **Entorno:** Google Colab

## Principales Hallazgos
- Se observó que los planetas gigantes tienden a tener una metalicidad estelar ligeramente superior en comparación con los no gigantes.
- No se encontró una relación lineal fuerte entre la metalicidad ([Fe/H]) y la excentricidad en los datos filtrados, aunque se notan ligeros patrones.
- Se encontró que el año con más planetas descubiertos fue en 2016 con 1504 planetas.
- Se reafirmó la relación entre una alta metalicidad estelar y la presencia de planetas gigantes gaseosos.
- Se comprobó la prueba de Kruskal-Wallis: El resultado obtenido fue p < 2.2e-16. Lo que nos dice que existen diferencias muy significativas entre los grupos de metalicidad (Baja, Solar, Alta). La probabilidad de que esto sea por azar es prácticamente 0%.

## Visualizaciones Destacadas

**1. Distribución de metalicidad (Gigantes vs No Gigantes)**
![Grafico densidad](https://github.com/user-attachments/assets/d69c333f-d26e-44ae-a7c5-3d493f5ec397)
*Observación: La curva de densidad muestra un pico más alto y desplazado hacia la derecha para los planetas gigantes, confirmando la relación entre metalicidad y la formación de gigantes gaseosos.*

**2. Relación entre Metalicidad y Excentricidad**
![Grafico excentricidad](https://github.com/user-attachments/assets/49dc293c-6b60-4097-adfd-2d68f787ba1a)
*Observación: Al filtrar datos con lim=0, la dispersión de los datos no muestra una tendencia lineal clara, lo que sugiere que la excentricidad depende de otros factores además de la metalicidad.*

**3. Año con más descubrimientos**
![Grafico años](https://github.com/user-attachments/assets/351012f4-f11c-4bf4-8a89-2077a527ed75)
*Observación: El año con más planetas descubiertos fue en 2016 con 1504 planetas, probablemente impulsado por misiones espaciales como Kepler.*

**4. Prueba de Kruskal-Wallis**
![Grafico Kruskal](https://github.com/user-attachments/assets/33ee7aed-c81b-43e2-a603-069397740452)
*Observación: Existen diferencias muy significativas entre los grupos de metalicidad (Baja, Solar, Alta). La probabilidad de que esto sea por azar es prácticamente 0%.*

---
**🚀 Explora el código completo en Google Colab:**
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1ZwfL6D75Uv-tphZF_-nB0vWdfHR42ZyD?usp=sharing)
