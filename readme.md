# General description
Unsupervised learning with SOM, PCA and k-means

### Objective
Compare the results from three different unsupervised learning techniques:
* Principal Component Analysis (PCA)
* K-means
* Self-Organizing Maps (SOM)

### Data
* Files:
	- iris-data.txt: the Iris Plants Database
	- iris-info.txt: information about the Iris Plants Database
* Columns: 4 variables, 1 class
	- Variables:
		- sepal length in cm
		- sepal width in cm
		- petal length in cm
		- petal width in cm
	- Classes available:
		- Iris Setosa
		- Iris Versicolour
		- Iris Virginica
* Patterns: 150 patterns
	- 50 patterns of each class
	- The class information should “not” be used in the unsupervised learning, only to identify the three classes in the plots

### Unsupervised learning
* PCA: find and plot the PCA projection in two dimensions, using a different color for each class
* K-means: use k-means to classify the patterns in k=2, 3, 4 and 5 classes, and compare the obtained classes with the real ones
* SOM: use SOM to visualize the data, using different settings (topology and size of the map, learning rate, neighborhood function, etc.). For the “best” map, calculate also the component planes.
