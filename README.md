The complete system can be processed in two different phases. The first phase is
about getting the input of images into application using a real time camera from farmers that is
images of their crop, processing the image, segmenting the image, extracting the features from
image using machine learning algorithm and then the detection and classification of sugarcane
crop disease . The second phase is about providing the service to the end user that is to detect
the disease crop from the field and spray the pesticides .The Proposed System will be helpful for
farmers to find a solution to their problem in a much more efficient manner

Firstly Dataset is gathered of different Disease of Suagarcane .The Pre-processed
images are then fed into MobileNetV2 model which is retrained according to the new customized
dataset to identify and classify the sugarcane disease into the four major diseases . The Trained
model is then obtained as the saved model which is further fed into the TensorFlowLite
converter to obtain .tflite file which can then be deployed in android applications. New disease
suspected plant images are then clicked and uploaded to the application where the trained model
executes to identify if the plant is diseased and classified accordingly. The application also helps
farmers by suggesting the remedial measures to be taken to address the particular disease at the
early stage thereby decreasing the crop loss.
