# Introduction

Meteoroids are what we call “space rocks” that range in size from dust grains to small asteroids. This term only applies when they’re in space. Meteorites that fall to Earth represent some of the original, diverse materials that formed planets billions of years ago. These include the age and composition of different planetary building blocks, the temperatures achieved at the surfaces and interiors of asteroids, and the degree to which materials were shocked by impacts in the past.

We think the dataset of meteorites is fascinating and we can analyze various data related to the meteorite.

The dataset is from the Meteoritical Society which contains information on all of the known meteorite landings.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
pip install iPython
pip install -U scikit-learn
pip install json
pip install cartopy
pip install pandas
pip install matplotlib
pip install numpy
pip install traitlets
```

## Usage

```python
from iPython.display import Image
from sklearn import preprocessing

import json
import cartopy
import pandas as pd
import matplotlib.pyplot as plt
import numpy as np
import traitlets
import ipywidgets
```


### Dataframe

![image](https://github.com/ken1009us/meteorite-visualization/blob/main/image/df.png "df")

### The number of meteorites (top five)

![image](https://github.com/ken1009us/meteorite-visualization/blob/main/image/num-mete-top5.png "num")

### The largest mass of meteorites (top five)

![image](https://github.com/ken1009us/meteorite-visualization/blob/main/image/largest-mete-top5.png "largest")

### Plot the Earth Meteorite Landings Map (sketch)

![image](https://github.com/ken1009us/meteorite-visualization/blob/main/image/map-sketch.png "sketch")

### Plot the Earth Meteorite Landings Map

![image](https://github.com/ken1009us/meteorite-visualization/blob/main/image/map.png "map")

### Use a vega-lite visualization to analyze the Earth Meteorite Landings dataset

[Vegalite Visualization](https://ken1009us.github.io/meteorite-visualization/)

### Most frequent recorded classes of meteorite fall

![image](https://github.com/ken1009us/meteorite-visualization/blob/main/image/most-mete.png "most")

### Distribution of most frequent recorded classes of meteorite fall over the years

![image](https://github.com/ken1009us/meteorite-visualization/blob/main/image/stack-bar.png "stack-bar")


The stacked bar chart clearly depicted why L6 is the most frequent class of meteorite fall, as it has the largest count in every 25-year interval of the 20th century. One more interesting insight was to find which 25-year interval had more diverse meteorite fall? In between the years 1925 to 1950, about 9 types of meteorites have landed on earth.

### Highest average mass of meteorite fall by recorded class

![image](https://github.com/ken1009us/meteorite-visualization/blob/main/image/highest-mass.png "highest")

The goal here is to find out which classes of meteorites have the highest average mass recorded. This kind of insight can be valuable in specialized research about those classes and their material properties.

## Below is all my experimentation to get the implementation of these functions and the attempt at interactivity correct. (Download the Jupyter Notebook file)

![image](https://github.com/ken1009us/meteorite-visualization/blob/main/image/interactive.png "interactive")

### Occurrence of Different Types of Meteorite

![image](https://github.com/ken1009us/meteorite-visualization/blob/main/image/occurrence.png "occurrence")

L6:

![image](https://github.com/ken1009us/meteorite-visualization/blob/main/image/L6.png "L6")

H5:

![image](https://github.com/ken1009us/meteorite-visualization/blob/main/image/H5.png "H5")

### Discoveries Per Year and Discoveries Per Decade

![image](https://github.com/ken1009us/meteorite-visualization/blob/main/image/discoveries-per-year.png "discoveries-per-year")

![image](https://github.com/ken1009us/meteorite-visualization/blob/main/image/discoveries-per-decade.png "discoveries-per-decade")
