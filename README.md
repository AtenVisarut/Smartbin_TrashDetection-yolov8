# Smartbin_TrashDetection-yolov8
Real-time Waste Sorting with Deep Learning on an Embedded System
# SmartBin_TrashDetection-yolov8 🗑️🤖

**Real-time Waste Sorting with Deep Learning on an Embedded System**

## Introduction

An intelligent trash bin that automatically sorts waste using Deep Learning and IoT. The system uses a trained YOLOv8 model to analyze waste images and control servo motors to open the correct compartment lid.


--


## How It Works

1. **Image Capture**: Built-in camera captures real-time image of the waste  

2. **Image Analysis**: Raspberry Pi processes the image with YOLOv8 model  

3. **Commanding**: GPIO signals sent based on classification  

4. **Sorting**: Servo motors open the appropriate compartment lid  

--

## Dataset Information

**Source:** [RoboFlow Garbage Detection Dataset](https://universe.roboflow.com/garbage-detection-nalan/garbage-euqch)



### Dataset Statistics

| Metric          | Count  |

|-----------------|--------|

| Total Images    | 6,075  |

| Training Set    | 4,259 |

| Validation Set  | 1,200  |

| Test Set        | 616    |



*\*Note: Augmented training samples increase count beyond original dataset*



### Preprocessing

- Auto-Orient: Applied  

- Resize: 640x640 (stretched)  

- Augmentations: None applied  



### Class Distribution

The dataset contains 10 waste categories:

battery

cardboard

clothes

glass

metal

miscellaneous trash

organic

paper

plastic

shoes

---



## Hardware Requirements

| Component                     | Specification           |

|-------------------------------|-------------------------|

| Single Board Computer         | Raspberry Pi 3/4        |

| Camera                        | oker hd1080p   |

| Actuators                     | SG90 Servo Motors (x4)  |

| Power Supply                  | 5V 2A DC               |

| Custom Enclosure              | 3D printed/wooden bin   |



---



## Software Requirements

- **OS**: Raspberry Pi OS (32-bit)  

- **Python**: 3.7+ (colab)  

- **Key Libraries**:

  ```bash

  pip install opencv-python ultralytics RPi.GPIO numpy

  Developer

[Visarut tase]

[tenyama55@gmail.com]

[27/3/2025]
