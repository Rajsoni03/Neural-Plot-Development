# Neural Plot
## This Libary is working on Matplotlib


### Single Layer Graph Plotting

```python
for i, c in enumerate(['r', 'g', 'b']):
    x,y,z = mat3dl(32, 32, 3, (i,i+1))
    ax.scatter(x, z, y, c=c, marker='o')
plt.show()
```
![alt text](Screenshot/Image-001.png "Single Layer Plotting")

## Multilayer Layer Graph Plotting

```python
layers = [(32, 32, 3, 'rgb', '.'),(16, 16, 5, 'r', '+'),(20,20,3,'y', 's'),(5,5,5),(10,1,1,'b', '^')]
neuralplot(layers)
```
![alt text](Screenshot/Image-002.png "Multilayer Layer Plotting")
