# Image Human Segmentation Using U-Net Architecture

## Business Understanding
This project focuses on processing images to identify and segment humans within them. By utilizing the U-Net architecture, the goal is to accurately separate humans from the background in images, aiding in various applications such as object detection, surveillance, and image editing.

## Data Understanding
The dataset consists of original images paired with ground truth label images, where the labels represent the masked areas corresponding to humans in the original images.

## Screenshots
![U-Net Architecture](Unet.png)
![Image Masking with OpenCV](color.png)
![Sample Output](output.png)

## Technologies
- PyTorch
- OpenCV (cv2)
- NumPy
- Pandas
- Matplotlib.pyplot
- train_test_split
- tqdm
- Helper

## Setup
To set up this project, execute the following code in your notebook to install required packages and download the dataset from GitHub using git clone:
```python
!pip install segmentation-models-pytorch
!pip install -U git+https://github.com/albumentations-team/albumentations
!pip install --upgrade opencv-contrib-python
!git clone https://github.com/parth1620/Human-Segmentation-Dataset-master.git

## Accuracy
After 25 epochs:
- Training Loss: 0.10180051624774933
- Validation Loss: 0.19108986854553223

## Status
The project has been successfully completed.
