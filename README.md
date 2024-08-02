# Traffic-Signal-detection-Model
Developed a traffic sign detection model using YOLOv9. Created a custom dataset by capturing and labeling traffic sign images, enhancing it with data augmentation and preprocessing. The YOLOv9 model was optimized and rigorously evaluated, achieving high accuracy. This project highlights skills in data handling, model development, and evaluation.

Overview

This project demonstrates a traffic sign detection model built using YOLOv9, a state-of-the-art object detection algorithm. The model is trained on a custom dataset that I created, which includes a diverse collection of traffic sign images. The goal of this project is to detect and classify traffic signs accurately, with applications in autonomous driving and intelligent transportation systems.

Project Details

Custom Dataset
Description: The dataset consists of around 800 labeled images of traffic signs captured from German roads. The images cover a wide range of traffic sign types and conditions to ensure robustness. around 6 classes 
Dataset Preparation: Images were labeled and organized into classes using annotation tools. Data augmentation techniques were applied to increase the diversity and robustness of the dataset.
YOLOv9 Model
Model: YOLOv9, known for its efficiency and accuracy in object detection tasks, is used to train the traffic sign detection model.
Features: YOLOv9 provides real-time object detection with high accuracy, making it suitable for traffic sign recognition tasks.
Getting Started
To train the model on your own custom dataset using YOLOv9, follow these steps:

1.Clone the Repository

%git clone https://github.com/yourusername/traffic-sign-detection.git
cd traffic-sign-detection


2.Setup Environment
Ensure you have the necessary libraries installed. You can use the provided requirements.txt to set up your environment.

%pip install -r requirements.txt

3. Prepare Your Custom Dataset
Format: Ensure your dataset follows the YOLO format for annotations. The images and labels should be organized into training and validation sets.
Structure: Place your dataset in the appropriate directories as specified in the provided Colab file.
4. Train the Model
Colab File: Use the provided Colab notebook to train the YOLOv9 model with your dataset. This notebook includes steps for setting up the environment, configuring the model, and running the training process.
5. Evaluate and Use the Model
After training, you can evaluate the model's performance and use it for inference on new images. Detailed instructions are included in the Colab notebook.

