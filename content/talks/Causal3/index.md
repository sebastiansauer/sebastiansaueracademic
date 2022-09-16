---
date: "2022-09-15"

image:
  caption: Title Cover by Karsten Luebke
  focal_point: Smart
summary: More emphasis should be put on the mapping and link between subject matter knowledge and data modeling to avoid drowning in the data
tags:
- causal
title: "Acting Data-Driven - But How?"
url_pdf: "https://sebastiansauer-academic.netlify.app/uploads/ECDA-2022-causal-luebke-etal.pdf"
url_code: "https://luebby.github.io/ECDA-2022"
---

Talk presented at [ECDA 2022](http://ecda2020.unina.it/)


## Authors 


Karsten Lübke (FOM)

Matthias Gehrke (FOM) 

Jörg Horst (FH Bielfeld) 

Sebastian Sauer (HS Ansbach) 

Gero Szepannek (HS Stralsund) 






## Abstract

In many cases, data is used to draw conclusions, e.g., to support decision-making processes.
But quite often, the data is inconclusive, with Simpson's paradox being the most prominent example where the adjusted or unadjusted effect may even show in opposite directions.
But as causal inference is one of the data science tasks (Hern et al., 2019), the qualitative assumptions about the data generating process need to be considered and discussed in order to draw correct conclusions.

In a simulated scenario we asked students as well as practioners which conclusions they draw from a given regression output. In the simulation the sign of the estimate of interest changes if a covariable is added to the model.
First the result is presented without a causal diagram, afterwards with a causal diagram. 
The results show that the chosen conclusions are quite often wrong given the information provided (with or without the causal diagram). 
As a consequence for data science projects, more emphasis should be put on the mapping and link between subject matter knowledge and data modeling to avoid drowning in the data.




## Bibliography


HERN, M.A and HSU, J. and  HEALY, B. (2019). A Second Chance to Get
Causal Inference Right: A Classification of Data Science Tasks CHANCE, 32(1), 42--49. 



