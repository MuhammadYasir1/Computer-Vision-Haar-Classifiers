# Computer-Vision-Using-Haar-Classifiers
### Face Detection on Newspaper Articles using Haar Cascade Classifiers

* This Project takes in a ZIP file of images and process them using buitin python _Zip_ library. A ZIP file takes several different files and compresses them, thus saving space, into one single file. The files in the ZIP file we provide are newspaper images and the Project provides a  python code which allows one to search through the images looking for the occurrences of keywords and faces. E.g. if you search for "pizza" it will return a contact sheet of all of the faces which were located on the newspaper page which mentions "pizza". 

* By Using _OpenCV_ for face detection, _PyTesseract_ for OCR and _Pillow_ for Contact-Sheet and image manipulation, the project returns the output showing a list of all the faces in a particular zip file (containing newspaper articles)

* Each page of the newspapers is saved as a single PNG image in a file called images.zip. These newspapers are in english, and contain a variety of stories, advertisements and images. 

##### Note: This file is fairly large (~200 MB) and may take some time to work with, I would encourage you to use small_img.zip for testing.The large file took me 15 minutes to run.
