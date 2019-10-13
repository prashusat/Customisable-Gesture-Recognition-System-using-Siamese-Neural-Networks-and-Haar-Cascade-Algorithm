# Customizable-Gesture-Recognition-System-using-Siamese-Neural-Networks-and-Haar-Cascade-Algorithm

There has been a lot of work in the field of gesture
recognition in the last few decades but all of them compel
the user to use a set of gestures that are predefined by the
maker. This turns out to be a huge pitfall for motor impaired
people as they are constricted in terms of movement and
may not be able to accomplish gestures predefined by the
system.

We have built a customizable dynamic hand
gesture recognition which will be useful for them. When the
user operates the system for the first time, he has to record 3
gestures for controlling 3 different applications.

Our paper's link can be found here:

https://ieeexplore.ieee.org/document/8834600/authors#authors

We are making the code open source so that further contributions can be made to it.

Instructions to run the code:

Gesturefinal.ipynb contains all the code necessary to test the system.

3 empty files need to be created in the same directory as the ipynb file.These files are used to store the gestures which have been taught to the sytem by the user the first time he uses it.

Haar Cascade algorithm has been used for detection and tracking of hand.Than training file for the is contained in hand4.xml.

A lot of help was also taken from Sorenboumas blog and github repository for one shot learning.The link is posted below.

https://github.com/sorenbouma/keras-oneshot


<b>The system has been built to perform 3 applications but the applications can be modified:</b>
<br/><br/>

1)Calling a phone number.<br/>
2)Messaging a phone number.<br/>
3)Switching on and off a light using Arduino.
