# zara_project

## Descripción del proyecto

Este proyecto realiza un análisis exploratorio de datos (EDA) sobre un dataset de ventas de la marca Zara. El objetivo es encontrar patrones de consumo en las ventas, tomando como referencia la información que proporciona cada venta. A través de gráficos y agrupamientos, se busca entender cómo diferentes variables como los productos con promociones, en temporada, el tipo de prenda o la ubicación física del producto en tienda influyen en el comportamiento de compra.

## Descripción del dataset

Este dataset de ventas de Zara contiene información sobre productos vendidos en tiendas durante un período determinado. Incluye variables relevantes como el nombre del producto, categoría, precio, volumen de ventas, si estaba en promoción, si era parte de una colección de temporada, y la ubicación del producto en la tienda.
Este dataset se puede obtener en el siguiente enlace: https://www.kaggle.com/datasets/xontoloyo/data-penjualan-zara

### Variables incluidas:
- **Product ID**: Identificador único de cada producto.
- **Product Position**: Ubicación del producto en la tienda física.
- **Promotion**: Indica si el producto estaba en promoción.
- **Product Category**: Categoría del producto (jackets, t-shirts, etc)
- **Seasonal**: Indica si el producto pertenece a una colección de temporada.
- **Sales Volume**: Cantidad vendida.
- **Brand**: Marca del producto.
- **URL**: Enlace del producto (si es vendido online).
- **SKU**: Código de inventario.
- **Name**: Nombre del producto.
- **Description**: Descripción del producto.
- **Price**: Precio del producto.
- **Currency**: Moneda del precio.
- **Scraped_at**: Fecha y hora en que se extrajo la información (scraping).
- **Terms**: Tipo o condición de la prenda.
- **Section**: Sección mujer u hombre.

**Licencia**: MIT  
**Actualización esperada**: Nunca  
**Etiquetas**: Business, Data Analytics, EDA, Limpieza de datos, Principante, Beginner, 

## Objetivo del Análisis

El propósito de este análisis es detectar patrones de consumo en las ventas y comprender cómo diferentes variables influyen en:

- El volumen total de ventas
- El precio promedio de los productos
- El comportamiento de compra según promociones, temporada y ubicación del producto
- Las diferencias entre secciones (hombres vs. mujeres)
- El desempeño comercial según el tipo de prenda

## Tecnologías utilizadas
- Python 3
- pandas
- seaborn
- matplotlib
- Jupyter Notebook

## Como ejecutar el proyecto
1. Cloná este repositorio o descargá el archivo notebook.
2. Asegurate de tener las siguientes librerías instaladas:
   ```bash
   pip install pandas seaborn matplotlib
3. Ejecutá el archivo EDA_Zara.ipynb en Jupyter Notebook o Google Colab.

