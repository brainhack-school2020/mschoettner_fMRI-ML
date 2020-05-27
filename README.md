# Machine Learning classifier on fMRI data

Team contributors: Mikkel Schöttner

## Summary 

This project will use machine learning on the preprocessed [ABIDE](http://preprocessed-connectomes-project.org/abide/index.html) data set to predict autism spectrum disorder (ASD) from resting state functional magnetic resonance imaging (rs-fMRI) data.

Because of the large size of the data set, the main analysis will be run on a high performance computing (HPC) cluster.

## Project definition 

### Background

Several studies have found lower functional connectivity in the default mode network in people with ASD (Anderson, 2014). Based on these findings, rs-fMRI data have been used to predict autism by training a classifier on the multi-site ABIDE data set (Nielsen et al., 2013). This project aims to replicate these findings.

### Tools 

The project will rely on the following technologies:

- nilearn
- scikit-learn
- plotly
- HPC/compute Canada

### Data 

The Autism Brain Imaging Data Exchange contains resting state fMRI data from several sites of 539 individuals with autism spectrum disorder (ASD) and 573 neurotypical controls. It has been preprocessed using several different preprocessing pipelines. More information on that can be found [here](http://preprocessed-connectomes-project.org/abide/Pipelines.html). The data set is included in the Nilearn data sets. It can be downloaded using `nilearn.datasets.fetch_abide_pcp`. See [here](https://nilearn.github.io/modules/generated/nilearn.datasets.fetch_abide_pcp.html) for all parameter specifications.

### Deliverables

At the end of this project, we will have:

 - a Jupyter notebook that contains an interactive graph/dashboard created using plotly
 - a Jupyter notebook that includes preparation of the data, visualization, explanations etc.
 - a Python script that contains the main analysis

## Results

### Progress overview

The project was initiated by Mikkel Schöttner.

### Week 3 deliverable: data visualization

TO DO: Where can the dashboard be found?

### Tools I learned during this project

- machine learning
- using HPC clusters
 
## Conclusion and acknowledgement

TO DO: Include conclusion and acknowledgement.

## Literature

Anderson, J. S., Patel, V. B., Preedy, V. R., & Martin, C. R. (2014). Cortical underconnectivity hypothesis in autism: evidence from functional connectivity MRI. *Comprehensive guide to autism, 1457*, 1471.

Nielsen, J. A., Zielinski, B. A., Fletcher, P. T., Alexander, A. L., Lange, N., Bigler, E. D., ... & Anderson, J. S. (2013). Multisite functional connectivity MRI classification of autism: ABIDE results. *Frontiers in human neuroscience, 7*, 599.
