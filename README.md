# setpy
A python library for data scientists, researchers,  and hobbyists alike to sort through, manipulate, and extract data from datasets.

## Requirements
* Python >= 3.6

## Installation
[setpy](https://pypi.org/project/setpy/) can be installed via [PyPi](https://pypi.org/project/setpy/) or [Github](https://github.com/makertech81/setpy).  

### Install via PyPi
```
$ pip3 install setpy
```

### Install via Github (the source)
```
$ python3 setup.py install
```

## Basic Usage
To start a basic project in Python using SetPy import the spmean class as shown (currently the only functionality available):
```python
from setpy import spmean

# First set the directory where your dataset files in txt format are. Include a backslash at the end.

directory_str = "datasets/"

# Create an spmean() class object with the directory as the constructor parameter.

spm = spmean(directory_str)

# Use the function dataMean() to calculate the mean of a certain column of data within as many dates as needed. Each set of dates are recorded as a seperate period.

covidArr = spm.dataMean("01/08/2020", "03/12/2020", "03/13/2020", "04/13/2020")

```

## Documentation
Still a in progress! Check back later for more.

## Limitations of Project
This project is fairly beginner, but in the future I’d love for this project to grow into way for and be a mainstream tool for and one doing research projects or working with datasets.  This will hopefully be even more flexible and dynamic in the future.

## Contributing
For now, open up an issue stating any interest, ideas, questions, or feedback.

## Contact
TJ Ledwith: makertech81@gmail.com
