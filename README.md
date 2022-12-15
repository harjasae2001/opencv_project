Explanation

AIM: To identify the centre point of gate in the image provided for the bot to pass through it.


Method:
In this image I have first applied thresholding to identify the orange gates using a trackbar and then wrote those values. Then I have converted the coloured image (RGB) into grayscale image. Then I have applied gaussian blur for smooth detection of edges for the detection of gates. Then I have used the canny edge detection technique to identify the edges of the gate pillars. Then I have drawn the contours around the edges of the gates detected by the canny edge detector. After that I have found the centre of the rectangle formed by the contours of the edges of the gate. This helps in aligning the bot in a particular direction so that it always passes through the gate. This is how OPENCV helps in finding and aligning the bot to pass through the gate.
