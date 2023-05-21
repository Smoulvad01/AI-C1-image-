## **Overview**

The Eye Blinking Detection Software is designed to detect and track eye blinks using rule based, KNN & Logistic regression and CNN models. The models are developed with a focus in photo editing software, but can be integrated into various applications, such as driver monitoring systems, attention tracking, and VR capabilities.

## **Requirements**

- Python 3.7 or above
- CV2 library
- Dlib library
- NumPy library
- TensorFlow library
- Sklearn library
- Matplotlib library

## Dataset
We were not able to upload dataset on GitHub due to size limitation but you can download the dataset on the following link: https://www.kaggle.com/datasets/serenaraju/yawn-eye-dataset-new?resource=download 

## **Usage**

- Install the required libraries by running the command pip install livelossplot.
- Ensure that you have the necessary dependencies installed. If any library is missing, you can install it using pip install [library-name].
- Add the dataset to Google Drive --> MyDrive and give access
- Follow the instructions on the text cells to train, evaluate and test the models.
- View the blink detection results displayed on the screen or customize the output as needed.

## **File structure**

- README.md to understand the scope and goal of the project. 
- Inspecting_image_data, we inspected the data before and after processing
- Image_Analysis_CNN cointains the loading of data, processing, KNN, Logistic Regression, CNN and applying the CNN on new images of eyes, taken by us 
- Rule_Based_Model contains a rule based model to identify open or closed eyes, used on the images taken by us. 


## **License**

This project is published under the MIT License.

## **Acknowledgements**

We would like to express our gratitude to the contributors of the open-source libraries used in this project, as well as the research community for their valuable insights and resources.

Please refer to the documentation and code comments for more detailed information on how to use and customize the eye blinking detection software.
