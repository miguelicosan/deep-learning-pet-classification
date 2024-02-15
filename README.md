# Proyecto de Reconocimiento y Clasificación de Imágenes con Deep Learning

## Descripción
Este proyecto implementa un sistema de reconocimiento y clasificación de imágenes utilizando Deep Learning, específicamente para distinguir entre imágenes de perros y gatos, incluyendo la clasificación por razas. Basado en el "Oxford-IIIT Pet Dataset", el proyecto utiliza TensorFlow y la técnica de transfer learning con la red neuronal InceptionV3 para lograr este objetivo.

## Características
- **Reconocimiento y Clasificación de Imágenes**: Capaz de diferenciar entre perros y gatos, con posibilidad de extensión a clasificación por razas.
- **Transfer Learning con InceptionV3**: Utiliza un modelo preentrenado para mejorar la eficiencia y precisión de la clasificación.
- **Entorno Configurable con Miniconda**: Facilita la gestión de dependencias y entornos de Python.

## Requisitos Previos
- Miniconda o Anaconda instalado en tu sistema.
- Conocimientos básicos de Python, TensorFlow y manejo de Jupyter Notebook.

## Configuración del Entorno
1. Clone este repositorio a su máquina local.
2. Cree un entorno conda utilizando el archivo `environment.yml` proporcionado (o instale manualmente las dependencias necesarias como TensorFlow, Matplotlib, etc.).
    ```bash
    conda env create -f environment.yml
    ```
3. Active el entorno conda.
    ```bash
    conda activate <nombre_del_entorno>
    ```

## Uso
1. Descargue el "Oxford-IIIT Pet Dataset" y colóquelo en el directorio adecuado siguiendo las instrucciones en el cuaderno Jupyter.
2. Ejecute el cuaderno Jupyter `Proyecto_Deep_Learning.ipynb` para entrenar y probar el modelo.
3. El cuaderno incluye pasos detallados para la preparación de datos, entrenamiento de modelo, y evaluación de predicciones.

## Estructura del Proyecto
```
.
├── Proyecto_Deep_Learning.ipynb   # Cuaderno Jupyter principal
├── images/                        # Carpeta para imágenes de dataset
│   ├── train/
│   │   ├── cats/
│   │   └── dogs/
│   └── test/
│       ├── cats/
│       └── dogs/
├── annotations/                   # Anotaciones del dataset
│   ├── trainval.txt
│   └── test.txt
└── README.md
```

## Contribuciones
Las contribuciones son bienvenidas. Si desea mejorar el proyecto o agregar funcionalidades, siéntase libre de clonar el repositorio y enviar sus pull requests.

## Licencia
Este proyecto se distribuye bajo la Licencia MIT.

## Contacto
Para cualquier consulta o ayuda adicional, por favor abra un issue en el repositorio de GitHub.

## Fuente de Aprendizaje
Este proyecto se inspiró y guió en gran medida por los conceptos y técnicas presentados en [Reconocimiento y clasificación de imágenes con Deep Learning](https://www.campusmvp.es/recursos/post/reconocimiento-y-clasificacion-de-imagenes-con-deep-learning.aspx) de CampusMVP. Este recurso fue fundamental para entender las bases del procesamiento de imágenes y la aplicación de redes neuronales convolucionales en tareas de reconocimiento y clasificación.