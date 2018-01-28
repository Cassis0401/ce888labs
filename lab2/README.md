# myvehicles.py
This is the code about vehicles.csv,and Create histograms and scatterplots for "current fleet" and "proposed fleet". 
I use the function from python to get the values for mean, median, var,std and MAD.

- Mean: 30.481013
- Median: 32.000000
- Var: 36.831918
- Std: 6.068931
- MAD: 4.000000

I use the fuction called dropna() to remove the nan.

![logo](./my_scaterplot.png?raw=true)
this is scaterplot from the vihicles.csv

![logo](./my_histogram.png?raw=true)
this is histogram from the vihicles.csv

# mybootstrap.py
This is to get the standard deviation of both samples. 
I use data = df.values.T[0]	to get the values from curren fleet and T[1] to get data from new fleet
I use data = data[np.logical_not(np.isnan(data))] to remove the nan 

And the result are:
-  current fleet stander: 20.14457831325301
-  lower bound: 5.807489495727639
-  uooer bound: 6.95390809494446

-  new fleet stander: 30.481012658227848
-  lower bound: 5.135830850824099
-  uooer bound: 6.898307964967191

