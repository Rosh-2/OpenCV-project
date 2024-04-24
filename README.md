# openCV-project - Sunspot Recognition
1. Import Libraries: Begin by importing the necessary libraries, including OpenCV and NumPy.
<br>
2. Load Image: Load the target image in grayscale mode. Grayscale conversion simplifies processing while retaining essential details.
<br>
3. Adaptive Thresholding: Apply adaptive thresholding to convert the grayscale image into a binary image. This process effectively highlights sunspots against the background.
<br>
4. Contour Detection: Utilize contour detection to identify distinct shapes within the binary image. Sunspots, being prominent features, typically form contours.
<br>
5. Contour Filtering: Filter the detected contours based on their area to isolate sunspots from other elements in the image. This step helps remove noise and irrelevant shapes.
<br>
6. Sunspot Visualization: Draw bounding boxes or circles around the identified sunspots to visually mark their locations and sizes. This visualization aids in further analysis or presentation of the results.




