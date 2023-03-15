# LeagueOfLegends

It is a Regression Problem, where i predicted the Score of the players, given their class, tier, role, win%, etc.
R2 score is taken as the primary metric for evaluating and comparing the model performance, while other metrics like mean squared error(MSE), root mean squared error(RMSE), mean absolute error(RMSE) are also taken under consideration for evaluation.
The workflow: 
Reading Data -> Cleaning Data -> Encoding -> Splitting Data -> Model Building with ML Algorithms -> HyperParameter Tuning with the Best Model -> Finding the important Features

The dataset contains the stats of the players of the game, which include their 'Name', 'Class', 'Tier', 'Role', 'Role %', 'Pick %', 'Ban %', 'KDA', etc

>>> The features are: <<<

Name : Name of the champion
Class : Fighter, Assassin, Mage, Marksman, Support or Tank
Role : Top, Mid, ADC, Support or Jungle
Tier : God, S, A, B, C or D
Score : Overall score of the champion
Trend : Trend of the score
Win % : Win rate of the champion
Role % : Role rate played with the champion
Pick % : Pick rate of the champion
Ban % : Ban rate of the champion
KDA : (Kill+Death)/Assist ratio of the champion

Dataset link: 
https://www.kaggle.com/datasets/vivovinco/league-of-legends-stats-s13?datasetId=2892473&sortBy=dateRun&tab=profile

