# Detección de Emociones Usando Redes Neuronales Convolucionales (CNN)

Este proyecto utiliza Redes Neuronales Convolucionales (CNN) para la clasificación de emociones en imágenes faciales utilizando el conjunto de datos "Facial Emotion Recognition" (FER) disponible en Kaggle. El proyecto compara dos arquitecturas de CNN y evalúa su rendimiento utilizando métricas como la precisión y la pérdida. Los modelos entrenados se prueban con imágenes nuevas para detectar la emoción presente.

## Conjunto de Datos
El conjunto de datos utilizado en este proyecto contiene imágenes de rostros con siete emociones distintas:
- Enojo (Angry)
- Asco (Disgust)
- Miedo (Fear)
- Felicidad (Happy)
- Neutralidad (Neutral)
- Tristeza (Sad)
- Sorpresa (Surprise)
Las imágenes están divididas en carpetas de entrenamiento y prueba, y han sido preprocesadas para ser de tamaño 48x48 píxeles y en escala de grises.

## Requisitos Previos
Para ejecutar este proyecto, necesitarás:
- **Python 3.8+**
- **Jupyter Notebook**
- **pip** instalado para manejar las dependencias

### Instalación
1. Clona este repositorio en tu máquina local:
   ```bash
   git clone https://github.com/wuiquique/Emotion-Detection-NN.git
   cd Emotion-Detection-NN
   ```

2. Crea un entorno virtual (venv) para instalar las dependencias necesarias:
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate  # En Windows usa `venv\Scripts\activate`
   ```

3. Instala las dependencias utilizando el archivo `requirements.txt`:
   ```bash
   pip install -r requirements.txt
   ```

### Dependencias
El archivo `requirements.txt` contiene las siguientes bibliotecas esenciales:
- `numpy`
- `pandas`
- `matplotlib`
- `opencv-python`
- `tensorflow`
- `scikit-learn`
- `jupyter`
