# VIRTUAL_Painting_Application

ABSTRACT:
Writing in air has been one of the most
fascinating and challenging research areas in field of
image processing and pattern recognition in the recent
years.
It contributes immensely to the advancement of an
automation process and can improve the interface
between man and machine in numerous applications
By using this application we can easily draw objects,shapes
by using different colours and different tools without using
any mouse,keypad, we can draw it by using contact less way.
In this application, it will display a screen and a canvas board,
As we will keep moving our fingers over the screen ,and show
the particular fingers which are given some function, the
application will detect those finger movements and perform
the specific task which is assigned to it.

INTRODUCTION:
In the era of digital world, traditional art of writing is
being replaced by digital art. Digital art refers to forms of
expression and transmission of art form with digital
form. Relying on modern science and technology is the
distinctive characteristics of the digital manifestation.
Traditional art refers to the art form which is created
before the digital art.
The traditional way includes pen and
paper, chalk and board method of writing and drawing.
The essential aim of digital art is of building hand gesture
recognition system to write digitally.
Digital art includes many ways
of writing like by using keyboard, touch-screen surface,
digital pen, stylus, using electronic hand gloves, etc. But
in this system, we are using hand gesture recognition
with the use of machine learning algorithm by using
python programming, which creates natural interaction
between man and machine.

SYSTEM METHODOLOGY and IMPLEMENTATION:
We will use computer vision to trace the path of the
finger.
Here,we are going to track our hand movements and we will
collect the information of the landmarks which are
moving,and by keeping the record of the previously moved
point and currently moving point we can draw lines between
them and thus we can create a figure.
In the handTracking module, we are detecting the landmarks
of our finger tips,there are total 20 landmarks of our hand,as
we will keep moving our hand it will detect the position of
the landmarks in the x ,y and z coordinates.
For detection we are using webcam .
After the detection of the landmarks, we will detect the
movement of the specific fingers, we will detect which finger
is displayed on the screen, as each finger has different id so
according to that we can detect which landmark is displayed.
That’s how we can count the number of fingers.
We will use this finger counting in our application.if two
fingers that is pinky finger and middle finger are displayed
then the selection mode will be turned on,that is in this
mode we can select different drawing tools displayed in the
tool selection bar,
And when one finger that is pinky finger is displayed then the
drawing mode will be turned on, in this we will be able to
draw the objects,
Here the landmarklist in the handtracking module will keep a
track of the path of the landmarks moved,
We will store the previously moved landmark and current
landmark and later we will create a connection between
those two landmarks and will draw a line between then,this
is how we can create continuous lines for the moving finger
tip.
For displaying the painting we have used canvas board which
is made with the help of numpy,
The tool selction bar is made on the canva app and 4
different images are created,so as to show the toggling effect
for the different tools.
We firstly are displaying the images on a different canvas
board which will be black in color,lateron if we want to
display those creatures on the screen itself then we will
invert the colors on the canvasboard into black and white
and then we will merge the screen and canvas board and the
again invert the colors to their original form.

DEMO FOR THIS PROJECT:

https://drive.google.com/file/d/1tlMushWByhvn280taGy0Rzwvjc-FFoBZ/view?usp=sharing

REPORT :

https://drive.google.com/file/d/1vcFikeuJXNZG0jfQvgNII1pJ59dDu8dO/view?usp=sharing
