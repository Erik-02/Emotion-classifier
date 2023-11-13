# Emotion-classifier

Emotion detection in images is the process of using AI and computer vision to recognize and interpret human emotions conveyed in pictures and videos, enabling applications in areas like user experience, mental health, and marketing. This project focusses on using AI to be able to detect the emotional state of a human while watching the company's advertisements.

The first part of this project started with understanding the business problem and having to clearly define the wants and needs of the company. For the task I then had to create a CNN model that can capture the differences between the required emotions, Happy, Sad and Neutral. The CNN model was then saved for futher usage.

To be able to use the model with ease I created a Gradio UI interface that can be hosted online or on the business local server. This UI provides a simple way of uploading an image and provides the clasification of this image along with the predicted probability.

The CNN model was trained on a total of 14400 images, with each emotion class containing 4800 images. The data that I used was the FEr-2013 emotion image dataset, available on Kaggle. I used Keras and Tensorflow to build and train the model. I tried out Transfer learning models such as VGG16 and implemented data augmentation techniques such as colour rescaling, image rotation and flipping. The model was evluated using the 80/20 split for training and testing.

For a visual understanding of each component please refer to the UML-diagram. The dataset can be found here:https://www.kaggle.com/datasets/msambare/fer2013.
