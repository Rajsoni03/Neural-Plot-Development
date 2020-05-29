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

## Plot Simple 3D Network  _(3 - Neural Net.ipynb)_

![alt text](Screenshot/Image-003.png "Plot 2D Network - 1")

## Plot Complex 3D Networks _(3 - Neural Net.ipynb)_

![alt text](Screenshot/Image-004.png "Plot 2D Network - 2")

![alt text](Screenshot/Image-005.png "Plot 2D Network - 3")
