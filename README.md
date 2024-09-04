# Water Purity Assessment Using GAN and Image Segmentation

## Project Overview
This project aims to develop an automated system for assessing water quality using Generative Adversarial Networks (GAN) with Negative Diffusion and Image Segmentation techniques. The system analyzes images of water samples to detect and classify impurities, providing a cost-effective and efficient solution for water quality monitoring.

## Features
- Automated impurity detection and classification.
- Real-time processing with optimized performance.
- Scalable for various applications from household to industrial settings.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/USERNAME/water-purity-assessment.git
   ```
2. Navigate to the project directory:
   ```bash
    cd water-purity-assessment
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
   
## Usage

1. Place your images in the `data/sample_images/` directory.

2. Run the model training script:

    ```bash
    python src/train_model.py
    ```

3. Use the inference script to evaluate new images:

    ```bash
    python src/inference.py --image_path path/to/image.jpg
    ```
## Technologies Used

- **Python**: For scripting and data processing.
- **TensorFlow**: Used for building and training the neural networks.
- **Keras**: High-level API for neural networks used in conjunction with TensorFlow.
- **OpenCV**: For image processing and manipulation.
- **NumPy**: For numerical computations and handling image arrays.
- **Matplotlib**: For visualizing data and model performance.

