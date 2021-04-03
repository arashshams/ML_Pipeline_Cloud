# DSCI_525_group12

### UBC MDS Web and Cloud Computing group project

# About

This project aims to build and deploy Ensemble Machine Learning models in the cloud to predict daily rainfall in Australia on a large dataset (~6 GB), where features are outputs of different climate models and the target is the actual rainfall observation.

The dataset used in this work can be found [here](https://figshare.com/articles/dataset/Daily_rainfall_over_NSW_Australia/14096681) on figshare and has been put together by [Dr. Tomas Beuzen](https://www.tomasbeuzen.com/) of UBC MDS. The dataset contains daily rainfall data from 1889 to 2014 in New South Wales, Australia. 

This project includes four milestones as described below:

**Milestone 1**: Getting  the data from web using API, processing it and converting it to an efficient file format

**Milestone 2**: Moving the data to cloud, setting up the infrastructure in cloud and doing the ML model

**Milestone 3**: Setting up the distributed infrastructure (Spark) in cloud and running the same ML model using Spark

**Milestone 4**: Deploying the ML model in cloud so that other consumers can use it

# Report

The report for **Milestone 1**: "Tackling big data on a laptop" can be found in a notebook [here](https://github.com/UBC-MDS/dsci_525_group12/tree/readme/notebooks).

# Dependencies

- ` Python `

- ` pandas `

- ` dask `

- ` rpy2 `

- ` pyarrow `

- ` R `

- `scikit-learn`

# License

- The materials on predicting daily rainfall in Australia are licensed under the [MIT License](https://github.com/git/git-scm.com/blob/main/MIT-LICENSE.txt) (Copyright © 2020 Master of Data Science at the University of British Columbia).

- The dataset is licensed under the [Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

## Contributors

|  	 Core contributor| GitHub handle| 
|---------|---|
|  Neel Phaterpekar |  @nphaterp| 
|  Arash Shamseddini | @arashshams| 
|  Charles Suresh | @charlessuresh| 

## References

- Beuzen. T., Daily rainfall over NSW, Australia (2021): https://figshare.com/articles/dataset/Daily_rainfall_over_NSW_Australia/14096681/3

- Beuzen. T., DSCI 525 Example Project: Data Collection (2021): https://github.ubc.ca/MDS-2020-21/DSCI_525_web-cloud-comp_students/blob/master/get_data.ipynb
