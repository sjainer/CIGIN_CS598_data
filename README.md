# Chemically Interpretable Graph Interaction Network for Prediction of Pharmacokinetic Properties of Drug-Like Molecules

This repository is to reproduce the paper Chemically Interpretable Graph Interaction Network for Prediction of Pharmacokinetic Properties of Drug-Like Molecules as a part of Deep Learning for Healthcare course of Spring 2024. 

When developing new drugs in the pharmaceutical industry, it is very useful to be able to predict important properties before performing trials. One such property is the solubility of a substance, which is expensive to compute manually, but extremely important to the efficacy of a drug. The paper proposes an approach for predicting this for a given uncharged solute/solvent pair. 


In this repository we:
- Reproduce main experiments of the paper
- Do ablations
- Do further experiments

To run our experiments, please use the [DL4H_Team_25.ipynb](https://github.com/sjainer/CIGIN_CS598_data/blob/main/DL4H_Team_25.ipynb) notebook. The notebook consists of various sections which will be discussed.

## Sections

- Introduction
- Data prepration
- Testing main hypothesis
- Additional experiments
- Ablations
- Results and conclusions


### Section description
Bellow is the general description of each section and steps to run it:

##### Introduction: 
This section discussed the paper motivation, the information about the approach and, the model architecture. It also discusses the phases of the model and provides steps to reproduce the results. It also imports the required packages.

##### Data prepration:
This part of notebook discusses the steps taken to obtain the data for our experiments. It consists of downloading the dataset and curating it and converting it to the expected format. Inside the hidden cells we also provide statistics and visualization about the data we use. 

##### Testing main hypothesis:
This section conducts our main experiments. Here we first define our model in Pytorch with detailed model description. Next cells do the training, followed by evaluation. Finally results are compared with that of reported in the paper. Run the cells in the order to do the training.

##### Additional experiments:
This section discusses the additional experiments performed with the second version of the model. It starts with pre-processing of data and defining the model followed by training and reporting the results. Run the cells sequentially to view the results. Don't forget to uncomment the training cells if you want to train from scratch, otherwise it feed the saved model to the notebook. There are three aditional experiments in total, and all follow the similar trend.

##### Ablations:
This section also has the similar structure of the previous section. We performed three ablations in total, and each of those consists of defining the model, training loop (which shall be uncommented or model should be loaded) followed by results. Run cells sequentially to get the desired results. 

#### Results and conclusions:
This section discusses the results and the conclusions.

## Requirements
Refer to the Enivorment cell in the Methodology section within the introduction to find the required packages.

## Data and images
All the data used and the models trained are also available within the data folder in the repository. Images are also within the images directory.

## Team
- Shrusti Jain (Shrusti2)
- Lahari Anne (Lanne2)
- Hossein Arjomandi (hm31)

## License
MIT

