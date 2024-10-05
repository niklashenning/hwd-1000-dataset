<h1 align="center">HwD-1000 Dataset</h1>

<p align="center">
    Dataset containing 1000 images of handwritten digits (0-9) in various styles and pen widths.
</p>

<br>

<p align="center">
    <img src="https://github.com/user-attachments/assets/6b84dd91-b959-472a-a3b6-e327c1826a3d">
</p>


## About
Each image of the dataset contains a single digit (0-9) that has been manually drawn on a white
28x28 px background with a black pen in varying widths and styles.
<br>
The dataset is intended to be used for training a basic digit recognition machine learning model.


## Installation
Clone this repository and copy the `dataset.csv` file and the `img` folder into your project.
```
git clone https://github.com/niklashenning/hwd-1000-dataset
```

## Usage
The `dataset.csv` file consists of two columns: the image path and the label for the image.
You can create a data frame from the file by using pandas' `read_csv()` method:
```python
import pandas as pd

dataframe = pd.read_csv('dataset.csv')
```


## License
This project is licensed under the [MIT license](LICENSE).
