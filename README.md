# Object-counter-using-computer-vision
![C_AdobeExpress](https://user-images.githubusercontent.com/68701684/222059712-cd3cf525-dc2e-41a0-ac02-2e912108160a.gif)
![C_AdobeExpress](https://user-images.githubusercontent.com/68701684/222059754-b2934c3b-ab44-4c66-ae03-ca6635853507.gif)

# Setup

* Create a new environment with the python 3.8 of anaconda
* Open that environment in the terminal by the followig command
  * ```conda activate <your env name>```
* Install all the required libraries
  * ```pip install -r requirements.txt```
* Run the project from the terminal by the following commands and paramters
  * ```python track.py --source <video path> --classes <list of the classes> --save-vid <flag to save the output> --conf-thres <detection confidence>```
* Example of the command is:
  * ```python track.py --source C:\Users\User\Downloads\C.mp4 --classes 0 24 26 28 --save-vid --conf-thres 0.3```
