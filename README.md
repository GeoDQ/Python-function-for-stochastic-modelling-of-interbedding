# Python-function-for-stochastic-modelling-of-interbedding
I developed this stochastic interbedding modelling function to generate multiple realizations of interbedded chalk and flint layers, based on the variogram-based geostatistical modelling algorithm -Sequential Gaussian Simulation. This function can be adapted to model other interbedding cases, such as the interbedding of sandstone and shale layers.
#
The picture below shows the interbedded chalk and flint layers at Stevns Klint in Denmark.
![alt text](https://github.com/GeoDQ/Stochastic-modelling-of-interbedding/blob/main/Picture1.jpg)
# 
User specified input parameters include: 2D model size and resolution, mean and standard deviation of the thickness distribution of lithology_1 (chalk in my case), and variogram range which describes the lateral variation of the thickness
# 
The output is a 2D matrix with 0s indicating lithology_1(chalk in my case) and 1s indicating lithology_2(flint bands in my case)
#
![alt text](https://github.com/GeoDQ/Stochastic-modelling-of-interbedding/blob/main/Picture1.png)
### References
- Pyrcz, M. GeostatsPy. https://github.com/GeostatsGuy/GeostatsPy/blob/master/examples/GeostatsPy_Testing.ipynb
- Janson, X. and Madriz, D.D., 2012. Geomodelling of carbonate mounds using two-point and multipoint statistics. Geological Society, London, Special Publications, 370(1), pp.229-246.
