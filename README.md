# Gender and Age Detection using OpenCV

This project performs real-time face detection, gender classification, and age prediction using pre-trained models from OpenCV. It uses a combination of deep learning and computer vision techniques.

## Features
- Detects faces in an image or video feed.
- Predicts the gender (Male/Female) of detected faces.
- Estimates the age group of detected faces.

## Requirements
- Python 3.9
- OpenCV

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/Abubaker-khilji/gender-and-age-detection.git
   cd gender-and-age-detection
   ```
2. Set up a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Ensure the pre-trained models (`.caffemodel` and `.prototxt`) are in the same directory as `age.py`.
2. Run the script:
   ```bash
   python age.py
   ```
3. The program will process the video feed (from your webcam or an image) and display the detected faces with predicted gender and age.

## Project Structure
```
|-- age.py                # Main script to run the project
|-- requirements.txt      # Python dependencies
|-- README.md             # Project documentation
|-- pre-trained models/   # Pre-trained models used for detection and classification
```

## Pre-trained Models
- **Face Detection Model**: OpenCV's `deploy.prototxt` and `res10_300x300_ssd_iter_140000.caffemodel`.
- **Age Detection Model**: `age_deploy.prototxt` and `age_net.caffemodel`.
- **Gender Detection Model**: `gender_deploy.prototxt` and `gender_net.caffemodel`.

## Contributing
Feel free to fork this repository, make improvements, and submit pull requests. Suggestions and bug reports are welcome!

## License
This project is licensed under the MIT License.

---

### Acknowledgments
- OpenCV library for providing pre-trained models and tools for computer vision.

Happy coding! 😊

