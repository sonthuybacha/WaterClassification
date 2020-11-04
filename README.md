# Water classification project
> The objective of this project is to provide a water color classification based on remote sensed images


```python
#export
from WaterClassification.core import *
from nbdev.showdoc import *
```

## Data Preparation
> All the processes for cleaning the raw data are defined and explained in the [Data_Preparation](https://cordmaur.github.io/WaterClassification/Data_Preparation/) documentation

## EDA - Exploratory Data Analysis
> The notebook [EDA](https://cordmaur.github.io/WaterClassification/EDA/) contains the initial data processing and a exploratory data analysis of the available reflectances

## Core Functions
> The core functions that are mostly used throughout the notebooks can be found in [core](https://cordmaur.github.io/WaterClassification/core/) documentation
This is an example of the `wavelength_range` function, that returns a list of wavelengths given initial, final and step values, specified in nanometers(nm)

```python
show_doc(wavelength_range)
```


<h4 id="wavelength_range" class="doc_header"><code>wavelength_range</code><a href="https://github.com/cordmaur/WaterClassification/tree/master/WaterClassification/core.py#L37" class="source_link" style="float:right">[source]</a></h4>

> <code>wavelength_range</code>(**`ini_wl`**, **`last_wl`**, **`step`**=*`1`*)

Creates a range of wavelengths from initial to last, in a defined nanometers step.


```python
wavelength_range(340, 350)
```




    ['340', '341', '342', '343', '344', '345', '346', '347', '348', '349', '350']


