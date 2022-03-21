# coefficientofdispersion
# Find the coefficient of dispersion for any vector

# THIS IS R/R STUDIO SCRIPT

# Hello, I created a package in R for anyone who needed to find the coefficient of dispersion.  
# I use this at work for the county assessor's office.  It's to check the accuracy of property
# tax on sold homes.  The only input is the vector of values which in my case, is the current
# ratio.  I am hoping to update and expand the package to create the ratio first and then the 
# coefficient of dispersion by a dataset input.  Hope this helps, the package is called:
# CoefficientPackage (hoping to change that name in the future lol) and the only function in it 
# so far is the coeff function to find the coef of dispersion.  


install.packages("CoefficientPackage")
library(CoefficientPackage)
testvector <- c(1:45)
ceoff(testvector)
