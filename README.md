Análisis de Datos en Instacart

🌍 Introducción

Instacart es una plataforma de entregas de comestibles donde los usuarios pueden realizar pedidos y recibirlos en sus hogares. El objetivo de este proyecto es analizar los patrones de compra de los clientes, optimizar estrategias de ventas y proporcionar insights útiles basados en los datos de pedidos.

Este análisis se centra en la exploración, limpieza y visualización de datos de compras en Instacart, identificando tendencias clave como los productos más vendidos, los días de mayor demanda y las tasas de recompra.

📊 Dataset y Diccionario de Datos

El conjunto de datos incluye 5 tablas principales:

instacart_orders.csv: Información sobre los pedidos realizados.

products.csv: Lista de productos disponibles.

aisles.csv: Información sobre los pasillos de la tienda.

departments.csv: Datos sobre los departamentos de productos.

order_products.csv: Relación entre productos y pedidos.

Cada tabla contiene información clave para entender los patrones de compra y segmentar los datos de manera efectiva.

📂 Archivos Incluidos

aisles.csv: Contiene información sobre los pasillos (categorías de productos) disponibles en la tienda.

departments.csv: Lista de los departamentos de la tienda.

instacart_orders.csv: Datos sobre los pedidos realizados por los clientes.

products.csv: Información sobre los productos disponibles.

Analisis_datos_Data_Wrangling.ipynb: Jupyter Notebook con el análisis y las visualizaciones generadas.

🤖 Tecnologías y Herramientas Utilizadas

Python: Lenguaje principal.

Pandas: Manipulación y limpieza de datos.

Matplotlib & Seaborn: Visualización de datos.

Jupyter Notebook: Desarrollo y documentación del proyecto.

🏗️ Estructura del Proyecto

Carga de datos: Lectura de los archivos CSV.

Análisis exploratorio: Estadísticas descriptivas y análisis de los datos.

Limpieza de datos: Tratamiento de valores nulos y ajustes en los datasets.

Visualización: Gráficos para mostrar patrones en los datos.

Resultados clave:

Identificación de los productos más vendidos.

Análisis de los horarios con mayor cantidad de pedidos.

Relación entre categorías de productos y comportamiento del cliente.

🎨 Visualización de Resultados

¿A qué hora compran más los clientes?

Se observó un pico entre las 10:00 AM y 5:00 PM.

¿Cuándo compran más?

Los días domingo y lunes tienen la mayor cantidad de pedidos.

¿Qué productos se venden más?

✅ Bananas

✅ Espinaca orgánica

✅ Leche orgánica

¿Qué productos tienen mayor tasa de recompra?

✅ Banana (66,050 compras)

✅ Aguacates orgánicos

✅ Leche orgánica

🚀 Conclusiones y Recomendaciones

Patrones de compra: La mayor actividad de compra ocurre entre las 10 AM y 5 PM.

Frecuencia de recompra: Los productos frescos y orgánicos son los más repetidos.

Días de mayor compra: Domingo y lunes tienen el mayor volumen de ventas.

Estrategia de marketing: Se pueden hacer descuentos en productos populares y promociones en días de menor demanda.

📑 Reproducir el Análisis

Clonar este repositorio:

git clone https://github.com/jose-alberto-hurtado/Analisis-de-datos.git

Instalar dependencias:

pip install pandas matplotlib seaborn

Abrir el archivo Jupyter Notebook:

jupyter notebook Analisis_datos_Data_Wrangling.ipynb

👥 Contacto

Email: josealberto1829@gmail.com

GitHub: jose-alberto-hurtado

LinkedIn: José Alberto Hurtado Echeverría

🌟 Si te gustó este proyecto, dale una estrella en GitHub! ⭐
