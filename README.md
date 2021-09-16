# Smart-crosswalk
Final project in the Department of Electrical Engineering at the Holon Institute of Technology.
This project is based on my original idea on the subject of road accidents computer vision and deep learning.
-------------------------------------------------------------------------------------------------------------

 Steps for project execution

 1) People are sometimes run over in a crosswalk.
   Sometimes there are hit and run accidents in which the victim is left in a crosswalk sometimes without the possibility of calling for help.

 2) Suggestion to try to help the problem.
  Placing a device that detects live when people are run over in a crosswalk and the device calls for help via SMS or automatic call.


 3) Project structure

   * Preparation of a database
   Photographing a vehicle that overturns a person at a crosswalk, I used my vehicle
   And a random crosswalk I found in one of the cities.

   * Labeling the database and dividing it into categories.

   * Entering the database into the YOLOV5-S object identification network

   * Transfer the grid with the weights to the Invida Jetson Nano controller.
