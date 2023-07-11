# ASL-Detection
Hey there, welcome to my project  "American Sign-language Detection" which I have developed using Tensorflow and Python in Jupyter Notebook.
The model which I have used for training purposes is SSD MobileNet V2 FPNlite 320x320 from tensorflow 2 model zoo.
Let me give you a brief walkthrough of all the files and folders which I have included.

Folders
Test: It contains all the properly labeled images along with their .xml files. This can be used for testing.
Train: It contains all the properly labeled images along with their .xml files. This can be used for training.
Both the testing and training folder contains my data sets which I have collected through the webcam.

Files:
DataCollection2: It is a jupyter notebook that contains all the codes for image collection through webcam.
Labeling: It contains the Python codes related to labeling our image by using Pascal VOC and correspondingly creating the .xml files.
Training&Detection: It contains all the code starting from creating the paths, installing the model and all the necessary pipelines, creating label maps and tf records, training code as well real-time detection through the webcam.

Important Links:
Here I am adding some Important GitHub links that may be helpful for you.
Tensorflow 2 Model Zoo: https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/tf2_detection_zoo.md
LabelImg tool: https://github.com/heartexlabs/labelImg

