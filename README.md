# **iMODA**

# **iMODA: integrative Multi-Omics Data Analysis**

In multi-omics studies, genotypes are typically available for all study subjects, whereas other data types may be measured only on a subset of subjects due to cost or other constraints. In addition, quantitative omics measurements, such as metabolite levels and protein expressions, are subject to detection limits in that the measurements below (or above) certain thresholds are not detectable. iMODA is a software program that performs integrative analysis of multi-omics data with missing values and detection limits. The quantitative omics variables are related to genetic variants and other variables through linear regression models, while phenotypes are related to quantitative omics variables and other variables through generalized linear models. An EM algorithm is used to perform maximum likelihood estimation for all model parameters. The current implementation covers both continuous and binary phenotypes. We are actively improving the capabilities of iMODA, so please check back frequently for updates.

Documentation (includes a description of example data):\
[iMODA](http://dlin.web.unc.edu/wp-content/uploads/sites/1568/2019/08/iMODA.docx)

Source Code (includes example data and a Linux executable):\
[iMODA.tar](http://dlin.web.unc.edu/wp-content/uploads/sites/1568/2019/06/iMODA.tar_.gz)
