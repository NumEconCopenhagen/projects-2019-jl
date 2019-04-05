# Dataproject

Should contain a short introduction to your project, and show how to produce your results.

This data analysis project presents data on total external export from 1997 to 2018. The export is distributed between nine different categories which are: 
  
  Live Animals, Food, Beverages and Tobacco 
  
  Crude Materials, Inedible, except Fuels
  
  Chemicals and Related Products 
  
  Manufactured Goods Classified Chiefly by Material
  
  Machinery (excl. transport equipment)
  
  Transport Equipment
  
  Miscellaneous Manufactured Articles 
  
  Mineral Fuels, Lubricants and Related Materials 
  
  Vessels, Aircraft etc. 

Our data set is imported from Statistics Denmark (Danmarks Statistik) and the data set is originally called UHV1. The data set contains both seasonally and non seasonally adjusted numbers and we choose to use only the non seasonally adjusted numbers. The data is in nominal prices which we want to change into real prices. Therefor we import another data set from Statistics Denmark the data set is originally called "PRIS112" and contains the danish consumer price index which can be used to transform the nominal values into real values by merging the two data sets and dividing the inflation rate on the rest of the data. 

To be able to illustrate the change in the variables better we choose to calculate the percentage growth rate, which gives us a new data set. This data set we do a basic statistics analysis on to get an overview of which categories have evolved better over the years. In the end we present the percentage change variables in an interactive plot, where you are able to adjust the time span and choose between the categories from a drop down menu. 

To be able to produce our results you should run our code from top to end. Be aware that some of the code does not respond well to being run several times. When this is the case it appears explicit in our code document and you will have to start running the code from the top again. 
