# Application-of-Face-mask-detector-rakshak-2.0-mini-project-2

This a very simple application of the face mask detector. This code can detect people without a face-mask using a camera and also alert when the room is full. We can use this along with a mechanism to operate a door, so that the person entering the room has to face the camera, the code verifies if the person is wearing a mask, and the door opens for people with a mask. When the person is not wearing a mask, or when room is full, the door can remain closed and give an alert. This can used in meeting rooms, malls, and other public gathering areas.

The face mask detector:
The basic requirement for this is to identify the face in the percieved image captured in through camera. This is achieved through Haar cascade files.
Very good explanation of face detection can be found here: https://www.datacamp.com/community/tutorials/face-detection-python-opencv 

For downloading the haar cascade files: https://github.com/opencv/opencv/tree/master/data/haarcascades - you can also find classifiers for different features here.

This code uses the concept of convolution neural networks. A very clear and good explanation can be found here:

https://e2eml.school/how_convolutional_neural_networks_work.html

https://www.analyticsvidhya.com/blog/2018/12/guide-convolutional-neural-network-cnn/

After the model saving is done, the model with a good accuracy an be loaded into the rakshak 2-o.py code.

# Code and database credits:

https://github.com/prajnasb/observations/tree/master/experiements/data

https://github.com/aieml/face-mask-detection-keras

https://towardsdatascience.com/covid-19-face-mask-detection-using-tensorflow-and-opencv-702dd833515b

# This is a team project, team members:

Phani Tulasi - https://www.linkedin.com/in/phani-tulasi-batchu-a998651a8

Pendyala Harshita - https://github.com/PendyalaHarshita

Rutvik Guduguntla

Pragatheeswar Murugan
