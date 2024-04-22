# Automated Attendance System Using Face Recognition

Automated Attendance System Using Face Recognition is a project developed by Ali Hafeez as a part of his BS Artificial Intelligence studies. This project utilizes FaceNet for face detection, MTCNN for face cropping, and a Convolutional Neural Network (CNN) for training and testing accuracy. The system enables real-time attendance tracking by accessing the laptop's webcam.

## Features

- Face detection using FaceNet
- Face cropping using MTCNN
- Training and testing accuracy using CNN
- Real-time attendance tracking via webcam

## Requirements

- Python 3
- OpenCV
- TensorFlow
- NumPy

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your_username/automated-attendance-system.git
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

Make sure you have Jupyter Notebook installed. If not, you can install it using pip:

   ```bash
   pip install jupyterlab
   ```

Start the Jupyter Notebook server by running the following command in your terminal:

   ```bash
   jupyter notebook
   ```

This will open a new tab in your web browser showing the Jupyter Notebook dashboard. Navigate to the location of your `Automated_Attendance_System.ipynb` file and click on it to open it.

You can now run the code cells in the notebook by pressing Shift + Enter.

If you specifically want to run the code in the notebook using Python outside of Jupyter Notebook, you can convert the notebook to a Python script using the following command:

```bash
jupyter nbconvert --to script Automated_Attendance_System.ipynb
```

This will create a `.py` file that you can then run using the `python` command. However, note that some functionalities of Jupyter Notebook, such as interactive widgets, may not work in a regular Python script.


3. Run the application:

   ```bash
   python Automated_Attendance_System.py
   ```

## Usage

1. Ensure that your webcam is connected and functional.
2. Run the `main.py` file.
3. The application will detect faces in real-time and mark attendance accordingly.

## Acknowledgements

This project was developed with the help of the following resources:

- [FaceNet](https://github.com/davidsandberg/facenet)
- [MTCNN](https://github.com/ipazc/mtcnn)
- [TensorFlow](https://www.tensorflow.org/)

