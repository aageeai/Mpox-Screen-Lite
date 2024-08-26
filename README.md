# Mpox Screen Lite

This repository contains two machine learning models designed to detect skin conditions, with a focus on Mpox, using two different architectures: MobileNetV2 and YOLOv8. These models are implemented in the Jupyter notebooks `Mpox_Screen_Lite-MobileNetV2.ipynb` and `Mpox_Screen_Lite-YOLOv8.ipynb`.

## Getting Started

### Prerequisites
- Python 3.8+
- Jupyter Notebook or JupyterLab

### Installation

1. **Clone the repository:**
   ```
   git clone https://github.com/yourusername/mpox-detection.git
   cd mpox-detection
   ```

2. **Install required libraries:**

   For MobileNetV2 model:
   ```
   pip install tensorflow==2.8.0 
   ```

   For YOLOv8 model:
   ```
   pip install ultralytics==8.2.82
   ```

### Running the Notebooks

1. **Launch Jupyter Notebook:**
   ```
   jupyter notebook
   ```

2. Navigate to the notebook you wish to run:
   - `Mpox_Screen_Lite-MobileNetV2.ipynb` for the MobileNetV2 model
   - `Mpox_Screen_Lite-YOLOv8.ipynb` for the YOLOv8 model

3. Run the cells sequentially to see the model in action.

## Models

### MobileNetV2
- **File:** `Mpox_Screen_Lite-MobileNetV2.ipynb`
- **Description:** Utilizes the MobileNetV2 architecture pre-trained on ImageNet, fine-tuned for classifying three skin conditions: Mpox, Normal, and Other. It provides a straightforward demonstration of loading an image, processing it, and classifying it with associated confidence scores.

### YOLOv8
- **File:** `Mpox_Screen_Lite-YOLOv8.ipynb`
- **Description:** Employs the YOLOv8 model to detect and classify skin conditions directly from images. It outputs class predictions and confidence scores.

## Example Usage
- Ensure that your input images are located in the directory accessible by the notebook.
- Modify the `image_path` variable to point to your test images.

## Contributing
Contributions are welcome. Please fork the repository and submit pull requests to enhance the functionalities or documentation.
