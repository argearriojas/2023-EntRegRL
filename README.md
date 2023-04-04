# Example code for article submission

## Setup
```
$ python3 -m pip install -U tqdm joblib numpy pandas scipy matplotlib gym=0.21
```

## Reproducing the figures
The script `main.py` can be directly executed to produce most figures in the manuscript, like this:
```
$ python3 main.py
``` 

Some figures in the manuscript are time consuming to compute. This script as delivered, will compute simpler versions that will be ready much faster. You can compute the full, time consuming versions of the figures by uncommenting the appropriate lines of code at the bottom of the script `main.py`.

## The result
Here are example images of the figures this code produces:

### Figure 2
![Figure 2](figure_2.png)

### Figure 3
![Figure 3 top](figure_3_top.png)
![Figure 3 bottom](figure_3_bottom.png)

### Figure 5
![Figure 5](figure_5.png)

### Figure 6
![Figure 6a](figure_6a.png)
![Figure 6b](figure_6b.png)
![Figure 6c](figure_6c.png)

### Figure 7
![Figure 7](figure_7.png)

### Figure 8
![Figure 8](figure_8.png)
