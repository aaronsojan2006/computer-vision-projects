# Computer Vision Projects

## Overview
A collection of five AI and computer vision projects developed using Python and Google Colab. These projects explore driver safety, vehicle identification, traffic-scene analysis, fruit freshness classification, and plant growth monitoring.

## Project 1: Driver Drowsiness Detection

### 1. Problem Statement
Driver drowsiness can reduce attention and reaction time, increasing the risk of road accidents.

### 2. Objective
To classify images into eye and yawning states associated with possible driver drowsiness.

### 3. Dataset
Images organized into four classes: `Closed`, `Open`, `no_yawn`, and `yawn`.

### 4. Methodology
The images are processed using a MobileNetV2-based classification model. The model predicts the class and provides confidence scores.

### 5. Tools/Libraries Used
Python, Google Colab, TensorFlow/Keras, MobileNetV2, NumPy, Matplotlib.

### 6. Results
Recorded test accuracy: **92.15%**.

### 7. Conclusion
The project demonstrates image classification for identifying visual signs associated with driver drowsiness. Further real-world testing is needed.

## Project 2: Vehicle License Plate Detection

### 1. Problem Statement
Manually locating vehicle license plates can be time-consuming.

### 2. Objective
To detect or locate license plate regions in vehicle images.

### 3. Dataset
Vehicle and license plate images used by the notebook. The exact dataset source and size are not specified here.

### 4. Methodology
The input image is processed using the detection method implemented in the notebook, and potential license plate regions are identified and displayed.

### 5. Tools/Libraries Used
Python, Google Colab, and the image-processing or detection libraries used in the notebook.

### 6. Results
The notebook demonstrates the license plate detection workflow. A numerical accuracy value has not been established here.

### 7. Conclusion
The project demonstrates a computer vision approach to vehicle license plate localization.

## Project 3: Traffic Sign / Traffic Region Detection

### 1. Problem Statement
Identifying traffic signs in complex road scenes can be challenging because of vehicles and background objects.

### 2. Objective
To analyze traffic-scene images and identify potential traffic-sign regions.

### 3. Dataset
Traffic-scene images used as input to the notebook. The exact source and size are not specified here.

### 4. Methodology
The image is processed to identify possible regions of interest. Bounding boxes and labels are drawn around detected regions, and the number of regions is displayed.

### 5. Tools/Libraries Used
Python, Google Colab, OpenCV, NumPy, Matplotlib.

### 6. Results
One demonstration reported **8 possible traffic-sign regions**. Some detections included vehicles and background structures, so these were not all confirmed traffic signs.

### 7. Conclusion
The prototype demonstrates preliminary traffic-scene region detection. Better filtering and testing with labelled images could improve reliability.

## Project 4: Apple Freshness Detection

### 1. Problem Statement
Visually distinguishing fresh fruit from rotten fruit can be subjective and time-consuming.

### 2. Objective
To analyze fruit images and classify them as fresh or rotten, with a percentage-based output.

### 3. Dataset
Fruit images supplied to the notebook. The exact dataset source, size, and class distribution are not specified here.

### 4. Methodology
The input fruit image is processed by the implemented classification method. The system displays a freshness category and its associated percentage.

### 5. Tools/Libraries Used
Python, Google Colab, and the image-processing or machine-learning libraries used in the notebook.

### 6. Results
The prototype displays a fresh or rotten prediction with a percentage-based result. A verified accuracy value has not been established here.

### 7. Conclusion
The project demonstrates image-based fruit freshness classification. Testing with a diverse, labelled dataset is needed to assess reliability.

## Project 5: Plant Growth Monitoring

### 1. Problem Statement
Manually comparing plant images can make changes in visible foliage difficult to measure.

### 2. Objective
To compare plant images and estimate changes in foliage coverage, canopy width, and canopy height.

### 3. Dataset
Two AI-generated plant images representing earlier and later stages. They are demonstration images, not real observations of a growing plant.

### 4. Methodology
The images are resized and converted to HSV colour space. Green-colour thresholding identifies potential foliage, segmentation masks are generated, and foliage coverage and canopy dimensions are compared.

### 5. Tools/Libraries Used
Python, Google Colab, OpenCV, NumPy, Matplotlib.

### 6. Results
The prototype generates foliage masks and compares estimated foliage coverage and canopy dimensions. These measurements are image-based estimates, not verified biological growth rates.

### 7. Conclusion
The project demonstrates image processing for plant-image comparison. Real plant photographs and improved segmentation would help establish its real-world accuracy.

## Overall Conclusion
These five projects demonstrate applications of computer vision in driver safety, vehicle identification, traffic-scene analysis, fruit freshness classification, and plant monitoring. Further evaluation with representative datasets can help improve reliability and practical usefulness.

## Limitations
Dataset sources, model configurations, and evaluation metrics should be documented from each notebook where available. Results from prototypes should not be interpreted as proof of real-world accuracy without appropriate testing.
