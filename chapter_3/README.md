## It seems like after I read the datafile.csv, there will apper many wrong codes or results. I think is because there are many comma in description. I think we should delete them and write a clear dataset from Rstudio.


data：https://www.kaggle.com/c/petfinder-adoption-prediction/data?select=breed_labels.csv

theme：https://www.datadreaming.org/post/r-markdown-theme-gallery/

dat$ASnum[dat$AdoptionSpeed == 1] = 1 * rgeom(sum(dat$AdoptionSpeed == 1), 0.1)  
dat$ASnum[dat$AdoptionSpeed == 2] = 2 * rgeom(sum(dat$AdoptionSpeed == 2), 0.1)  
dat$ASnum[dat$AdoptionSpeed == 3] = 3 * rgeom(sum(dat$AdoptionSpeed == 3), 0.1)  
dat$ASnum[dat$AdoptionSpeed == 4] = 4 * rgeom(sum(dat$AdoptionSpeed == 4), 0.1)  
****
dat$ASnum[dat$AdoptionSpeed == 1] = 1 + rgeom(sum(dat$AdoptionSpeed == 1), 0.05)  
dat$ASnum[dat$AdoptionSpeed == 2] = 8 + rgeom(sum(dat$AdoptionSpeed == 2), 0.05)  
dat$ASnum[dat$AdoptionSpeed == 3] = 31 + rgeom(sum(dat$AdoptionSpeed == 3), 0.05)  
dat$ASnum[dat$AdoptionSpeed == 4] = 100 + rgeom(sum(dat$AdoptionSpeed == 4), 0.05)  

