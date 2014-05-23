thesis-test-images
==================

Contains the 32 sets of test images used for testing our four hand recognition algorithms. 

Each algorithm was tested with 8 sets of images: 1 for each gesture and 1 set of negatives:

Global Histogram Matching (Open, Fist, Thumb, Two, Three, Four, Duck, and Negatives)

Region of Interest Histogram Matching (Open, Fist, Thumb, Two, Three, Four, Duck, and Negatives)

Global Contour Matching (Open, Fist, Thumb, Two, Three, Four, Duck, and Negatives)

Square Bounded Contour Matching (Open, Fist, Thumb, Two, Three, Four, Duck, and Negatives)


Each set consists of about 25-35 images. Each gesture's folder contains its set of test images and 
a text file that contains, for each test image, an indication of which gesture the algorithm guessed
and what the similarity value between the chosen gesture in the training set and the test image was.
