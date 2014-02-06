281_CE2
=======

##Decoder Analysis
What is a decoder? The decoder that appears in this project is basically a binary to decimal number converter. Whenever the encoder is "turned on" (EN is 1) the converter will take the input and output a 1 in the culumn which represents that binary number in decimal.

#####Truth Table

|  I1 I0 EN |  Y0 |Y1| Y2| Y3  | 
|:--:|:--: |:--:|:--:|:--:|
| 000  |  0|0|0|0  |  
| 001  |  1|0|0|0  |  
| 100  |  0|0|0|0  | 
| 101  |  0|0|1|0  |  
| 010  |  0|0|0|0  | 
| 011  |  0|1|0|0  | 
| 110  |  0|0|0|0  |
| 111  |  0|0|0|1  |

#####Structural Test Bench Simulation Capture
![alt tag](https://raw.github.com/EricWardner/281_CE2/master/CE2testcapture.PNG)

#####Behavioral Test Bench Simulation Capture
![alt tag](https://raw.github.com/EricWardner/281_CE2/master/BehavioralTestCapture.PNG)

#####Functionality Analysis
It is clear by viewing the different simulation captures that both the Structural code and behavioral code result with the same outputs, this is due to the fact the both sets of code have the same functionality just a different method of reaching that functionality. In the long run it would be easier to use the structural design because it is easier to implement a large amount of different components but in this case where only a few components were used the behavioral design was quicker to create.
