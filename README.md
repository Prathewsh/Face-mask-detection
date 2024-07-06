# Face Mask Detection

## Overview

Face Mask Detection is a Python-based project designed to detect whether people in images or video streams are wearing face masks. This project utilizes deep learning models to perform real-time detection, providing a valuable tool for ensuring compliance with health and safety protocols, especially during the COVID-19 pandemic.

## Features

- Real-time face mask detection in video streams
- High accuracy with pre-trained deep learning models
- Easy-to-use interface for testing with images and video files
- Customizable for different deployment environments

## Installation

### Prerequisites

- Python 3.7 or higher
- OpenCV
- TensorFlow or PyTorch
- NumPy

### Steps

1. Clone the repository:

   ```sh
   git clone https://github.com/Prathewsh/Face-mask-detection.git
   cd Face-mask-detection
   ```

2. Install the required packages:

   ```sh
   pip install -r requirements.txt
   ```

3. Download the pre-trained model weights:
   - [Link to model weights] (provide a link to the model weights here)

## Usage

### Running the Detection on Images

1. Place your images in the `images` directory.
2. Run the script:
   ```sh
   python detect_mask_image.py --image images/your_image.jpg
   ```

### Running the Detection on Video

1. Ensure you have a video file or a webcam connected.
2. Run the script:
   ```sh
   python detect_mask_video.py --video videos/your_video.mp4
   ```
   or for webcam:
   ```sh
   python detect_mask_video.py --video 0
   ```

### Command Line Arguments

- `--image`: Path to the input image file.
- `--video`: Path to the input video file or webcam index.

## Example Results

### Image Detection

![Image Result](results/image_result.jpg)

### Video Detection

![Video Result](results/video_result.gif)

## How It Works

The face mask detection system works in the following steps:

1. **Face Detection**: Uses a pre-trained face detection model to locate faces in the input.
2. **Mask Classification**: Classifies the detected faces into two categories: with mask and without mask.
3. **Annotation**: Annotates the image or video frames with the detection results.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes and push to your fork.
4. Create a pull request with a description of your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- This project uses models and datasets from various open-source projects.
- Special thanks to the contributors of the TensorFlow, OpenCV, and PyTorch communities.

## Contact

For any questions or suggestions, please open an issue or contact [prathewsh123@gmail.com](mailto:prathewsh123@gmail.com).
