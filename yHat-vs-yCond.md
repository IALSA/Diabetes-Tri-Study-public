# Diabetes and Hypertension in ELSA, OCTO, and RUSH


<!--  Set the working directory to the repository's base directory; this assumes the report is nested inside of only one directory.-->


<!-- Set the report-wide options, and point to the external script file. -->







 









# Report Description

After model estimation, MPlus produces a .gh5 file that contains the data necessary for graphing (so they claim). The data extracted from a .gh5 file contains a column for the unique intercepts and slopes (so it seems). The trajectories produced with these values
```
yHat = B_Y + LINEAR*TIME
``` 
On the other hand, we can look at the fixed effect estimate in the .out file. Using the values for the estimated fixed effect we can produce the individual trajectories, conditional on the values of predictors
```
yCond = int + slope*TIME
```

So it is unclear which predicted trajectories are the correct ones. If .gh5 data can be trusted as the unique intercepts and slopes then there is a mistake in the computation of predicted trajectories from estimates in the .out file.


# Predicted (Time-yHat)
yHat : predicted value reconstructed from .gh5 estimates (int, slope)
Semi-transparent blue lines: individual predictions
Red line: Main effects

## Time-yHat : ELSA  
![](figure_rmd/mTraj_ELSA_yHat-1.png) 

## Time-yHat : OCTO 
![](figure_rmd/mTraj_OCTO_yHat-1.png) 

## Time-yHat : RUSHc 
![](figure_rmd/mTraj_RUSHc_yHat-1.png) 

## Time-yHat : RUSHe 
![](figure_rmd/mTraj_RUSHe_yHat-1.png) 

## Time-yHat: RUSHl 
![](figure_rmd/mTraj_RUSHl_yHat-1.png) 


# Predicted (Time-yCond)
yCond: predicted values reconstructed from .out estimates (fixed effects)
Semi-transparent blue lines: individual predictions
Red line: Main effects

## Time-yCond : ELSA  
![](figure_rmd/mTraj_ELSA_yCond-1.png) 

## Time-yCond : OCTO 
![](figure_rmd/mTraj_OCTO_yCond-1.png) 

## Time-yCond : RUSHc 
![](figure_rmd/mTraj_RUSHc_yCond-1.png) 

## Time-yCond : RUSHe 
![](figure_rmd/mTraj_RUSHe_yCond-1.png) 

## Time-yCond: RUSHl 
![](figure_rmd/mTraj_RUSHl_yCond-1.png) 




# Predicted (Age-yHat)

##  Age-yHat : ELSA 
![](figure_rmd/mTraj_ELSA_yHat_Age-1.png) 

##  Age-yHat : OCTO 
![](figure_rmd/mTraj_OCTO_yHat_Age-1.png) 

##  Age-yHat : RUSHc 
![](figure_rmd/mTraj_RUSHc_yHat_Age-1.png) 

##  Age-yHat : RUSHe 
![](figure_rmd/mTraj_RUSHe_yHat_Age-1.png) 

##   Age-yHat : RUSHl 
![](figure_rmd/mTraj_RUSHl_yHat_Age-1.png) 



# Predicted (Age-yCond)

##  Age-yCond : ELSA 
![](figure_rmd/mTraj_ELSA_yCond_Age-1.png) 

##  Age-yCond : OCTO 
![](figure_rmd/mTraj_OCTO_yCond_Age-1.png) 

##  Age-yCond : RUSHc 
![](figure_rmd/mTraj_RUSHc_yCond_Age-1.png) 

##  Age-yCond : RUSHe 
![](figure_rmd/mTraj_RUSHe_yCond_Age-1.png) 

##   Age-yCond : RUSHl 
![](figure_rmd/mTraj_RUSHl_yCond_Age-1.png) 



</br></br> </br></br></br></br></br></br></br></br></br></br></br>

