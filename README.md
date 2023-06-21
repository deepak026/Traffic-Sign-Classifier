# Traffic Sign Classification
This project aims to classify traffic signs using a Convolutional Neural Network (CNN). It uses the German Traffic Sign Recognition Benchmark (GTSRB) dataset, which consists of images of 43 different types of traffic signs.

## Requirements
* Python 3.x
* Numpy
* Pandas
* Matplotlib
* OpenCV (cv2)
* TensorFlow
* Keras

## Installation
1. Clone the repository:
  ```sh
  git clone https://github.com/your-username/traffic-sign-classification.git
  ```
2. Install the required dependencies:
  ```sh
  pip install -r requirements.txt
  ```
3. Download the GTSRB dataset and extract it into the project directory.

## Usage
1. Run the ***'train.py'*** script to train the CNN model on the dataset:
  ```sh
  python train.py
   ```
2. The trained model will be saved as my_model.h5.

3. Run the test.py script to evaluate the model on the test dataset and calculate the accuracy:
  ```sh
  python test.py
  ```
4. The accuracy of the model on the test dataset will be displayed.

## Results
* The training process will output the accuracy and loss plots for the model.
* The accuracy of the model on the test dataset will be displayed after running the test.py script.

## License
This project is licensed under the **MIT License**.

## Acknowledgments
The GTSRB dataset: http://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset




