# Biplot shiny operator

##### Description

Shiny application for creating a biplot from 2 layers of data.

A biplot is typically used to show both the scores and loadings of a Principal Component Analysis in a single plot but can also be used with other matrix factorization methods. 

##### Usage
- Use in Tercen is somewhat involved as two layers of data must be added to the cross tab view. See: https://tercen.com/Rik/w/02c1a6dfed523f30e97c03be927d6979
![image](https://user-images.githubusercontent.com/36480607/178115142-7b098f70-c15b-4457-b04a-6871a1c9ec00.png)


- Set the layer selector to `All` before switching to the `Operator View`

Input projection Layer 1|.
---|---
`row`           | rows contain the observations (i.e. PCA scores)
`colors`        | Factor(s) or variable(s) added as colors are used to colour the points for the score plots
`labels`        | A single factor that identifies the observations

Input projection Layer 2|.
---|---
`column`        | columns contain the variables (i.e. PCA loadings)
`labels`        | A single factor that identifies the variables

Output relations|.
---|---
`Operator view`        | Interactive biplot application, Set the layer selector to `All` before switching to the `Operator View`


##### Screen shot:

![image](https://user-images.githubusercontent.com/36480607/178115236-68830e32-3c93-4415-8e7a-8b3233b3c0a8.png)

