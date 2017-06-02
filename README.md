A small step using TensorFlow on Traffic Sign Detection and Classification


Currently only stop signs and pedestrian crossing signs are detected. Example detection images are below.

## Dependencies of this program
* Python 3.5+ or Anaconda
* TensorFlow v0.12.0 or 0.12.1( i used 0.12.1)
* Pickle
* OpenCV-Python
* Matplotlib

To run the program
* `python inference.py -m demo`


Intial issuses i faced (And my solutions how i solved it)

stated the errors that i faced step by step while running this program 
*  Scikt-lean error

so install scikt-learn (pip-install-u scikt-learn) or (conda install scikt-learn)

* Cv2 error
So install Cv2 (conda install cv2) it will again pop up error so "IMPORTANT NOTE: Install Opencv" before intalling Cv2

* Matplot.lib error
Intall matplot library (conda install matplot.lib)

* moviepy error(major error consumes time to fix)

Initally (install moviepy) by conda "pip install -i https://pypi.anaconda.org/pypi/simple moviepy "
 
 then
 
 install Imageio,install Pickle(hope Moviepy comes under it..but not sure..may be optional)

 then
Download "FFMPEG"

Extract the zip file

copy the files and go to program files or location or drive where you had installed

open library->Sitepages->moviepy and paste FFMPEG  





Now to use the pre-trained model:
[Download the pre-trained model](https://drive.google.com/open?id=0BzaCOTL9zhUlekM3NWU1bmNqeVk)

and save the downloaded model in our Root.

now run the program using the command  

* `python inference.py -m demo`

  * This will take the images from sample_images, annotate them, and display them on screen

