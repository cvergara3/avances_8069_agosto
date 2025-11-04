# avances_8069_agosto
Entregables (códigos de jupyter notebook) relacionados con el proyecto 8069 del mes de agosto

El repositorio consta de dos códigos: 

1. shot_gather_submuestreo_recons.ipynb
En el código se subdivide en dos. La primera parte submuestrea shot gathers de forma aleatoria y entrena una U-Net para reconstruir los shots. La segunda parte submuestrea shot gathers incluyendo en el entrenamiento la capa binaria. El notebook incluye gráficas y métricas.

2. utah_unet_ste.ipynb
Se presenta el código de preprocesamiento de los datos reales de Utah, así como el algoritmo de submuestreo y reconstrucción con U-Net y capa binaria entrenable. Los datos de entrada corresponden a los shot gathers 2D crudos de Utah FORGE, los cuales pueden descargarse de esta ruta: https://gdr.openei.org/submissions/1015 el archivo 2D_seismic_data.zip
