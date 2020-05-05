# Gender and Age Detector using OpenCV
</br>
OpenCV is an open source Computer vision and Machine Learning library. </br>

This library is capable of processing real-time image and video while also boasting analytical capabilities </br>

In this Project, Deep Learning is used to accurately identify the gender and age of a person from a single image of a face. <br />

The predicted gender may be one of ‘Male’ and ‘Female’, and the predicted age may be one of the following ranges-<br/> 
- (0 – 2)
- (4 – 6)
- (8 – 12)
- (15 – 20)
- (25 – 32)
- (38 – 43)
- (48 – 53)
- (60 – 100) 

The 3 trained models were too big to upload 

* For face detection , a .pb file which is a protobuf file which has a trained tensorflow model.
* For age and gender, the .prototxt files describe the network configuration and the .caffemodel file defines the internal states of the parameters of the layers. 
* Gad.py which contains the main OpenCv code which gets input either from webcam or from an image in the same directory using the argparse library by specifying the image as an argument. It runs the trained models and predicts the age and gender of the user from the image or webcame and displays it back as output. 

## Output Examples

* From Webcam

![](https://github.com/hrithikkothari1234/Gender-Age-Detector/blob/master/exampleimages/output1.png?raw=true)

* From Image

![](https://github.com/hrithikkothari1234/Gender-Age-Detector/blob/master/exampleimages/output2.png?raw=true)
