# Neural Plot
## This Libary is working on Matplotlib
## Currently Under Development


### Single Layer Graph Plotting _(1 - Neural Net.ipynb)_

```python
for i, c in enumerate(['r', 'g', 'b']):
    x,y,z = mat3dl(32, 32, 3, (i,i+1))
    ax.scatter(x, z, y, c=c, marker='o')
plt.show()
```
![alt text](Screenshot/Image-001.png "Single Layer Plotting")

## Multilayer Layer Graph Plotting _(2 - Neural Net.ipynb)_

```python
layers = [(32, 32, 3, 'rgb', '.'),(16, 16, 5, 'r', '+'),(20,20,3,'y', 's'),(5,5,5),(10,1,1,'b', '^')]
neuralplot(layers)
```
![alt text](Screenshot/Image-002.png "Multilayer Layer Plotting")


## 2D Network Plot _(3 - Neural Net.ipynb)_
```python
layers = [(1, 32, 1, 'b','o'),(1, 32, 1, 'r', '.'),(1, 8, 1, 'g', '.'),(1, 12, 1, 'g', '.'),(1, 4, 1, 'm', 's')]
neuralplot(layers)
```
![alt text](Screenshot/Image-006.png "2D Network Plot")


## Plot Simple 3D Network  _(3 - Neural Net.ipynb)_

![alt text](Screenshot/Image-003.png "Plot 2D Network - 1")

## Plot Complex 3D Networks _(3 - Neural Net.ipynb)_
```python
layers = [(4, 4, 3, 'rgb','s'),(2, 2, 2, 'y', 'o'),(3, 3, 3, 'g', '.'),(5, 5, 1, 'b', '.'),(2, 1, 1, 'b', '^')]
neuralplot(layers)
```
![alt text](Screenshot/Image-004.png "Plot 2D Network - 2")


```python
layers = [(8, 8, 1, 'r','o'),(4, 4, 2, 'g', '.'),(2, 2, 3, 'b', '.'),(5, 5, 2, 'y', '.'),(2, 1, 1, 'c', 's')]
neuralplot(layers)
```
![alt text](Screenshot/Image-005.png "Plot 2D Network - 3")
