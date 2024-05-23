# DigitAladin

DigitAladin is an intuitive digit recognition app that tells you what you have drawn on the screen. Using a pre-trained neural network model, the app can predict the digit you draw on a canvas.

## Features

- Draw digits on a canvas.
- Predict the digit using a pre-trained convolutional neural network model.
- Visualize the drawn digit and the predicted result.
- Clear the canvas to draw again.

## Requirements

### Libraries
- Python 3.x.
- NumPy.
- TensorFlow.
- ipywidgets.
- ipycanvas.
- Pillow.
- Matplotlib.

### Model
- Pre-trained CNN model attached in the repository.

## Installation

To install and run DigitAladin, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Muhammadummerr/DigitAladin.git
    cd DigitAladin
    ```

2. **Install the required dependencies**:
    ```bash
    pip install numpy tensorflow ipywidgets ipycanvas pillow matplotlib
    ```

3. **Ensure you have the trained model file**:
   The trained model file `Model.keras` is attached in the repository. Ensure it is located in the appropriate directory as specified in the code:

## Usage

To run the DigitAladin app, execute the following command:

```bash
python App.py
```
This will launch the application window where you can draw digits on the canvas and get predictions.

## Acknowledgements

- The model used in this app is trained on the MNIST dataset.
- Thanks to the open-source community and dataset providers for providing tools and libraries that made this project possible.
