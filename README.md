
# Privacy and Data Integration
## Goal
The goal of this project is to do the following:

1. Understand the definition of differential privacy,
2. Create a new definition of privacy to account for the ability to do data 
integration,
3. Show how the later definition generalizes the first and also adds less
noise to the original data.

## Motivation
Differential privacy (Dvork CITEME) is *the* mathematical framework for
analyzing privacy. Unfortunately, it adds a lot of noise to the data set 
(TODO). The motivation of differential privacy comes from the following 
idea: a person's data is private if the resulting statistic is not much
that different compared to the result as the same data set without the 
person's data.

Instead of this approach, I want to motivate a definition of privacy that
arises out of data integration. Essentially, the definition of privacy that
I have in mind is the following: a person's data is private if it has a 
small chance of being matched with their data in another data set. This 
project is to put this idea into mathematical formalism.
