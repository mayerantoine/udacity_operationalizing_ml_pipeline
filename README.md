
# Operationalizing Machine Learning pipeline in Azure ML

This project is part of the Udacity Azure ML Nanodegree. In this project, we  deployed the best model generated from an auto ml training  process as a realtime web service endpoint.We test the endpoint. We create and publish an azure ml pipeline that reproduce and automate the complete process.

The data is related to direct marketing campaigns (phone calls) of a Portuguese banking institution.The classification goal is to predict if the client will subscribe a term deposit (variable y).

The best performing model was a VotingEnsemble. 

## Architectural Diagram
An architectual diagram of the project:
* Find the best model using Azure auto M, deploy the model and test it (using Azure Ml Studio portal)
* Develop an Azure ML pipeline with all the steps for automation and reproducibility (Organizing and control via a notebook)

<img src="diagram.png"   alt="operationalizing pipeline"  style="float: left; margin-right: 10px;" />

## Key Steps
<p>
    <img src="screens\azserviceprincipal.JPG"   alt="operationalizing pipeline"  style="float: left; margin-right: 10px;" />
    <img src="screens\amlworkspaceshare.JPG"   alt="operationalizing pipeline"  style="float: left; margin-right: 10px;" />
    <img src="screens\datasets.JPG"   alt="operationalizing pipeline"  style="float: left; margin-right: 10px;" />
    <img src="screens\automl_experiment.JPG"   alt="operationalizing pipeline"  style="float: left; margin-right: 10px;" />
</p>

## Screen Recording
*TODO* Provide a link to a screen recording of the project in action. Remember that the screencast should demonstrate:


