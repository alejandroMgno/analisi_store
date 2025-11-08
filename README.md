# analisi_store

# 📊 Análisis de Ventas - Tiendas LATAM 

## 📌 Descripción del proyecto
Este proyecto tiene como objetivo determinar **a qué tienda le conviene más al Sr. Juan vender sus productos**, a partir del análisis de datos de cuatro tiendas diferentes (Tienda 1, Tienda 2, Tienda 3 y Tienda 4).  
El estudio se desarrolla en Python utilizando **Pandas, Matplotlib y Folium** para el procesamiento, análisis y visualización de la información.

---

## 🧠 Objetivos del análisis
1. Evaluar los **ingresos totales** de cada tienda.  
2. Identificar las **categorías de productos más y menos vendidas**.  
3. Analizar las **calificaciones promedio de los clientes**.  
4. Detectar los **productos más y menos vendidos**.  
5. Calcular el **costo de envío promedio**.  
6. Integrar toda la información para **recomendar la mejor tienda** para vender.

---

## 📈 Datos utilizados
Los datos se obtuvieron del repositorio público del **Challenge Data Science LATAM **, disponibles en formato CSV:

- `tienda_1.csv`
- `tienda_2.csv`
- `tienda_3.csv`
- `tienda_4.csv`

Cada archivo contiene información sobre:
- Producto y categoría  
- Precio y cantidad vendida  
- Calificación del cliente  
- Costo de envío  
- Coordenadas geográficas (lat, lon)

---

## 🧩 Herramientas y librerías
El proyecto fue desarrollado en **Google Colab** con las siguientes librerías:

```python
import pandas as pd
import matplotlib.pyplot as plt
from matplotlib.ticker import ScalarFormatter
import folium
