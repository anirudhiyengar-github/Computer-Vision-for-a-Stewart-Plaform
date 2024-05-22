# Computer-Vision-for-a-Stewart-Plaform
I was part of a team that developed a self-stabilizing platform called a Stewart Platform. My contribution to this project was developing the computer vision that tracked the position of the object, a ping pong ball, via a camera mounted on the platform. 

The best part? This project was developed with a budget of under $300-$400, and most parts can be 3D printed! Our object detection algorithm can be loaded onto a Raspberry Pi 4 module with a Pi Camera module V2, which returns position data. The platform is balanced using servo motors that return servo angles as data, and all this data is sent to a control algorithm that returns the servo speed to actuate the position of the ball on the platform.

To determine the optimum algorimth , I compared SSD , RCNN and YOLO Object Detection algorithms, implemented transfer learning and achieved mAP( Mean average precision) detection of 95% . 

I used Python and C. 

the platform was made with an objective to be implemented in space based applications for stability , control and affordable solutions to an ever growing modern space technology needs. 

I enjoyed developing the Computer Vision subsystem for this project. 


#How to use the reposiory 
You can either train the model from scrach with your own custom dataset or you cna use the pretrainde model and use transfer learning to implement the object detecion code that will give you the inila detection. The model is trained using a Rapberry Pi camera module V2. 
