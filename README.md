# Automatic-License-Number-Plate-Recognition-

This project aims to recognize license number plates. In order to detect license number plates, we will use OpenCV to identify number plates and python pytesseract to extract characters and digits from the number plates.
OpenCV is an open-source machine learning library and provides a common infrastructure for computer vision. Whereas Pytesseract is a Tesseract-OCR Engine to read image types and extract the information present in the image.

In this python project, to identify the number plate in the input image, we will use following features of openCV:

Gaussian Blur: Here we use a Gaussian kernel to smoothen the image. This technique is highly effective to remove Gaussian noise. OpenCV provides a cv2.GaussianBlur() function for this task.
Sobel: Here we calculate the derivatives from the image. This feature is important for many computer vision tasks. Using derivatives we calculate the gradients, and a high change in gradient indicates a major change in the image. OpenCV provides a cv2.Sobel() function to calculate Sobel operators.
