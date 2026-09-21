# CLA-4

![ image loaded successfully.
](output.png)

## Aim
To perform the given Computer Vision experiment and display the output using Python.

## Description
This project implements the Computer Vision experiment using Python.
The program processes the input image and produces the required output.

## Technologies Used
- Python
- OpenCV
- NumPy
- Matplotlib

## Code

```python
import cv2
import matplotlib.pyplot as plt

img = cv2.imread("input.jpg")

img_rgb = cv2.cvtColor(img, cv2.COLOR_BGR2RGB)

plt.imshow(img_rgb)
plt.axis("off")
plt.show()
