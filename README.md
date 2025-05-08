# Overview of the Repo
The data_pull_OMOP notebook contains the queries to pull the relevant data from an OMOP database. The data_processing_EHR_FM notebook contains the code to convert the raw data into processed data for use in our modeling pipeline. The MACE_PT_and_prediction notebook contains code to pretrain a model to predict MACE and fine tune for MACE predictions. The mortality_prediction notebook contains code to fine tune pre-trained models for mortality predictions. The environment.yml file contains all package versions used for our paper.
     
Due to privacy restrictions around EHR data, the raw data cannot be shared.
