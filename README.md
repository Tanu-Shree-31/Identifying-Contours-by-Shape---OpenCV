# Identifying-Contours-by-Shape---OpenCV

## Approach
- Import module
- Import image
- Convert it to grayscale image
- Apply thresholding on image and then find out contours.
- Run a loop in the range of contours and iterate through it.
- In this loop draw a outline of shapes (Using drawContours() ) and find out center point of shape.
- Classify the detected shape on the basis of a number of contour points it has and put the detected shape name at the center point of shape.


## Input Image

![inputimg](https://user-images.githubusercontent.com/69342524/155849771-8b699fe0-5709-4a35-a1f7-c8962fc78b32.PNG)

## Output Image

![outputimg](https://user-images.githubusercontent.com/69342524/155849851-2a0ecc27-47e5-40f6-a470-a688dcc047d6.PNG)

