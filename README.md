# Broken Lines Patching

Here in this project, I am fixing the broken lines of the table image.

## Installation 

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install these packages:

```bash
pip install matplotlib
```
```bash
pip install numpy
```
```bash
pip install opencv-python
```

## Import

```python
import numpy as np
import cv2
```

## How to execute the code
- Import the above two library first.
- Then provide the input image path at ```cv.imread()``` function. Incase the image is stored in same pwd then rename it as ```fig-1.jpg/png```.
- If you want to write the output in your disk then provide the path in ```cv.imwrite()``` function. If you don't provide the path then it will write the image in pwd.



## License
[MIT](https://choosealicense.com/licenses/mit/)
