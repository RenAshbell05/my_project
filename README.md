# 📊 Análisis de ventas por producto

## 🎯 Objetivo
Analizar datos de ventas para identificar qué productos generan mayores ingresos y detectar patrones básicos.

## 📌 Descripción
Este proyecto utiliza Python para explorar y visualizar datos de ventas, con el fin de generar insights útiles para la toma de decisiones.

import pandas as pd
import matplotlib.pyplot as plt

data = {
    "producto": ["A", "B", "C", "D", "E"],
    "ventas": [100, 250, 180, 300, 220]
}

df = pd.DataFrame(data)

df

## 📊 Datos

El dataset contiene información de ventas por producto.
Cada fila representa un producto y su cantidad de ventas.

plt.bar(df["producto"], df["ventas"])
plt.title("Ventas por producto")
plt.xlabel("Producto")
plt.ylabel("Ventas")
plt.show()

## 🔍 Análisis

Se observa que el producto D tiene las mayores ventas, seguido por el producto B.
Esto indica que estos productos son los más demandados dentro del conjunto analizado.

## 📈 Conclusiones

- El producto D es el más vendido, lo que lo convierte en el principal generador de ingresos.
- Existe una diferencia notable entre los productos con mayor y menor rendimiento.
- Estos insights pueden ayudar a enfocar estrategias de venta en los productos más rentables.
