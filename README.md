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

[Dataset Creation Script](https://github.com/fitranurmayadi/yolov10_testing_mcu_detection/tree/main/Create%20dataset)

## Data Annotation

Data annotation was performed using Roboflow. The process included:
- Data augmentation
- Dataset splitting into train, validation, and test sets
- Checking data proportions

## Model Training

The model was trained using YOLOv10 on Google Colab. The training script is available in the repository.

[Training Script](https://github.com/fitranurmayadi/yolov10_testing_mcu_detection/blob/main/yolov10_MCU_Board_Object_Detection.ipynb)

## Model Inference

The trained model was downloaded and used for inference on a local computer with a USB camera.

[Inference Script](link-to-github-script)

## Results

The results of the detection process are promising, showing the capabilities of YOLOv10 in detecting various MCU boards.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.
