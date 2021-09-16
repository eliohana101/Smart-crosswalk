# Smart-Crosswalk

Electrical Engineering final year project.
The project is based on my original idea in the field of road safety, and aims to identify crosswalk accidents by using computer vision and deep learning tools.
The project was performed at Holon Institute of Technology, 2021.

---------------------------------------------------------------------------------------------------------------------------------

Problem description and motivation to the project:
In Israel, almost every day pedestrians are hit by cars when walking on crosswalks. In case of a 'hit and run' the victim is left on the crosswalk,  without the possibility of calling for help.

The suggested solution:
Placing a camera that detects real-time pedestrian accidents on the crosswalk and calls for help via SMS or automatic call.
The detection is done by using deep learning tools.


Project Structure:
* Creating a database of pedestrian crosswalk accidents images
* Labeling the images and dividing the database to categories
* Loading the database into YOLO-V5 object detection network
* Transferring the grid and the weights to the Nvidia Jetson Nano controller
* Connecting a camera which transfers real-time photos and video to the Jetson Nano controller
* The network is able to detect an accident in the real-time data

