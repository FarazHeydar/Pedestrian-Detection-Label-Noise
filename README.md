# Pedestrian-Detection-Label-Noise
This repository contains the official implementation and dataset for the course project: *From Blindness to Robustness: Analyzing and Mitigating Asymmetric Label Noise in YOLOv7 Pedestrian Detection.*

## Quick Start
Click the badge below to run the code directly in your browser without any setup:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/FarazHeydar/Pedestrian-Detection-Label-Noise/blob/main/Pedestrian_Detection_Label_Noise.ipynb)

## Dataset
The dataset used in this project is available at:

Custom Dataset:
- [**CustomImages**](https://drive.google.com/file/d/1PUtxnGw6LzSpo6MCrkJUw8ZRPPqZ7D3H/view?usp=drive_link)
- **Description:** This is a custom-collected dataset used to supplement the primary training data. It contains 267 images. The data was collected using local environments (Thunder Bay, Canada) and targeted web scrap-ing and is annotated for pedestrians.

CityPerson Dataset:
- [**Cityscape**](https://www.kaggle.com/datasets/kavithak1388/cityscapes)
- [**CityPersonsAnnotations**](https://www.kaggle.com/datasets/wildred/city-persons-annotations)
- **Description:** The CityPersons dataset is specifically designed for pedestrian detection. It consists of 5,000 images (2,975 for training, 500 for validation, and 1,525 for testing) recorded in street scenes across 50 different cities. The dataset provides high-quality bounding box annotations for pedestrian classes (pedestrian, rider, sitting person, etc.) and covers various occlusion levels and pose variations.

## Acknowledgements
This implementation is based on the YOLOv7 framework. We thank the authors for their open-source contribution.
- [**Original YOLOv7 Repository:**](https://github.com/WongKinYiu/yolov7)

## Usage
1. Open the Colab notebook linked above.
2. The second cell in the notebook downloads the dataset automatically. No manual download is required.
3. Run all cells (instructions are clear and accessible through markdowns and comments) to reproduce the results found in Table 3 of the report.
