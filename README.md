 Reproducibility Materials 
================


We develop a regression procedure for modeling directional responses in arbitrary dimensions while the covariates are on Euclidean space. In general, modeling directional responses is significantly challenging due to the presence of intractable normalizing constants in probability distributions on the corresponding sample spaces. 
 Therefore,  the regression for the general dimensional spherical responses is nontrivial, and many of the standard techniques commonly employed in modeling responses on Euclidean space cannot easily be adapted to the context. 
 
 
 First of all, the readers are encouraged to consider browse through the file "RBVNFPackage_installationGuide.pdf".
 
 In this project, we develop 4 algorithms:
 1) Em algorithm for obtaining the posterior mode of the regression coefficient. 
 2) MCMC algorithm to sample from the posterior distribution of the regression coefficients. 
 3) EM-glmnet algorithm to conduct the LASSO regression for a directional response. 
 4) MCMC for BAyesian Lasso regression for the directional response. 
 
 In this folder we have included the following: 
 
 1) The readers are referred to the reproducibility reports and the corresponding R Markdown.Rmd file a demonstration of the usage of the algorithms. 
 
 2) We include the code files (.Rmd files) for data analysis included in the manuscript. 
 3) We have included the extensive simulation that we have conducted
 4) Codes are included for creating the summary of the simulations
 5)  a tutorial slide "RBVNFPackage_installationGuide.pdf" is included for the initial setup and testing of the relevant R functions. 
 6) The R workspaces (including the Workspaces corresponding to the real data analysis), utilized to generate the results and the plot are included. 
 
 7) The simulations pertain to analyzing a total of 1800 datasets of various settings, therefore 1800 different sets of MCMC samples from the respective posterior. Due to the huge size fo the 1800 files containing the MCMC posterior samples, we could not upload it to GitHub. Interested readers may reproduce the results using the codes provided in these files (or request the author to arrange sharing it via a more direct procedure. Harddrive storage)
 8) PLots are also included in the plots folder. 