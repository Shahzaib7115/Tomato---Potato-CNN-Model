Vegetable Image Classifier (CNN Project)

This is a small deep learning project I built to classify vegetables — right now it can recognize Tomatoes and Potatoes using a Convolutional Neural Network (CNN) built with TensorFlow and Keras.

I trained the model on a custom dataset and used image augmentation, pooling, and dropout layers to reduce overfitting. The model performs really well — it reached around 99% training accuracy and 100% test accuracy on my dataset.

🔍 What this project does

Loads and trains a CNN on vegetable images

Saves the model in keras format so you don’t have to retrain it every time

Lets you upload an image (in Colab) and instantly see the prediction

Shows confidence percentage along with the predicted label

🧱 Model Structure

The CNN includes:

Convolution + MaxPooling layers to detect image features

Dropout layers to avoid overfitting

Fully connected Dense layers for classification

Softmax at the end for predicting the right class

📊 Results

Training Accuracy: ~99%

Validation Accuracy: ~100%

Test Accuracy: ~100%
(might be slightly overfitted on small datasets, but works great in tests!)

⚙️ Tools & Libraries

TensorFlow / Keras

NumPy

Matplotlib

Google Colab
