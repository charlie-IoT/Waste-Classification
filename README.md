# Waste-Classification
Predictive model trained using CNN to identify cans and bottles in waste

CNN-based model specifically designed to classify images into different predefined classes. It learns to extract relevant features from input images and map them to the corresponding classes, enabling accurate image classification.

Step1-Import Paramount dependecies:Tensorflow
                                  :opencv

Step2-Data Cleansing:import cv2
                    :import imghdr

Step3-Data processing: Scale data and split data for training and testing

Step4-Build Model:from tensorflow.keras.models import Sequential
                 :from tensorflow.keras.layers import Conv2D, MaxPooling2D, Dense, Flatten, Dropout
                 (Sequential model us that uses activation:'relu' and adam optimizer)

Step5-Train and Test model!

