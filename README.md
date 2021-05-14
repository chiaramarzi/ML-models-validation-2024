# ML-models-validation

A repository with examples of validation schemes of machine learning models. 

Each model has been trained, validated and test to perform age prediction based on neuroimaging features. The investigated sample includes 86 healty subjects, with age range between 19 and 85 years. Their brain MRI exams were collected and free available from the *International Consortium for Brain Mapping (ICBM)* (Mazziotta et al., 2001). The neuroimaging features extracted, previously investegated in (Marzi et al., 2020) were:
* Cortical thickness (mCT)
* Gyrification index (Pial_mean_GI)
* Fractal dimension (FD)

Both regression and classification ("young" vs. "old") tasks were performed, through Support Vector Machines (SVMs) algorithms. Performances were evaluted by means of Mean Absolute Error (MAE) and accuracy, respectively

# References

Marzi, C., Giannelli, M., Tessa, C., Mascalchi M., and Diciotti S. Toward a more reliable characterization of fractal properties of the cerebral cortex of healthy subjects during the lifespan. Sci Rep 10, 16957 (2020). https://doi.org/10.1038/s41598-020-73961-w

Mazziotta, J. et al. A probabilistic atlas and reference system for the human brain: International Consortium for Brain Mapping (ICBM). Philos. Trans. R. Soc. Lond. B Biol. Sci. 356, 1293–1322. https://doi.org/10.1098/rstb.2001.0915 (2001).

Müller A.C., Guido S. Introduction to Machine Learning with Python. 2016. O'Reilly Media, Inc. ISBN: 9781449369415
