# Classic Motivational Problem

#### Objective: 
identifying handwritten digits from the MNIST Dataset

## Libraries used
    - numpy
    - pandas
    - matplotib

 ```python
import numpy as np # type: ignore
import pandas as pd # type: ignore
import matplotlib.pyplot as plt # type: ignore
np.set_printoptions(suppress=True, linewidth=999)
```
## In-between code
`minst_train.iloc[0, 1:].to_numpy().reshape(28, 28)`

## Final Result
`plt.imshow(minst_train.iloc[0, 1:].to_numpy().reshape(28, 28), cmap='gray', vmin=0, vmax=255)`
![image](/results.PNG)