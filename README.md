# Human-Activity-Recognition
# Human Activity Recognition Using Smartphone Data

## Overview
This project aims to classify various human activities such as walking, standing, sitting, etc., using accelerometer and gyroscope data collected from smartphones. The classification is performed using a Support Vector Machine (SVM) model, which effectively learns patterns in the data to predict activities.

##Application

One of the best applications of Human Activity Recognition (HAR) using smartphone data is in health monitoring and fitness tracking. This application stands out due to its wide impact on individual health, the growing popularity of fitness apps, and its potential to enhance overall well-being. Here’s a closer look:

Health monitoring through HAR involves using data collected from smartphone sensors (accelerometers and gyroscopes) to track and analyze a person's physical activities. This application empowers users to take charge of their health and fitness by providing actionable insights based on their daily movements.



## Table of Contents
- [Features](#features)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Features
- Classifies multiple human activities using smartphone sensor data.
- Utilizes accelerometer and gyroscope data.
- Implements a Support Vector Machine (SVM) algorithm.
- Provides evaluation metrics to assess model performance.

## Dataset
The dataset used in this project consists of time-series data from smartphone sensors, including:
- **Accelerometer Data**: Measures the acceleration forces acting on the device.
- **Gyroscope Data**: Measures the rate of rotation around the device's three axes.

The dataset files are organized as follows:
- `train/X_train.txt`: Training feature data.
- `train/y_train.txt`: Training labels.
- `test/X_test.txt`: Test feature data.
- `test/y_test.txt`: Test labels.
- `features.txt`: List of feature names.
- `activity_labels.txt`: Mapping of activity labels.

## Installation
To set up this project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/human-activity-recognition.git
   cd human-activity-recognition
