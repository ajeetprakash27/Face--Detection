# Face Detection

A simple real-time face detection application using OpenCV and Haar cascades.

## Description

This project demonstrates real-time face detection using OpenCV's Haar cascade classifiers. The application captures video from a webcam, processes each frame to detect faces, and draws green rectangles around detected faces in the live video feed.

## Features

- Real-time face detection from webcam feed
- Uses Haar cascade classifier for accurate detection
- Simple and lightweight implementation
- Easy to run in a Jupyter notebook

## Prerequisites

- Python 3.x
- OpenCV library
- Webcam (built-in or external)

## Installation

1. **Clone the repository:**
   ```
   git clone https://github.com/ajeetprakash27/Face--Detection.git
   cd Face--Detection
   ```

2. **Install required packages:**
   ```
   pip install opencv-python
   ```

3. **Ensure Haar cascade file is available:**
   The code uses the default Haar cascade frontal face detector that comes with OpenCV. If it's not found at the specified path, you may need to download it or adjust the path in the code.

## Usage

1. Open the `Face.ipynb` notebook in Jupyter Notebook or JupyterLab.

2. Run the cells in sequence:
   - First cell: Import OpenCV
   - Second cell: Execute the face detection code

3. The application will:
   - Access your default webcam (index 0)
   - Display a window showing the live video feed
   - Draw green rectangles around detected faces
   - Continue until you press the 'a' key to exit

4. Close the video window to end the session.

## Configuration

- **Webcam selection:** Change `cv2.VideoCapture(0)` to use a different camera index if needed.
- **Cascade file path:** Update the path in `cv2.CascadeClassifier()` if your Haar cascade XML file is located elsewhere.
- **Detection parameters:** Adjust `scaleFactor`, `minNeighbors`, `minSize` for different detection sensitivity.

## Troubleshooting

- **No video feed:** Ensure your webcam is connected and not being used by another application.
- **Import error:** Make sure OpenCV is properly installed.
- **Cascade file not found:** Download the Haar cascade XML files from OpenCV's GitHub repository and update the path.

## Dependencies

- opencv-python

## License

This project is open source. Please check the repository for license details.

## Contributing

Feel free to submit issues and enhancement requests!</content>
<parameter name="filePath">c:\Users\lucif\OneDrive\Desktop\Projects\Face_Detection\Face--Detection\README.md
