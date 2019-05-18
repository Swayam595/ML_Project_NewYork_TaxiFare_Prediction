
Instructions :

1) Download dataset from https://www.kaggle.com/c/new-york-city-taxi-fare-prediction/data
2) select the model
3) Run All

Other details:
1) Used Keras regressor and light GBM 
2) used Bokeh to plot co-ordinates on goolge maps
3) libraries used 
  - numpy 
  - pandas 
  - sklearn
  - seaborn
  - matplotlib
  - bokeh
  - keras
  - tensorflow
  - lightGBM
  - shutil
4) Light GBM, Keras, Random Forest regression are preformed on google collab.
5) uploaded complete dataset post data cleaning for convenience (https://drive.google.com/open?id=18P0MKr7cWTrosRGP4yidg89ylPUux3uS)
6) RMSE :
    linear regression : 6.341
    Random forest : 5.383
    Keras Regressor with 11 features : 5.202
    Keras regressor with 18 features : 5.160
    Light GBM :  3.840
7) Please get your own google api key to work with bokeh plots, key might expire soon
8) Haversine distance derived distance in Miles (as units of measure)
9) Overall take-away :
  - Light GBM is fast, efficient;
  - Random forest will work well if we increase depth(parameter tuning is important) 
  - Keras works well as we add-in more features (believe me feature Engineering will awe-inspire you, at the same will let you explore whole new dimensions. Ofcoz with lot of after math. ) 
