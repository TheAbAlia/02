# 02
Titanic

This is a case study of the classification problem on the "Titanic" dataset. The dataset is not model ready and required processing. We do it in steps:

01. Pre-analysis.
01.01. We see that the feature "Name" does not depend on the dataset, albeit there exists "Titles" which are. In particular, the title occurs after a ", " and before a ".". Finally, we remap by groupby. We identified these four cells as the most frequent, the others are being NA afterwards.
We drop the feutures "Ticket", since it contains high ratio of duplicates #We drop the feutures "Cabin", since it contain high ratio of null-values. We drop the feutures "Name" and "PassengerId", since they should have no dependence on the dataset.

02. Analysis.
02.01.01. Analysis via desciptive data.
02.01.02. Analysis via visualizing data.
02.02. Feauture preperation and categorical prep.
02.03. Feauture scaling.

03. Modelling.
03.01 Building the pipeline.
03.02 Parameters hyper tuning and cross validation.
