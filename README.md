## Prerequisites

The following tools and libraries are required to run the project.

### Software
- Python 3.9 or above
- Git
- VS Code or Jupyter Notebook

### Python Libraries
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- OpenCV
- Flask
- Pillow

### Installation Command

pip install tensorflow keras numpy pandas matplotlib scikit-learn opencv-python flask pillow




## Project Workflow

The PlantCare AI system follows the workflow below:

### 1. User Interface Interaction
The user accesses the web application and navigates to the image upload page.

### 2. Image Selection
The user uploads or captures an image of a plant leaf showing symptoms of disease.

### 3. Image Processing
The uploaded image is resized to 224x224 pixels and normalized to match the input requirements of the MobileNetV2 model.

### 4. Model Prediction
The pre-trained MobileNetV2 deep learning model processes the image and predicts the plant disease class.

### 5. Result Display
The web application displays the predicted disease along with basic recommendations.

---

## Complete Project Activities

### Data Collection and Preprocessing
- Download the New Plant Diseases Dataset
- Perform data exploration and visualization
- Apply image preprocessing and augmentation
- Split dataset into training and validation sets

### Model Building
- Import required libraries
- Load pre-trained MobileNetV2 model
- Add custom classification layers
- Configure model compilation

### Model Training
- Train the model using image data generators
- Monitor training progress
- Apply early stopping and learning rate reduction

### Model Evaluation
- Evaluate model performance
- Visualize training metrics
- Save the best performing model

### Application Development
- Create HTML templates
- Build Flask backend
- Integrate trained model with web interface
- Test the application end-to-end