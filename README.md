# FaceDetection & recognition using CNN
Using openCV libraby and Python language on Anaconda Platform 
Face detection using Haar cascade Training detector 
with AT&T and Yalefaces DB
Recognition with Eigen faces LDA approche. 
With functionalities like add new face not present in database while testing on new file

save this project at like C:\demo
Now you have C:\demo\pyfacesdemo which contains a __main__.py and a folder pyfaces(which is a python package)
from command line
cd to C:\demo 
run python pyfacesdemo imgname dirname numofeigenfaces threshold


where
imgname-image to be matched
dirname-directory where images of same extension reside
numofeigenfaces-how many eigenfaces need to be used in matching(shd be less than the number of images (of same extension)in folder represented by dirname.
threshold-a threshold value that should be the upper limit of euclidean distance between images

example:
to compare F:\myimages\probes\amy3.png against png images in the folder 'F:\myimages\gallery' using 6 eigenfaces and with distance below 3

python pyfacesdemo F:\myimages\probes\amy3.png F:\myimages\gallery 6 3



Tested on Windows7 + python 2.7
and Ubuntu Lucid + python 2.6.5
using 183 images from jaffe database

