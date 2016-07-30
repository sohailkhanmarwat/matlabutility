# Statistics utility and data handling 

Functions related to statistics and data analysis.

* **castdata.m** : put vector data into a matrix by assigned group
* **covcc.m** : column by column covarience for two matrices.
* **groupmean.m** : calculate mean using **accumarray** but more control.
* **hotellingT2.m** :  multivariate t-test with Hotelling's T-square
* **inlier.m** : function, remove outliers from vectors

* **meltdata** : Put each data in a matrix as a variable in a row ("an obseervation"), column id and row id as two other variables 
* **nancorr.m** : calculate correlation coefficient, ignore NaN in each pair
* **nangeomean.m** : calculate geometric mean with NaN removed. 
* **nanls.m** :  calculate ls parameters and r, p vlaue for correlation
* **nanzscore.m** : z-transform with NaNs. (remove NaN and pass parameters to matlab function **zscore**)
* **num2month** : return month string given number 1~12
* **randeval.m** : simulate and make histogram of argument
* **subset.m** : subset in a function 
* **tcastdata** : put data from table into a matrix by assigned group
* **tnames.m** : show names of variable in a table
* **thead.m** : show first few lines of table data
* **tri2line.m** : grab upper triangle of a (symatric) matix to a vector
* **vmeanSE.m** : calculate and display mean and SE from a vector