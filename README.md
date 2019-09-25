# Face Recognition using Haar-Cascade Classifier, OpenCV, and Python
Simple Face Recognition algorithm using Python and OpenCV

# Blog
http://utpcc.blogspot.com/2017/05/facial-recognition-machine-learning.html

## Requirement
- Python 3.6
- `pip install opencv-contrib-python`

## Outline
This project consist of 3 parts, which are:
1. Creating datasets (face_datasets.py)
2. Train the model (training.py)
3. Face Recognition (face_recognition.py)

## How to run ?
1. Make sure have executable permission. (chmod 777 .)
2. `pip install -r requirements.txt`
3. Please make sure that you have folders called 'datasets' and 'trainer' in the same directory. (Optional, I have put the code so it will create if it's not exist.)
4. Run in the command line the face_datasets.py for taking your face image as datasets. Don't forget to set each person's face to unique ID (You need to edit the code everytime, or maybe just change the id variable to raw_input[OPTIONAL])
5. If you have more face to be include, change the ID and run the program again
6. Train your datasets by running training.py
7. Lastly, run face_recognition.py

## Reading materials
1. Object Detection using Haar-like features, link: http://www.cs.utexas.edu/~grauman/courses/spring2008/slides/Faces_demo.pdf
2. Face Detection using Haar Cascades, link: http://docs.opencv.org/trunk/d7/d8b/tutorial_py_face_detection.html
3. Haar-like Features, link: https://en.wikipedia.org/wiki/Haar-like_features
4. Object Detection using Haar-cascades Classifier, link: http://ds.cs.ut.ee/Members/artjom85/2014dss-course-media/Object%20detection%20using%20Haar-final.pdf
5. OpenCV Documentation, link: http://docs.opencv.org/3.0-beta/doc/py_tutorials/py_tutorials.html

## Tips
- If you don't understand what the code do, I already comments it line by line.
- You also can Google the syntax, and read the explanation from OpenCV Documentation.

## Credit to:
#### Anirban from TheCodacus. Link: http://thecodacus.com/
#### All rights reserved to the respective owner
