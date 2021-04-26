# Demo-AwsSagemaker-Boston-Houses
Este es un replicado y adaptado del curso de Machine Learning Engineer de Udacity


## Objetivo 

El objetivo de este tutorial es explicar cómo se ejecuta el entrenamiento, evaluación y despliegue de una modelo utilizando como herramienta AWS Sagemaker. Para ello, se realizan los siguientes pasos:

1. Descargar los datos
2. Procesar / preparar los datos
3. Cargar los datos procesados en S3
4. Entrenar un modelo elegido
5. Implementar el modelo entrenado haciendo un despliegue con el endpoint que proporciona Sagemaker
6. Probar el modelo entrenado utilizando el despliegue realizado en el paso anterior


## Para ejecutar la demo


### Paso previo a ejecutar en AWS

Antes de ejecutar los notebook se debe configurar un rol IAM que permita acceder a S3 y a Sagemaker, por lo que se le deben agregar los permisos llamados AmazonS3FullAccess y AmazonSageMakerFullAccess

### Clonar el repositorio y 

1. Crear una instancia de notebook por demanda en Sagemaker e ingresar a ella
2. Abrir la terminal y posicionarte en la carpeta usando el comando cd SageMaker/
3. Una vez ahí debes clonar el repositorio https://github.com/iair/Demo-AwsSagemaker-Boston-Houses.git
4. Ahora, debes volver a jupyter donde varas la carpeta Demo-AwsSagemaker-Boston-Houses y haces click ahí
5. Entras a notebooks y ejecutas el notebook demo-boston-master-ia-deploy-bajo nivel.ipynb




