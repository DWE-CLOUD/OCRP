# CAPTCHA Recognition Model

## Overview

This project implements a CAPTCHA recognition model that can be trained to recognize and decode CAPTCHA images. The model uses deep learning techniques to accurately predict the characters in CAPTCHA images.

## Prerequisites

- Python 3.x
- TensorFlow
- Keras
- OpenCV
- NumPy
- Matplotlib

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/DWE-CLOUD/OCRP
    cd OCRP
    ```

## Dataset

Dataset will be fetched directly from our github repo . No need to download

## Training the Model

To train the model, remove the `Models` folder if it exists:

```bash
rm -rf Models
```

Then run the training script:

```bash
python train_model.py
```

## Running the Model

Once the model is trained, you can use it to recognize CAPTCHA images. To run the model on a new image:

```bash
python recognize_captcha.py --image path_to_image
```

## Files and Directories

- `train_model.py`: Script to train the CAPTCHA recognition model.
- `recognize_captcha.py`: Script to use the trained model for CAPTCHA recognition.
- `requirements.txt`: List of required Python packages.
- `Models/`: Directory to store the trained model.
- `dataset/`: Directory containing the training and testing data.

## Acknowledgements

- This project is inspired by various CAPTCHA recognition research papers and implementations available online.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---

Feel free to contribute to the project by submitting issues or pull requests. Happy coding!
