# Python-function-for-stochastic-modelling-of-interbedding
Interbedding is common in geology, it occurs when beds of a particular lithology lie between or alternate with beds of a different lithology. It often reflects a cyclical change in sedimentary conditions, e.g. sea level variations.
# 
I developed this stochastic interbedding modelling function to generate multiple realizations of interbedded chalk and flint layers, based on the variogram-based geostatistical modelling algorithm -Sequential Gaussian Simulation. This function can be adapted to model other interbedding cases, such as the interbedding of limestone and marl layers, the interbedding of sandstone and shale layers.
# 
User specified input parameters include: 2D model size and resolution, mean and standard deviation of the thickness distribution of lithology_1 (chalk in my case), and variogram range which describes the lateral variation of the thickness
# 
The output is a 2D matrix with 0s indicating lithology_1(chalk in my case) and 1s indicating lithology_2(flint bands in my case)
### References
- Pyrcz, M. GeostatsPy. https://github.com/GeostatsGuy/GeostatsPy/blob/master/examples/GeostatsPy_Testing.ipynb
- Janson, X. and Madriz, D.D., 2012. Geomodelling of carbonate mounds using two-point and multipoint statistics. Geological Society, London, Special Publications, 370(1), pp.229-246.
