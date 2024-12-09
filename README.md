# Limitaciones de los Sistemas Recomendadores Multimodales

## Descripción del Proyecto

Este proyecto se basa en el paper *"Limitaciones de los Sistemas Recomendadores Multimodales"*. En este trabajo se replica y analiza el dataset PixelRec, utilizando modelos de recomendación multimodal como LightFM. El objetivo principal es comparar estos sistemas con algoritmos tradicionales para evaluar la efectividad del uso de datos multimodales en sistemas recomendadores, identificando las principales limitaciones y desafíos encontrados.

Entre los aspectos abordados se encuentran:

- **Generación de embeddings:** Construcción de representaciones numéricas utilizando redes neuronales preentrenadas como CLIP.
- **Reducción de dimensionalidad:** Aplicación de PCA para optimizar el procesamiento de los datos.
- **Implementación de modelos:** Análisis del rendimiento de LightFM y de las limitaciones técnicas de otros enfoques.

## Contenidos del Repositorio

Este repositorio incluye los siguientes archivos y carpetas:

- `Preprocesamiento_de_datos.ipynb`: Notebook de Python para la exploración de datos y extracción de información para generar datasets.
- `LightFM Multimodal.ipynb`: Notebook de Python para la utilización de datos, reducción de dimensionalidad con PCA, y evaluación de métricas de recomendación.

## Referencias

- Cheng, Y., Pan, Y., Zhang, J., Ni, Y., Sun, A., & Yuan, F. (2023). An image dataset for benchmarking recommender systems with raw pixels. *arXiv preprint*. Disponible en: [arXiv:2309.06789](https://arxiv.org/abs/2309.06789).
- Zhou, H., Zhou, X., Zeng, Z., Zhang, L., & Shen, Z. (2023). A comprehensive survey on multimodal recommender systems: Taxonomy, evaluation, and future directions. *arXiv preprint*. Disponible en: [arXiv:2302.04473](https://arxiv.org/abs/2302.04473).
- Radford, A., et al. (2021). Learning transferable visual models from natural language supervision. *arXiv preprint*. Disponible en: [arXiv:2103.00020](https://arxiv.org/abs/2103.00020).

Para cualquier consulta o sugerencia, por favor contacta a los autores del proyecto:
- Jean Fuentes: jhfuentes@uc.cl
- Benjamín Blancaire: blancaire@uc.cl
- Marcos Santelices: marcos.santelices@uc.cl
