# data_torture
Fall 2021 DS

[Pawpularity Dataset](https://www.kaggle.com/c/petfinder-pawpularity-score/data)

- Using the metadata file 

# Work Split:

- Chapter 2 done by Andrew

- Chapter 3 done by Yixi

- Chapter 4 done by Sahara

- Chapter 5 done by Alexis

- Into and Conclusion done together

- We'll make the presentation at the end together

# Schedule

- Every Wednesday at 3pm via zoom


# Proposal: Alexis' Version

- Our data set comes from Kaggle. This data set is composed of information on individual animals, and the time it took for those animals to be adopted from the animal shelter. 

- Our team has used some preprocessing techniques to make this data more useful and analyzable. Specifically, the adoption speed variable was given to us as a categorical variable, with each level cooresponding to a bucket of a range of values. We transformed these buckets so that we could have a numerical dependent variable, one of the prerequisites for linear modelling.

## First START question

Is there a significant difference in the adoption speed between cats and dogs? To answer this question we will:

- Subset the two groups.
- Preform EDA to explore the data of these two subsets
- Use a t-test to check the means of these two subsets.

## Second START question

What are the most significant quantitative (Alexis for numerical variables) and categorical variables (Sahara for categorical) in determining the speed of adoption for a pet? To answer this question we will:

- Use single variable linear models to test the importance of each numerical variable.
- Use chi-square tests to find the differences in means for the categorical variables. 

## Third START question:
What combination of variables generates the best multi-variable models

## Sahara's version:
Pet rescue websites such as PetFinder have been around for decades and remain a popular method of finding new pets to adopt. 
We decided to analyze what features of a pet and their respective adoption profiles on PetFinder influenced the speed at which they got adopted. 
We got our dataset from Kaggle and it contains roughly 8000 observations of 23 variables pertaining to an adoption profile on PetFinder. 
Our dependent variable is AdoptionSpeed, a variable calculated by the speed at which the animal was (or was not) adopted. 
The adoption speed variable was given to us as a categorical variable, with each level corresponding to a bucket of a range of values. 
We transformed these buckets so that we could have a numerical dependent variable, one of the prerequisites for linear modelling.

The SMART Questions we plan to answer are:
- Do dogs get adopted faster than cats?
- What categorical variables influence adoption speed?
- What numerical variables influence adoption speed?
- What combination of categorical and numerical variables result in the best predictive model?
 
Our data set can be found here:
Data: https://www.kaggle.com/c/petfinder-adoption-prediction/data

Our github repo can be found here:
Github: https://github.com/alexiskaldany/data_torture
