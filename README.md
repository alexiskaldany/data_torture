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

What are the most significant quantitative and categorical variables in determining the speed of adoption for a pet? To answer this question we will:

- Use single variable linear models to test the importance of each numerical variable.
- Use chi-square tests to find the differences in means for the categorical variables. 
