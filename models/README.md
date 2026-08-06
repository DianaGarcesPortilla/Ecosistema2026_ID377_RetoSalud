####Models

Esta carpeta está destinada a la documentación relacionada con el modelo de Machine Learning desarrollado en este proyecto.

El proceso completo de:

- construcción de escenarios de balanceo,
- entrenamiento de los modelos,
- evaluación mediante métricas de desempeño,
- selección del mejor modelo,
- registro en MLflow,
- registro en Unity Catalog,

se encuentra documentado en:

- **README.md** del proyecto (Secciones 12, 13 y 14).
- **notebooks/04_Clasificacion**, donde se desarrolla el entrenamiento, evaluación y selección del modelo.
- **notebooks/05_Despliegue**, donde se registra el modelo en MLflow y Unity Catalog.

> **Nota:** El modelo entrenado no se incluye en este repositorio, ya que su gestión y versionamiento se realiza mediante **MLflow** y **Unity Catalog** en Databricks.