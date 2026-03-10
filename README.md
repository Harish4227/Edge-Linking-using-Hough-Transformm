# Edge-Linking-using-Hough-Transformm
## Name:Harish.D
## ref no: 212224220034
## Aim:
To write a Python program to detect the lines using Hough Transform.

## Software Required:
Anaconda - Python 3.7

## Algorithm:
### Step1:

Import all the necessary modules for the program.
### Step2:

Load a image using imread() from cv2 module.
### Step3:

Convert the image to grayscale.
### Step4:

Using Canny operator from cv2,detect the edges of the image.
### Step5:

Using the HoughLinesP(),detect line co-ordinates for every points in the images.Using For loop,draw the lines on the found co-ordinates.Display the image.
## Output

### Input image and grayscale image
<img width="821" height="590" alt="image" src="https://github.com/user-attachments/assets/8f1868a3-b56b-4bbb-a8de-548e9ac2a91b" />

### Canny Edge detector output
<img width="810" height="665" alt="image" src="https://github.com/user-attachments/assets/5587caca-b000-4034-bd2f-9f3d6bc4a2bb" />

### Display the result of Hough transform
<img width="1094" height="738" alt="image" src="https://github.com/user-attachments/assets/07041113-eb95-44a4-86f6-b7af9a1dff26" />

