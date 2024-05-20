# README

## Overview

This project involves processing and analyzing data related to canine cases, specifically focusing on two sets of parameters (left and right) for each case. The code reads the data from an Excel file, processes it to extract relevant columns, and saves the processed data into CSV files. Additionally, it includes functions to handle image files, augment the data by flipping only the poor catagory images, and analyze the distribution of parameters.

## Setup and Installation

To run the code, you need the following libraries:

- pandas
- os
- matplotlib
- seaborn
- PIL (Pillow)

You can install the necessary libraries using pip:

```bash
pip install pandas matplotlib seaborn pillow
```

## Code Explanation

### 1. Import Libraries

```python
import pandas as pd
import os
import matplotlib.pyplot as plt
import seaborn as sns
from PIL import Image
```


## Conclusion

This code provides a comprehensive approach to processing, analyzing, and augmenting data related to canine cases. By following the steps outlined above, you can replicate the data processing pipeline and analyze similar datasets. The visualizations help in understanding the distribution of parameters, making it easier to draw meaningful insights.
