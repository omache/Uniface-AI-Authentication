# Face Recognition Application

## Description
This is a face recognition application that uses deep learning techniques to identify and recognize faces. It consists of a backend and a frontend component.

## Backend
The backend code for the application is organized in the following folders:

- `FaceID.ipynb`: Jupyter Notebook containing the backend code for face recognition.
- `camer_test.py`: Python script for testing the camera functionality.
- `camera_test_input_box`: Folder containing input data for camera testing.
- `digi_face_dataset.py`: Python script for creating the face dataset.
- `joas_model.py`: Python script containing the main model for face recognition.
- `model_test.py`: Python script for testing the face recognition model.
- `takingInFile.py`: Python script for processing input images.
- `README.md`: Markdown file containing information about the backend.

### Dependencies
The backend code requires the following dependencies:
- `numpy`
- `scipy`
- `os`
- `cv2`
- `shutil`
- `random`
- `torch`
- `wandb`
- `torchvision`
- `torch.nn`
- `torch.optim`
- `torch.utils.data`
- `efficientnet_pytorch`
- `PIL`
- `sys`
- `timm`

To install the dependencies, run the following command:
`pip install numpy scipy opencv-python torch torchvision efficientnet_pytorch pillow`

### Running the Backend
To run the backend code, follow these steps:

1. Make sure you have all the dependencies installed.
2. Open the `joas_model.py` file in a Python IDE or Jupyter Notebook.
3. Set the correct paths for the data in the `path` and `data_path` variables.
4. Run the script to perform the face recognition tasks.

## Frontend
The frontend code for the application is located in the `frontend` folder.

### Running the Frontend
To run the frontend, follow these steps:

1. Open the `frontend` folder in a web development environment or code editor.
2. Start a local server to serve the frontend files.
3. Access the application in a web browser using the local server URL.

## License
This project is licensed under the [MIT License](LICENSE).
