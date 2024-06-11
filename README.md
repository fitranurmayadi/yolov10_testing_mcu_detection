# MCU Board Detection with YOLOv10

This repository contains the code and dataset for detecting multiple MCU boards using YOLOv10. This project is a simple experimentation to understand the detection capabilities of YOLOv10.

## Table of Contents

- [Dataset Creation](#dataset-creation)
- [Data Annotation](#data-annotation)
- [Model Training](#model-training)
- [Model Inference](#model-inference)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Dataset Creation

The dataset was created using a USB camera connected to a computer. We captured images at a rate of 4 photos per second using a Python script.

[Dataset Creation Script](../Create%20dataset)

## Data Annotation

Data annotation was performed using Roboflow. The process included:
- Data augmentation
- Dataset splitting into train, validation, and test sets
- Checking data proportions

[Dataset link](https://universe.roboflow.com/uji-coba-yolov8/mcu-board-detection)

## Model Training

The model was trained using YOLOv10 on Google Colab. The training script is available in the repository.

[Training Script](../Train)

## Model Inference

The trained model was downloaded and used for inference on a local computer with a USB camera.

[Inference Script](../Inference)

## Results

The results of the detection process are promising, showing the capabilities of YOLOv10 in detecting various MCU boards.

### Screenshots

Here are some screenshots of the detection results:

![Detection Example 1](path/to/screenshot1.png)

### Video Demonstration

You can watch the video demonstration of the model in action on YouTube:

[![Watch the video](https://img.youtube.com/vi/<VIDEO_ID>/0.jpg)](https://www.youtube.com/watch?v=<VIDEO_ID>)

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.
