# Bone Fracture Identification Using MaskFormer Segmentation and Vision Transformer (ViT) Model

## Aim of the Project

The objective of this research is to develop a robust and efficient system for detecting and segmenting bone fractures using advanced machine learning techniques. The project will employ MaskFormer for precise segmentation of fracture zones and the Vision Transformer (ViT) to enhance the overall identification process. The goal is to improve the accuracy, reliability, and speed of bone fracture identification in medical imaging by utilizing these state-of-the-art methods.

## Research Questions

- How can the combination of MaskFormer and Vision Transformer (ViT) models outperform conventional convolutional neural network (CNN) methods for medical imaging bone fracture segmentation and identification?
- What preprocessing procedures are recommended to enhance the consistency and quality of medical images when training advanced segmentation and classification models like MaskFormer and ViT?

## Methodology

The project will follow these steps:

1. **Data Collection and Preprocessing:**
   - Collect X-ray images of bones with and without fractures.
   - Preprocess the images to ensure consistency and quality, including resizing, normalization, and augmentation.

2. **Model Integration:**
   - Implement MaskFormer for segmenting fracture zones in the images.
   - Apply the Vision Transformer (ViT) model for the classification task, determining whether a fracture is present or not.

3. **Model Training:**
   - Train the MaskFormer model for segmentation on the dataset.
   - Train the ViT model using the segmented regions to classify images as "fractured" or "not fractured."

4. **Performance Evaluation:**
   - Evaluate the models' performance using standard metrics such as accuracy, precision, recall, and F1 score.

## How to Run the Code

### Prerequisites

Ensure you have the following packages installed:

- Python 3.11
- TensorFlow
- PyTorch
- OpenCV
- PIL
- Transformers
- Seaborn
- Scikit-learn
- NumPy
- Pandas
- Matplotlib
#### Inputs and Ouputs of the model

 - inputs for the model is images of x rays of bone
 - output for the model is fractured or not fractured
### Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/ABRPMGITHUB/finalproject.git
2. Install the required libraries from the requirements.txt
3. Go the folder where the repository is cloned.
4. Open the final code file in jupyter notebook.
5. Run the code from the menu bar in the jupyther notebook.