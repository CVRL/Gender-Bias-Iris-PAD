# Gender Bias in Iris PAD

Official GitHub repository for the paper: Mahsa Mitcheff, Siamul K. Khan, Patrick J. Flynn, Kevib Bowyer, and Adam Czajka, "Is There Evidence of Gender Bias in Iris Presentation Attack Detection Approaches?," IEEE Transactions on Biometrics, Behavior, and Identity Science **([ArXiv](xxx) | [IEEEXplore](xxx))**


### Table of contents
* [Abstract](#abstract)
* [Dataset of Gender Bias Iris PAD](#dataset)
* [Citation](#citation)

<a name="abstract"/></a>
### Abstract

This paper investigates whether there are gender-specific differences in iris images that cause variations in the accuracy of presentation attack detection (PAD). We assemble a dataset of iris images with gender metadata, containing both bona fide images and images of eyes wearing textured contact lenses. This dataset enables a comprehensive experimental analysis of four key research questions relating to the existence of gender-related effects, their generalizability, and their mitigation through training and testing datasets balancing. The analysis employs six different PAD algorithms, two dataset balancing strategies, and three classes of performance metrics to assess PAD performance. Our large-scale and diverse experiments show that although there are statistically significant variations in iris PAD performance for specific combinations of dataset, model and training regime, such variations are not rooted in population-wide male/female differences. Rather, observed accuracy differences across gender are found to be related to non-gender-based variations between groups that are only accidentally correlated with the bona fide/presentation attack class label. 

<a name="dataset"/></a>
### Dataset of Gender Bias Iris PAD

CSV files containing train and test sets used for training models for each experiment (E1, E3, and E4) can be find inside of CSVs folder.
Instructions on how to request a copy of the dataset will be added to the [CVRL webpage](https://cvrl.nd.edu/projects/data/).

<a name="citation"/></a>
### Citation

If you find this work useful in your research, please cite the following paper:

```
@inproceedings{Mitcheff_genderPAD_2026,
      title={Is There Evidence of Gender Bias in Iris Presentation Attack Detection Approaches?}, 
      author={Mahsa Mitcheff, Siamul K. Khan, Patrick J. Flynn, Kevib Bowyer, and Adam Czajka},
      year={2026},
      journal={IEEE Transactions on Biometrics, Behavior, and Identity Science},
}
```
