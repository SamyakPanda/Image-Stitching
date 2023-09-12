# RANSAC Line Fitting and Image Stitching Project

This project comprises two main parts: RANSAC Line Fitting and Image Stitching. These two computer vision tasks are implemented separately, providing insights into different aspects of image processing and feature detection.

## Part 1: RANSAC Line Fitting

### Overview

Part 1 of the project focuses on RANSAC (Random Sample Consensus) line fitting, a fundamental computer vision technique used to identify a line within an image. This technique is robust and can handle noisy data with outliers.

### Instructions

1. **Install the Required Libraries**

   Ensure you have the necessary Python libraries installed by running:

pip install opencv-python-headless==4.4.0.44
pip install numpy
pip install matplotlib
pip install imageio


2. **Prepare Your Image**

- Place the image you want to analyze in the same directory as the script.
- Ensure that the image is named "line_ransac.png," or update the script to specify the correct filename.

3. **Run the RANSAC Line Fitting Code**

- Open the Python script for RANSAC line fitting (`ransac_line_fitting.py`).
- Execute the script.

4. **Output**

- The script will display the input image with keypoints and the fitted line.
- It will also extrapolate the line to the edges of the image and display the extrapolated line.

## Part 2: Image Stitching

### Overview

Part 2 of the project deals with image stitching, a computer vision technique used to combine multiple overlapping images into a single panoramic image. This part demonstrates the basics of image stitching using the OpenCV library in Python.

### Instructions

1. **Install the Required Libraries**

Make sure you have the required Python libraries installed by running:

pip install opencv-contrib-python==4.4.0.44
pip install numpy
pip install matplotlib
pip install imutils


2. **Prepare Your Images**

- Create a directory and place the images you want to stitch inside it.

3. **Run the Image Stitching Code**

- Open the Python script for image stitching (`image_stitching.py`).
- Edit the script to specify the directory path containing your images.
- Execute the script.

4. **Follow the Prompts**

- The script will prompt you to enter the number of images you want to concatenate.
- Then, it will ask you to enter the filenames of the images in the order you want them concatenated.
- The script will display the input images, the intermediate matched points visualization, and the final stitched panorama.

5. **Output**

- The final stitched panorama image will be saved as "Panorama_image.jpg" in the same directory as the script.

## Conclusion

This project provides practical examples of two essential computer vision techniques: RANSAC line fitting and image stitching. By following the provided instructions, you can apply these techniques to analyze and process images in various applications.

Feel free to modify and extend the code to meet your specific project requirements or integrate these components into a larger computer vision project.
