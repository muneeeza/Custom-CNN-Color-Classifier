# Custom-CNN-Color-Classifier
This project, developed as part of my deep learning course, is a Convolutional Neural Network (CNN)-based system designed to classify objects as black, colorful, or transparent and assign them to specific conveyor belts for sorting. Trained on a custom dataset with 80 labeled images per category, the model achieves accurate classification and sorting. A Gradio GUI is included for easy image uploads and real-time predictions.

## Key Features
* **Custom Dataset**: A dataset of 240 images (80 per category) labeled as black, colorful, or transparent.

        https://drive.google.com/drive/folders/1UYXpo-ctA25ccfG-XCW5lH50gUAEp5Ok?usp=sharing

* **Image Preprocessing**: Custom preprocessing to enhance image quality based on brightness and color properties.

* **CNN Model**: A convolutional neural network model trained to classify images into three categories.

* **Conveyor Belt Mapping**: Each category is mapped to a conveyor belt for easy sorting.

* **Interactive GUI**: A Gradio-based interface that allows users to upload images and receive real-time predictions.

  
## Model Architecture
The model is a custom CNN with layers optimized for image classification:
* **Convolutional Layers**: To detect color and transparency features.
* **Pooling Layers**: To reduce spatial dimensions.
* **Dense Layers**: To classify the image into one of three categories.

More details included in the report. 

