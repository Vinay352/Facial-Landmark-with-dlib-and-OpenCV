# Facial-Landmark-with-dlib-and-OpenCV
This python program uses dlib, OpenCV, face_recognition and imutils libraries to mark facial landmarks. The arguments to the program are provided via command line where '-p' or '--shapePredictor' asks the user to input the path to the shape predictor file and the second argument '-i' or '--image' asks the user to input the path to the image whose facial landmarks you want to detect. This program first detects the faces in the image and then mark its landmarks.

## NOTE:-
 - If in any image the program output does not detect any or some faces in the image, all you need to do is increase the width of the image in Line 19 of this program.
 - Refer http://www.nada.kth.se/~sullivan/Papers/Kazemi_cvpr14.pdf for better understanding.
 - <b>(IMP)</b> If you run into an error like "RuntimeError: Unable to open shape_predictor_68_face_landmarks.dat", btw this is the file whose path you have to enter as your first argument for the program, then kindly download the 'face_recognition' module via pip, go to the directory where this module is installed, look for 'face_recognition_models', open it and go to 'models', there you will find four .data files. Enter the path of any one of the four .dat files as the first input to the program and the error would be resolved.
 
 
 
 
