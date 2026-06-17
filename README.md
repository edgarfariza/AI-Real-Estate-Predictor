# AI-Real-State-Agent
# Predicción de precios para Real State con Amazon SageMaker Canvas

Este proyecto ha sido desarrollado como parte de la Especialización en Cloud Computing. Consiste en la implementación de una solución de Machine Learning no-code mediante la plataforma Amazon SageMaker Canvas, orientada a la predicción de precios en el sector inmobiliario a partir de variables sociodemográficas, económicas y geográficas.

El objetivo de este repositorio es documentar el despliegue de la infraestructura en AWS, el análisis técnico del modelo de regresión y las conclusiones de su aplicación en el entorno empresarial.

---

## Infraestructura y Servicio Cloud Utilizado

Para la resolución de este proyecto se ha configurado el ecosistema de Amazon Web Services (AWS), utilizando los siguientes componentes:

* **Amazon SageMaker Domain:** Configuración del entorno de ejecución aislado y gestión de roles de ejecución de AWS IAM para asegurar el control de accesos y permisos.
* **Amazon SageMaker Canvas:** Servicio visual e intuitivo diseñado para crear y desplegar modelos de Machine Learning sin necesidad de escribir código (no-code). Esta herramienta facilita el acceso a la Inteligencia Artificial permitiendo generar predicciones precisas basadas en datos históricos.
* **Amazon S3:** Almacenamiento subyacente para la ingesta y persistencia de los conjuntos de datos.

---

## El Problema de Negocio (Sector Inmobiliario)

El caso de uso se centra en el sector inmobiliario. El objetivo principal es la predicción del valor de las viviendas a partir de un conjunto de datos que incluye múltiples variables sociodemográficas y geográficas, tales como la ubicación, la antigüedad de la vivienda, el número de habitaciones y los ingresos medios de la zona.

Para ello, se ha construido un modelo predictivo de regresión numérica, el cual analiza las relaciones entre las variables independientes para estimar un resultado cuantitativo y continuo. Los datos, extraídos del workshop de AWS, incluyen tanto las características físicas de los inmuebles como los factores socioeconómicos del entorno. El parámetro configurado para ser predicho por el modelo es el valor económico de la vivienda, buscando determinar cómo varía dicho precio al alterar el resto de las variables del dataset.

### Valor para el Negocio:
Para una empresa del sector inmobiliario, disponer de este modelo tiene una utilidad crítica puesto que permite:
* Automatizar la tasación inicial de inmuebles.
* Identificar propiedades infravaloradas en el mercado para su adquisición.
* Ajustar los precios de venta basándose en el comportamiento real de los datos en lugar de en la intuición.

---


