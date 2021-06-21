# An-Eye-for-Sightness
Our project “An Eye for Sightless” has been designed for helping virtually impaired person, the idea behind this project is to completely based on computer vision which help user to identify known person around him and easily able to speak through the help of headphone and also provide audio output through speakers to grab known person attention. . The designed project is extremely simple and user friendly. It provides various functionalities that may be beneficial to the user. We shall be obliged to get response about the further improvements and suggestions expected by the user and also about any technical problems faced by them. 
EYE FOR BLIND system is proposed for any kind of visual impaired persons: blind, partially
sighted, and people with progressive loss of vision. This system can help the visually impaired
individuals to travel through familiar or unfamiliar corridor by using the Kinect sensor that
mounted on the head or holding into hand. This chapter consists of four parts. The four parts can
be divided into problem statements, project introduction, previous related work, and conclusion

INTRODUCTION
 
THE EYE FOR A BLIND aims towards development in the field of AI (Artificial
Intelligence).Our main and sole purpose to develop this project to help the visually challenged
people.
This project is based on raspberry pi 3 model b+, python programming language for raspberry pi.
To detect the face of known person to user we will be using camera module,
Our project focuses on safety to detect and recognize the known person using Raspberry Pi3 B+
enabled with camera module, ArduCam module, or any suitable portable power supply to the Pi
and earphones. It also requires internet connections to operate. We have also planned to provide
basic day to day features to help the blind people using voice input through earphone’s mic and
output through earphones or any compatible headphones with mic. This system had to be made
as light-weight as possible because it is to be used on a daily basis.
Objective:
The Project aim or objectives that will be achieved after completion of project i.e. To study about
various devices and software such as Raspberry Pi, Raspberry Pi camera module, Speakers,
External USB Sound Card, Earphone with mic, and Open CV 3.0.
The specific objectives of the study were:
I. To provide safety for visually impaired people by providing authentication and letting
they know who is around them by the use of speakers and earphones.
II. To make their day-to-day life easier and convenient.
III. To recognize faces of people around them by raspberry pi camera module.
IV. Speaker will grab attention of particular known person.
V. Acknowledged about various technologies and Software such as Raspberry Pi, Python,
and Open CV 3.0.
1.2 PREVIOUS RELATED WORK
Before implementation of this project, we have come across various techniques or devices which
help visually impaired person. Through our studies we have reached where there are several
project based on person’s navigation and informing them so that we have come across this
project where we can able to detect some user known person face and letting user know who is
around him/her. This prototype will help the user to start communication with other his/her
known person. Our prototype uses ArduCam which is Raspberry Pi camera module and Power
and USB external sound card and suitable supply.
During the studies we came across Assistive technology: items designed specifically to help
people with vision loss or other disabilities, including everything from screen readers for blind
individuals or screen magnifiers for low-vision computer users, video magnifiers and other
devices for reading and writing with low vision, to braille watches and braille printers.
Further research introduced us towards various technologies and devices for virtually impaired
person which are as follows:-
1. Iris Vision
Iris Vision is an assistive technology solution approved and registered by the FDA as a
Class-1 medical device, one of the best vision enhancements, wearable low vision aids in
the market right now.
Comprised of Samsung’s VR Headset and Latest Smartphone, it is designed to facilitate
people suffering from low vision conditions, especially Macular Degeneration, and other
degenerative eye diseases like Diabetic Retinopathy, Cataracts, Albinism and so forth.
2. MyEye2
These low vision glasses for legally blind comprise of a light attachable camera mounted
on a pair of glasses. Especially designed to help people suffering from low vision read
better, it is also helpful in a handful of other activities like barcode identification, face
recognition and product identification.
3. Jordy
A wired, portable low vision solution for people suffering from low vision, Jordy helps
you with various daily activities like reading, writing and recognizing faces in many
different environments. It can be strapped around your head, offering you glasses-like
vision.
4. eSight
A pair of electronic glasses designed to help visually impaired and legally blind see.
These are battery operated, where a chord connects the battery with the device. This
means you get somewhat restricted mobility and need to keep track of the battery’s
charge.
5. NuEyes
NuEyes is a contemporary product comprising of a pair of smart electronic glasses. It
doesn’t weigh much and can be operated wirelessly through a controller that accompanies
the glasses or simply using a set of voice commands.
1.3 PROBLEM STATEMENT
Visually impaired individuals will face many difficulties and one of the common difficulties is
when they involve in self-navigating at an environment which is strange for them. In fact,
physical movement is one of the biggest challenges for them. Besides that, while they travel
around or walking at a crowded corridor, it may pose great difficulty. One of the existing
problems for visually impaired individuals to travel in a corridor is that they cannot detect either
they need to turn left or turn right when reached to the end of the corridor by using EYE FOR
BLIND device.
1.4 CONCULSION
One thing is for sure, with continued technological progression, life is going to be even better for
people with special needs. More and more processes, methods, tools and techniques will
continue improving the quality of people suffering from vision impairment, some of which have
been discussed in this write-up.
Though all of these low vision devices are designed to cater to the special needs of vision
impaired and legally blind people, all of these differ in one way or the other. And as a vision
impaired person, it’s up to you to decide your imminent needs and requirements, also
considering which one gives you the best value of money.
CHAPTER 2: LITERATURE SURVEY
2.1 INTRODUCTION
Before implementation of this project, we have come across various techniques or
devices which help visually impaired person. Through our studies we have reached
where there are several project based on person’s navigation and informing them
so that we have come across this project where we can able to detect some user
known person face and letting user know who is around him/her. This prototype
will help the user to start communication with other his/her known person. Our
prototype uses ArduCam which is Raspberry Pi camera module and Power and
USB external sound card and suitable supply.
Our project focuses on safety to Detect and Recognize people using Raspberry pi3
enabled with camera module, ArduCam module, power bank or any suitable
portable power supply to provide efficient power supply to the Pi and earphones. It
requires an Internet connection to operate. We have also planned to provide basic
day to day features to help the blind people using voice input through earphone’s
mic and output through ear phones or any compatible headphones with mic. Many
more features can be customized and added to the Rpi3 to make it more efficient
and much more user-friendly. This system had to be made as light-weight as
possible because it is to be used on a daily basis.
Our Face Recognition module works as followsFirstly the sample images of people to be recognized are given to the Python script
for checking against the real time feed.
When the user wants to recognize a person he would have to say the hot word to
awaken the virtual assistant and then say scan or recognize.
Then the face recognition script would run and check the person in the frame
against the sample images provided.
Every sample image would be associated with a name. So when the program
would find a match, the AI would tell the user the name of that person through the
Earphones. The object recognition module can only detect and recognize a handful
of objects. For this purpose the OpenCV software contains the HaarCascade files
of certain objects which are a combination of features and attributes extracted from
around a million of samples.
To detect and recognize an object, the script would check if the features and
attributes of the object match to the collective features and attributes of the
particular object’s HaarCascade file.
Problem Definition
Since every prototype has its own limitation, here are some defined problem which
may user rarely go through it.
• Power Failure: It will include in limitation where user won’t able to given
suitable amount of power supply which may lead to inefficient power supply to
Raspberry Pi.
• Database failure: It may be a rare case where there will be inadequate image
detection and storing problem which will lead to miscommunicate with user.
• ArduCam failure: This problem may lead to Capture image of person which is to
be stored in particular database.
• Inaudible sound: If the person detected may won’t able to hear the following
output voice from the speaker it may lead to miscommunication between them. 
2.2 LITERATURE OF DOMAIN USED
Computer vision is an interdisciplinary scientific field that deals with how
computers can gain high-level understanding from digital images or videos. From
the perspective of engineering, it seeks to understand and automate tasks that the
human visual system can do.
Computer vision tasks include methods for acquiring, processing, analysing and
understanding digital images, and extraction of high-dimensional data from the real
world in order to produce numerical or symbolic information, e.g. in the forms of
decisions. Understanding in this context means the transformation of visual images
(the input of the retina) into descriptions of the world that make sense to thought
processes and can elicit appropriate action. This image understanding can be seen
as the disentangling of symbolic information from image data using models
constructed with the aid of geometry, physics, statistics, and learning theory.
The scientific discipline of computer vision is concerned with the theory behind
artificial systems that extract information from images. The image data can take
many forms, such as video sequences, views from multiple cameras, multidimensional data from a 3D scanner or medical scanning device. The technological
discipline of computer vision seeks to apply its theories and models to the
construction of computer vision systems.
Sub-domains of computer vision include scene reconstruction, event detection,
video tracking, object recognition, 3D pose estimation, learning, indexing, motion
estimation, visual serving, 3D scene modelling, and image restoration .
The classical problem in computer vision, image processing, and machine vision is
that of determining whether or not the image data contains some specific object,
feature, or activity. Different varieties of the recognition problem are described in
the literature.
Object recognition (also called object classification) – one or several prespecified or learned objects or object classes can be recognized, usually together
with their 2D positions in the image or 3D poses in the scene. Blip par, Google
Goggles and Like That provide stand-alone programs that illustrate this
functionality.
Identification – an individual instance of an object is recognized. Examples
include identification of a specific person's face or fingerprint, identification of
handwritten digits, or identification of a specific vehicle.
Detection – the image data are scanned for a specific condition. Examples include
detection of possible abnormal cells or tissues in medical images or detection of a
vehicle in an automatic road toll system. Detection based on relatively simple and
fast computations is sometimes used for finding smaller regions of interesting
image data which can be further analysed by more computationally demanding
techniques to produce a correct interpretation.
The organization of a computer vision system is highly application-dependent.
Some systems are stand-alone applications that solve a specific measurement or
detection problem, while others constitute a sub-system of a larger design which,
for example, also contains sub-systems for control of mechanical actuators,
planning, information databases, man-machine interfaces, etc. The specific
implementation of a computer vision system also depends on whether its
functionality is pre-specified or if some part of it can be learned or modified during
operation. Many functions are unique to the application. There are, however,
typical functions that are found in many computer vision systems.
Image acquisition – A digital image is produced by one or several image sensors,
which, besides various types of light-sensitive cameras, include range sensors,
tomography devices, radar, ultra-sonic cameras, etc. Depending on the type of
sensor, the resulting image data is an ordinary 2D image, a 3D volume, or an
image sequence. The pixel values typically correspond to light intensity in one or
several spectral bands (gray images or colour images), but can also be related to
various physical measures, such as depth, absorption or reflectance of sonic or
electromagnetic waves, or nuclear magnetic resonance.[24]
Pre-processing – Before a computer vision method can be applied to image data in
order to extract some specific piece of information, it is usually necessary to
process the data in order to assure that it satisfies certain assumptions implied by
the method. Examples are:
 Re-sampling to assure that the image coordinate system is correct.
 Noise reduction to assure that sensor noise does not introduce false
information.
 Contrast enhancement to assure that relevant information can be detected.
 Scale space representation to enhance image structures at locally appropriate
scales.
Feature extraction – Image features at various levels of complexity are extracted
from the image data. Typical examples of such features are:
 Lines, edges and ridges.
 Localized interest points such as corners, blobs or points.
Detection/segmentation – At some point in the processing a decision is made
about which image points or regions of the image are relevant for further
processing. Examples are:
 Selection of a specific set of interest points.
 Segmentation of one or multiple image regions that contain a specific object
of interest.
High-level processing – At this step the input is typically a small set of data, for
example a set of points or an image region which is assumed to contain a specific
object. The remaining processing deals with, for example:
 Verification that the data satisfy model-based and application-specific
assumptions.
 Estimation of application-specific parameters, such as object pose or object
size.
 Image recognition – classifying a detected object into different categories.
 Image registration – comparing and combining two different views of the
same object.
Decision making– Making the final decision required for the application, for
example:
 Pass/fail on automatic inspection applications.
 Match/no-match in recognition applications.
 Flag for further human review in medical, military, security and recognition
applications.
2.3 COMPARISON WITH EXISTING SYSTEM
Before implementation of this project, we have come across various techniques or
devices which help visually impaired person. Through our studies we have
reached where there are several project based on person’s navigation and
informing them so that we have come across this project where we can able to
detect some user known person face and letting user know who is around him/her.
This prototype will help the user to start communication with other his/her known
person. Our prototype uses ArduCam which is Raspberry Pi camera module and
Power and USB external sound card and suitable supply. Our project focuses on
safety to Detect and Recognize people using Raspberry pi3 enabled with
camera module, ArduCam module, power bank or any suitable portable
power supply to provide efficient power supply to the Pi and earphones. It requires
an Internet connection to operate. We have also planned to provide basic day to
day features to help the blind people using voice input through earphone’s mic and
output through ear phones or any compatible headphones with mic. Many more
features can be customized and added to the Rpi3 to make it more efficient and
much more user-friendly. This system had to be made as light-weight as possible
because it is to be used on a daily basis.
2.4 FEATURES OF PROGRAMMING LANGUAGE USED
Features in Python
There are many features in Python, some of which are discussed below –
1. Easy to code:
Python is high level programming language. Python is very easy to learn language
as compared to other language like c, c#, java script, java etc. It is very easy to
code in python language and anybody can learn python basic in few hours or days.
It is also developer-friendly language.
2. Free and Open Source:
Python language is freely available at official website and you can download it
from the given download link below click on the Download Python keyword.
Download Python
Since, it is open-source; this means that source code is also available to the public.
So you can download it as, use it as well as share it.
3. Object-Oriented Language:
One of the key features of python is Object-Oriented programming. Python
supports object oriented language and concepts of classes, objects encapsulation
etc.
4. GUI Programming Support:
Graphical Users interfaces can be made using a module such as PyQt5, PyQt4,
wxPython or Tk in python.
PyQt5 is the most popular option for creating graphical apps with Python.
5. High-Level Language:
Python is a high-level language. When we write programs in python, we do not
need to remember the system architecture, nor do we need to manage the memory.
6. Extensible feature:
Python is an Extensible language. We can write some python code into c or c++
language and also we can compile that code in c/c++ language.
7. Python is Portable language:
Python language is also a portable language. For example, if we have python code
for windows and if we want to run this code on other platform such as Linux, Unix
and Mac then we do not need to change it, we can run this code on any platform.
8. Python is integrated language:
Python is also an integrated language because we can easily integrated python with
other language like c, c++ etc.
9. Interpreted Language:
Python is an Interpreted Language. Because python code is executed line by line at
a time. like other language c, c++, java etc. there is no need to compile python
code this makes it easier to debug our code. The source code of python is
converted into an immediate form called bytecode.
10. Large Standard Library
Python has a large standard library which provides rich set of module and
functions so you do not have to write your own code for every single thing. There
are many libraries present in python for such as regular expressions, unit-testing,
web browsers etc.
11. Dynamically Typed Language:
Python is dynamically-typed language. That means the type (for example- int,
double, long etc.) for a variable is decided at run time not in advance. Because of
this feature we don’t need to specify the type of variable.


: SYSTEM IMPLEMENTATION

The implementation of image processing in today's world has done a lot in various field.
Visually impaired or people with low vision always face difficulties recognizing a person
while social interactions and regular activities. The proposed system is designed for blind
people to reduce the complexity of blind people in regular activities and engage them. This
paper represents a Raspberry Pi embedded system based person’s face recognition system
using local binary pattern algorithm of image processing aiming visually impaired people.
This device detects and recognizes human faces of pre-made datasets, fetches information
from MySQL database on match and spells through a microphone applying text to speech
method. In the experimental case, the system gives 96% accuracy recognizing single person
and 92% accuracy in the case of recognizing multiple people and in complex background.
According to estimation there are 253 million individuals live with vision disability: 36
million are blind and 217 million have direct to extreme vision impairment. Among blind and
have moderate or severe vision impairment, 81% people are aged 50 years and above.
Sometimes loss of vision is related with a misfortune of freedom. Blind and visually
impaired individuals often face many challenging situations in their day to day life.
Individuals who are completely blind or have disabled vision as a rule have a troublesome
time navigating outside the spaces that they're usual to. They had to depend on the external
support system which can maintain by humans, guided dogs, or special electronic gadgets.
Another major problem they had to face is identifying a person in a variety of social
1interactions.
This project portrays a face detection and recognition system based on Raspberry Pi-3 that's
able of processing image or video delivering a voice output. Using face recognition
technology, the device identify classmates, relatives and colleagues by giving some identity
persons who previously custom-made dataset, and on match information are fetched from
MySQL database. This project proposes a design and implementation of facial recognition
system for visually impaired using image processing for an assistive service provided to the
visually impaired child using K neighbouring algorithm and machine learning.
The system uses instantaneous video feed as input and produces output in audio form giving
a description of the identified face if it is available in the directory. The directory contains
faces of acquaintance of the person. This can include people they meet on a daily basis. The
development of new technologies and concepts led to various healthcare services. These new
technologies used in advancement of hospital maintenance and help in monitoring patients on 
a daily bases. By monitoring the patients on a daily bases we can detect any distress in
patients’ health and treat it on time.

Module Description :
Our proposed system is mainly designed to overcome the problems that a visually challenged
person will face when they move in public places. This system came up with an idea of
detecting the faces of people behind them. The input for this system is a face of a person who
is behind the visually challenged person and output will be an audio which tells the name of
the person in front of them. First the input is taken as a video stream and then the image is
captured from that video which is the live feed
Our proposed System is based on Raspberry Pi 3 B, which has Raspbian OS as operating and
used as an portable computer. Raspberry Pi 3 has a quad-core 1.2GHz 64-bit ARM
processor, 1 GB RAM, onboard Wi-Fi, Bluetooth, 4 USB ports, 40 GPIO pins, Ethernet port
and micro SD space [8]. To get real time videos, Raspberry Pi Camera Module v2 which has
a 8 megapixel Sony IMX219 image sensor, is used. This camera module is competent of
taking 640 x 480 pixels videos. A 3.5mm ported earphone is connected with Raspberry Pi to
get voice output.
We used OpenCV 3.4 version with python programming language in Raspberry Pi for image
processing and pyttsx library of python for converting text to speech that is gained from
MySQL database. MySQL contains person’s information of name, address and some
previous records. Each person has unique ID number in database. On recognition of person,
based on matched ID number, information will be faced from database.
The Camera which is connected to the Raspberry Pi is switched by giving a command to the
ARM microcontroller. Then the Webcam captures the image of the object placed in front.
After capturing the image of the object the image undergoes Optical Character Recognition
Technology. The entire project is based on the Raspberry Pi. The scanned image of printed
text or symbols is converted into text or information the can be understood or edited using a
computer program Using OCR technology. In this project for implementing OCR
technology, we are using TESSERACT library. After the processing of the image, the
obtained text is converted into speech using an e-speak engine which speaks out the text
through a speaker or earphone that can be connected to the audio jack of the Raspberry Pi.
Effective machine learning training set for the text detection is an Adaboost model. The
training set comprises of positive and negative samples where we can further define positive
sample consisting of text image while negative sample contains images other than the text
present in the input image. Haar Cascade gets input image which analyses text which is
inside the ROI and matches the input text with predefined text in the training text.The one to 
which the range of similarity is high is then confirmed to be the character and the
corresponding audio is produced.

Conclusion :
The proposed system helps blind persons to read printed text on products which appears in
front of the camera through the earphone. In addition, it also helps them to detect the obstacle
to prevent them from falling. It can build self-confidence and can give a better life to the
blind users as they become self-dependent for day to day requirements. We have projected a
style on face recognition supported raspberry pi that is especially designed aiming visually
impaired people. The system is develop in a way so that it can recognize faces to classify
people, then fetch matched people’s information stored in dataset and spell through a voice
out using earphone or headset. Our future work can specialize in detective as recognizing a
lot of sorts of indoor objects and icons on assemblage additionally for indoor method finding
aid to help blind individuals travel severally. We are going to additionally study the many
human interface problems together with additive output and special change of object
location, orientation, and distance. With time period updates, blind users are able to higher
use special memory to grasp the encompassing atmosphere, obstacles and signs. The
projected system achieved each high accuracy and quick response. Additionally, as the
equipment’s are cheap in price, lightweight weight and quick software package processor, it
can be good way to remove obstacle between normal and visually impaired people. Facial
recognition system concludes that the system will help the visually challenged in several
purposes. It uses Raspberry Pi kit to execute this process. The Raspberry Pi kit is a small
board which can be used with any operating system like Linux FreeBSD, NetBSD, RISC OS.
It will improve the cognition of the visually impaired. This proposed system does not use any
prior knowledge about the position of the people. The experimental evaluation is performed
on a large dataset. The system will take input from the camera and gets the edges of the
images. The accuracy of the face detection and recognition of the system has 92% which is
comparatively perfect then the previous detection techniques
