---
title: "Visualisation of non-linear modelling"
author: "Daniela Dunkler"
---

**Visualisation of non-linear modelling**
=========================================

<center><div class = "gray">*by Daniela Dunkler and Georg Heinze*</div></center>

<br>

## Goal of this shiny app
The goal if this app is to **visualize the possible different functional forms** which can be modelled with **fractional polynomials**, **natural (restricted cubic) splines**, or **linear B-splines**. For eleven different explanatory variables, you can visualise non-linear effects applying these popular methods of non-linear modeling. You can visualise first- or second-degree fractional polynomials, linear B-splines with up to 4 degrees of freedom and natural splines with up to 3 degrees of freedom. 

For each method, the relevant parameters can be changed and the resulting non-linear effect can be directly graphically assessed. Usually regression coefficients are estimated by the model, but in this app you can manually set the regression coefficients. In this way, you can explore how these coefficients effect the functional form of the association between the explanatory variable $x$, e.g. age, and an outcome of interest $y$, e.g. BMI.

Additionally, if one assumes a specific residual standard error, one can visualise how the outcome $y$ could look like. *Are these data realistic in a biomedical setting?*

A short introduction of non-linear effects and the three methods can be found in the tab *explanatory comments*.

If you are interested in **modelling of non-linear effects**, we refer to our second shiny app (*under construction*).

<br>
               
## Learning objectives
* Show which functional forms of the association between the explanatory variable $x$ and the outcome $y$ can be modelled with these methods.
* Assess if the assumption of linearity (i.e. linear association between the explanatory variable $x$ and the outcome $y$), is a good approximation of the true underlying association.
* Show that very complex functional forms may not be realistic for real biomedical data.

<br>
               
## Data used in this app
The data used to visualise non-linear modelling stem from the [National Health and Nutrition Health Survey (NHANES)](<https://www.cdc.gov/nchs/nhanes/index.htm>) from the waves 2007-2008 and 2009-2010. Variables in this app include various medical measurements like weight (in kg), waist circumference (in cm), triglyceride ( in mmol/L), high-density lipoprotein (HDL) cholesterol (in mmol/L), systolic blood pressure (in mm Hg), diastolic blood pressure (in mm Hg), or age. For each variable either one thousand men or one thousand women were randomly selected.

<br>

## Comments, suggestions
Comments, questions, or suggestions for improvement are welcome. Please use the accompanying [github repository](<https://github.com/biometrician/nonlinear_visualisation>) for this purpose.

<br>

## Impressum
An explanatory shiny app developed on behalf of the [STRATOS Intiative](<https://stratos-initiative.org/>).

Written by Dunkler Daniela & Georg Heinze, Oct. 2020.

Contact: daniela.dunkler @ meduniwien.ac.at
