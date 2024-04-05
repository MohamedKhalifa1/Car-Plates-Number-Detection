# Car Plates Number Detection using Object Detection and OCR

This repository contains code for detecting car plates numbers using object detection and Optical Character Recognition (OCR). The project utilizes the PyTesseract library and a custom dataset.

## Dataset
The dataset used for this project can be found on Kaggle at the following link: [Car Plates Numbers Dataset](https://www.kaggle.com/datasets/mohamedashrafkhalifa/car-plates-numbers).

## Notebooks
The project consists of the following notebooks:

1. **01_xml_to_csv.ipynb**: This notebook is used for converting XML annotations to CSV format, which is a common format for object detection datasets.

2. **02_object_detection.ipynb**: This notebook contains the code for training the object detection model using the converted dataset.

3. **03_prediction.ipynb**: This notebook demonstrates how to use the trained model for prediction on new images, including the OCR process to extract the numbers from the detected plates.

## Requirements
To run the notebooks and utilize the code in this repository, you need to have Python installed along with the following libraries:
- PyTesseract
- TensorFlow
- OpenCV
- Pandas
- Matplotlib

You can install these dependencies via pip:

```bash
pip install pytesseract tensorflow opencv-python pandas matplotlib
```

## Contact
For any inquiries or suggestions regarding the project, feel free to reach out to the repository owner at: m.ashraf.20162002@gmail.com

## Repository Link
[Car Plates Number Detection Repository](https://github.com/MohamedKhalifa1/Car-Plates-Number-Detection)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.