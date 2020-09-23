# Introductions
# Image Processing
עיבוד תמונה הוא תחום במדעי המחשב, מתמטיקה שימושית, הנדסת חשמל ואלקטרוניקה העוסק בעיבוד של תמונות ובמניפולציות שונות עליה. לרוב העיבוד נעשה בתחום הדיגיטלי לאחר שהתמונה כבר נדגמה
https://en.wikipedia.org/wiki/Digital_image_processing

## Links
https://setosa.io/ev/image-kernels/
Image Kernels Explained Visually

https://ziyizhu.me/2020/03/17/image-processing-visualization/

https://pythonexamples.org/python-opencv-image-filter-convolution-cv2-filter2d/

# Open CV
OpenCV (ראשי תיבות של Open Source Computer Vision) היא חבילת תוכנה (המיועדת למתכנתים) שנועדה לעזור לפתח יישומים של ראייה ממוחשבת. OpenCV פתוחה לשימוש מחקרי ומסחרי כאחד (תחת רישיון BSD). הספרייה תואמת android,‏ windows,‏ Linux mac OS. הספרייה מוכוונת בעיקר עבור יישומי ראייה ממוחשבת בזמן אמת.

https://opencv.org

## Selected Functions
```python
import cv2

imgOBJ = cv2.imread('filename.jpg')

>>> print( img.shape )
(342, 548, 3)

>>> print( img.size )
562248
```
https://docs.opencv.org/master/d3/df2/tutorial_py_basic_ops.html

in google colab instead of using opencv image show function we use pyplot
```python
import matplotlib.pyplot as plt
plt.imshow(img) 
plt.imshow(img,cmap='gray') 
## if you want to display more than an image per cell you need to call .show after .imshow
plt.show()
```

