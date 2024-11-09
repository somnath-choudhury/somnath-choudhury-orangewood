# somnath-choudhury-orangewood

This repository provides code for training a YOLOv8 object detection model on the Aquarium dataset, aimed at supporting coral reef conservation efforts. The project utilizes Roboflow for dataset preparation and Google Colab for model training. Key performance metrics—such as precision, recall, and mean Average Precision (mAP)—are used to evaluate model efficacy.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Training](#training)
- [Evaluation](#evaluation)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project employs YOLOv8 (You Only Look Once, Version 8), a deep learning model tailored for real-time object detection tasks, to identify marine life in aquarium settings. YOLOv8 is customizable and ideal for applications like marine conservation due to its efficiency and high accuracy.

## Dataset

The Aquarium Dataset, used for model training and testing, includes annotated images of marine species commonly found in aquariums, such as fish, corals, and other underwater organisms.

- **Source**: Kaggle - Aquarium Data COTS
- **Classes**: Multiple, including fish and coral
- **Annotations**: Bounding boxes in YOLO format

## Installation

Clone this repository and navigate to the directory:

```bash
git clone https://github.com/your-username/aquarium-object-detection.git
cd aquarium-object-detection
