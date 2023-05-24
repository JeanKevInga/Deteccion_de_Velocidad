<H1 align="center">
YOLOv8 Segmentation with DeepSORT Object Tracking(Smart City) </H1>

## Google Colab File Link (A Single Click Solution)
El enlace del archivo de google colab para la segmentación y el seguimiento de yolov8 se proporciona a continuación, puede verificar la implementación en Google Colab, y es una implementación de un solo clic
, solo necesita seleccionar el Tiempo de ejecución como GPU y hacer clic en Ejecutar todo.

[`Google Colab File`](https://colab.research.google.com/drive/1wRkrquf_HMV7tyKy2zDAuqqK9G4zZub5?usp=sharing)



## YOLOv8 with DeepSORT Object Tracking

[`Github Repo Link`](https://github.com/JeanKevInga/Deteccion_de_Velocidad.git)

## Object Segmentation and Tracking (ID + Trails)  using YOLOv8 on Custom Data
## Google Colab File Link (A Single Click Solution)
[`Google Colab File`](https://colab.research.google.com/drive/1cnr9Jjj5Pag5myK6Ny8v5gtHgOqf6uoF?usp=sharing)



## Steps to run Code

- Clone the repository
```
git clone https://github.com/MuhammadMoinFaisal/YOLOv8_Segmentation_DeepSORT_Object_Tracking.git
```
- Goto the cloned folder.
```
cd YOLOv8_Segmentation_DeepSORT_Object_Tracking
```
- Install the Dependencies
```
pip install -e '.[dev]'

```
- Setting the Directory.
```
cd ultralytics/yolo/v8/segment

```
- Downloading the DeepSORT Files From The Google Drive 
```

https://drive.google.com/drive/folders/1kna8eWGrSfzaR6DtNJ8_GchGgPMv3VC8?usp=sharing
```
- Después de descargar el archivo Zip de DeepSORT de la unidad, descomprímalo, vaya a las subcarpetas y coloque la carpeta deep_sort_pytorch en la carpeta ultralytics/yolo/v8/segment

- Downloading a Sample Videos from the Google Drive
- Demo Video 1
```
gdown "https://drive.google.com/uc?id=19P9Cf9UiJ9gU9KHnAfud6hrFOgobETTX"
```

- Demo Video 2
```
gdown "https://drive.google.com/uc?id=1rjBn8Fl1E_9d0EMVtL24S9aNQOJAveR5&confirm=t"
```
- Demo Video 3
```
gdown "https://drive.google.com/uc?id=1aL0XIoOQlHf9FBvUx3FMfmPbmRu0-rF-&confirm=t"
```
- Run the code with mentioned command below.

- For yolov8 segmentation + Tracking
```
python predict.py model=yolov8x-seg.pt source="test1.mp4"
```




[![Watch the Complete Tutorial for the Step by Step Explanation](https://img.youtube.com/vi/0JIPNk21ivU/0.jpg)]([https://www.youtube.com/watch?v=0JIPNk21ivU&t=244s](https://www.youtube.com/watch?v=0JIPNk21ivU))


## References
- https://github.com/ultralytics/ultralytics
