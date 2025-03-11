# Human and Animal Identification in Flood and Unflooded Affected Areas Using Images by Pre-trained YOLO Model

## Overview

This project aims to detect humans and animals in both flood-affected and unaffected areas using images. It employs a pre-trained YOLO (You Only Look Once) model to efficiently identify and classify objects. The objective is to assist in disaster management by providing an automated method for identifying living beings in challenging environments.

## Features

- Detects humans and animals in flood-affected and unaffected areas.
- Utilizes a pre-trained YOLO model for fast and accurate detection.
- Supports image-based analysis for efficient disaster response.
- Helps in automating rescue operations by identifying stranded individuals and animals.

## Dataset

- The dataset consists of more than 100 images, including both flood-affected and normal conditions.
- Images are pre-processed and labeled to improve the accuracy of YOLO’s object detection.
- Augmentation techniques are applied to enhance the model’s robustness.

## Technologies Used

- **Deep Learning Framework**: TensorFlow / PyTorch
- **Object Detection Model**: YOLO (You Only Look Once)
- **Programming Language**: Python
- **Libraries**: OpenCV, NumPy, Matplotlib

## Workflow

1. **Data Collection & Preprocessing**

   - Gather images from various sources.
   - Annotate images for object detection.
   - Split dataset into training and testing sets.

2. **Model Selection & Training**

   - Use a pre-trained YOLO model.
   - Fine-tune the model with collected data.
   - Optimize performance metrics (precision, recall, mAP).

3. **Inference & Evaluation**

   - Run the model on new images.
   - Evaluate detection accuracy.
   - Improve performance by adjusting hyperparameters.

4. **Deployment**

   - Convert the model for real-time detection.
   - Integrate into a web or mobile-based application.

## Installation & Usage

### Prerequisites

- Python 3.x
- TensorFlow / PyTorch
- OpenCV
- YOLO Pre-trained Weights
- Required dependencies from `requirements.txt`

### Steps to Run

1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/human-animal-detection.git
   cd human-animal-detection
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Download YOLO weights and place them in the required directory.
4. Run the detection script:
   ```sh
   python detect.py --image path/to/image.jpg
   ```

## Results & Performance

- Model achieves high accuracy in detecting humans and animals in various conditions.
- Faster processing time enables real-time detection in emergency situations.
- Further improvements can be made with larger datasets and fine-tuning.

## Future Scope

- Integration with drone surveillance for large-scale disaster response.
- Enhancing model performance with more labeled data.
- Deployment as a cloud-based API for rescue teams.

## Contributors

- [Yaswanth]

## License

This project is licensed under the MIT License - see the LICENSE file for details.

