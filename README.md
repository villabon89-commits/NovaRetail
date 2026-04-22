# Análisis de Comportamiento de Clientes - NovaRetail+

## 📄 Descripción del Proyecto

Este proyecto tiene como objetivo principal evaluar los factores del comportamiento de los clientes de **NovaRetail+**, una plataforma de comercio electrónico líder en Latinoamérica. El análisis se centra en identificar qué variables (visitas, compras, satisfacción, etc.) están más fuertemente asociadas con el **ingreso anual generado** por el cliente durante el cierre de 2024. Los hallazgos buscan proporcionar una base basada en datos para que el equipo de Crecimiento y Retención pueda diseñar estrategias más efectivas.

## 📊 Datasets Utilizados

Se utilizó el dataset principal alojado en '/content/sample_data/novaretail_comportamiento_clientes_2024.csv':

1.  **`novaretail_comportamiento_clientes_2024.csv`**: Contiene 15,000 registros con información demográfica (edad, región), métricas de uso (visitas, compras, dispositivo), indicadores de satisfacción y el ingreso anual (métrica objetivo).

## 📈 Etapas del Análisis

El análisis se estructuró en las siguientes etapas:

1.  **Carga y Exploración de Datos**: Validación de la integridad del dataset, tipos de datos y estadísticas descriptivas iniciales.
2.  **Preparación y Limpieza**: Confirmación de la ausencia de nulos y verificación de variables binarias y categóricas para el análisis estadístico.
3.  **Visualización de Relaciones (Heatmap)**: Creación de una matriz de correlación visual, utilizando una escala divergente con centro en cero para identificar asociaciones directas e inversas de forma clara.
4.  **Análisis Correlacional Numérico**: Cálculo de coeficientes de Pearson para variables numéricas, Punto-Biserial para binarias y V de Cramér para categóricas, asegurando el método correcto para cada tipo de dato.
5.  **Desarrollo de Insights Profundos**: Creación de métricas de eficiencia como el Ingreso por Compra (AOV) y análisis de tasas de conversión segmentadas por membresía Premium.
6.  **Interpretación Ejecutiva**: Resumen de hallazgos clave, diferenciando estrictamente entre correlación y causalidad, y formulación de implicaciones de negocio.

## 🚀 Cómo Ejecutar el Notebook

Este notebook fue desarrollado en Google Colab para facilitar su reproducción.

1.  **Abrir en Google Colab**: Sube el archivo `.ipynb` a tu entorno o impórtalo desde GitHub.
2.  **Cargar el Dataset**: El código busca el archivo en `/content/sample_data/novaretail_comportamiento_clientes_2024.csv`. Asegúrate de cargar el archivo en esa ruta.
3.  **Ejecutar Celdas**: Puedes ejecutar todas las celdas en orden (`Runtime > Run all`) para generar el análisis completo y las visualizaciones.

## ♻️ Guía de Reproducción

Para reproducir este análisis, sigue estos pasos:

1.  **Clonar el Repositorio**:
    ```bash
    git clone https://github.com/villabon89-commits/NovaRetail.git
    cd NovaRetail
    ```
2.  **Entorno de Python**: Se recomienda usar Python 3.x con las siguientes librerías instaladas:
    * `pandas`, `numpy`, `seaborn`, `matplotlib`, `scipy`.
3.  **Ejecución**: Abre el notebook en tu IDE preferido o en Colab y sigue el flujo de trabajo documentado.
