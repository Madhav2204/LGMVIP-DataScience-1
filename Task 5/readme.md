## MNIST Dataset Classification :- 
- The mnist_train.csv file contains the 60,000 training examples and labels. 
- The mnist_test.csv contains 10,000 test examples and labels. 
- Each row consists of 785 values: the first value is the label (a number from 0 to 9).
- And the remaining 784 values are the pixel values (a number from 0 to 255).
- Download the dataset from [here](https://www.kaggle.com/oddrationale/mnist-in-csv).

### Packages Used :- 
```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import visualkeras

from sklearn.model_selection import train_test_split
from sklearn.metrics import confusion_matrix

from keras.models import Sequential
from keras.layers import Conv2D, Lambda, MaxPooling2D
from keras.layers import Dense, Dropout, Flatten
from keras.layers import LayerNormalization
from keras.preprocessing.image import ImageDataGenerator
from keras.utils.np_utils import to_categorical
from keras.utils.vis_utils import plot_model
```
