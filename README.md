#Introduction

We are presented with data inputs and outputs from a Circulating Fluidized Bed (CFB) boiler. The inputs include fuel type and its respective fuel power capacity, and at the output is Flue Gas Flow. The data is in tabular format with daily records for 365 days.

#Aims

We are trying to work out a model, which will predict the Flue Gas Flow for different fuel mixes.

#Methodology
We will look into a number of regressors. The main focus is on Linear Regression as the data is fairly limited (ideally we'd appreciate hourly timeframe) and the phenomenon in question is likely of linear nature. 

#Conclusions

We manage to work out a funciton that gives us reasonably satisfactory results with the R-squared of 0.74. The model fits the data reasonalby well. We will await more info including hourly timeframe and a more varied fuel mix and see how that plays out.
