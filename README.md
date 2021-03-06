# Instructions for reading Walkthrough Example


This Walkthrough is intended for showing how to interact with the simpful Probabilistic Fuzzy System. It mainly uses the Probabilistic Fuzzy System which can be found at: https://github.com/Nikhilrs1993/simpful and the evolution modules which are listed in the folder `modules`(contained in the zip file). If you just want to view the results, you can just view them online as the results have been saved in the notebooks.

The quickest way to get the code runnning is probably to set up a virtual env using the simpfulediting.yml file.
Alternatively, one can pip install the master branch of https://github.com/Nikhilrs1993/simpful.

**To quickly see what's possible go through the notebooks following the given order. Unzip the zip file in the root folder (using extract here).**

1. The first one uses automatic modelling for constructing the Probabilistic Fuzzy Model (PFS, using Genetic Programming) using the titanic dataset.
2. The second one takes a look at the results obtained from the first one.
3. The third one contains information on how to `manually` make a PFS model using the simpful PFS system.

Directories outline (contained in zip):

inputs_processed_ --- contains titanic sets in a processed way (X-train, X-test etc..)

modules --- contains the code for Genetic Programming. Has some comments but needs more.

saved_models --- contains 2 already found models

saved_pickles --- Helper folder for saving intermediate results.

Titanic_survival_dataset(Contains preprocess steps) --- contains exact preprocessing steps. Consult if you're interested.

**The best way to read the notebooks is probably in the order given.**

sample_log.log --- contains (some) information about the evolution process.

simpfulediting.yml --- **Probably quickest way to run the code**. However, the only (main) new dependency is sklearn. Specifically the confusion matrix was used because of the computation speed. An alternative to remove the dependency is commented out in Simpful. However it comes at the price of reduced efficiency.
