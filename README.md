## Group 1 Project 4

## 

## Introduction
### Problem Statement: <br>
VinoVista, a renowned winery, is committed to producing consistently exceptional wines. However, they have observed variability in the quality of their white wine batches. To address this challenge, VinoVista seeks a predictive model that can accurately assess the quality of wine batches based on their chemical properties before bottling.

### Project Goal: <br>
The primary objective of this project is to develop a robust machine learning model capable of predicting wine quality on a scale of 0-10. This model will utilize a dataset containing various chemical properties of wine, such as acidity, pH, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, sulfates, and alcohol content.


#### Key Metrics in this data
![Variables](Resources/Screenshot 2024-11-12 201857.png)



#### Collaborators:
```yaml
Chuck Bui
Jack Jeffries
Beau Massie
Christopher Turner
```

### Proposed Technologies:
```yaml
Programming Language: Python (Jupyter Notebook, Pandas Library, ScikitLearn)

```

### This repo contains the following files:
```yaml
    root\
    - VinoVista.ipynb - the Jupyter Notebook file with our code for the project
    - README.md

    resources\
    - Screenshot 2024-11-12 201857.png - Screenshot of the metrics for this dataset
    - Group1Proposal.pdf - Document for project proposal

    data\
    - winequality-white.csv - dataset for the data science job market
```


### Resources, Cites
- *Wine Quality* - Dataset from UC Irvine Machine Learning Repository - https://archive.ics.uci.edu/dataset/186/wine+quality 

### Notes on wine componets 
    1. Fixed Acidity
Effect: Represents non-volatile acids in wine, such as tartaric, malic, and citric acids. It contributes to the overall acidity and freshness of the wine.

Impact on Taste: Higher levels enhance tartness and crispness, which can be desirable in white wines. However, too much fixed acidity can make the wine taste overly sour.

    2. Volatile Acidity
Effect: Mainly refers to acetic acid, which can turn into vinegar if present in high concentrations. It's a measure of the acids that can evaporate and contribute to the aroma.

Impact on Taste: Low levels can add complexity, but high levels result in unpleasant, vinegary flavors. Acceptable limits for volatile acidity are often higher in red wines compared to whites.

    3. Citric Acid
Effect: Naturally found in small amounts in wine, it adds freshness and enhances the fruitiness of the wine.

Impact on Taste: Gives a slight sharpness and can brighten the flavor profile, especially in white wines, making them taste fresher.

    4. Residual Sugar
Effect: The sugar left after fermentation. It's a key factor in determining the sweetness level of the wine.

Impact on Taste: High residual sugar leads to sweeter wines, while low residual sugar results in drier wines. It can also balance acidity, making the wine taste smoother.

    5. Chlorides
Effect: Reflects the salt content in wine, often derived from the soil in which the grapes were grown.

Impact on Taste: Adds body and mouthfeel. However, high levels can make the wine taste salty or brackish, which is generally undesirable.

    6. Free Sulfur Dioxide (SO₂)
Effect: Acts as an antioxidant and antimicrobial agent, protecting wine from oxidation and spoilage.

Impact on Taste: Adequate levels preserve the wine's freshness and prevent spoilage. However, excessive sulfur dioxide can impart a pungent, chemical-like taste and aroma.

    7. Total Sulfur Dioxide
Effect: The sum of bound and free SO₂ in wine. It’s a crucial preservative used during the winemaking process.

Impact on Taste: While necessary for stability, high levels can cause off-flavors and are a common cause of headaches for sensitive drinkers.

    8. Density
Effect: Often used to estimate the sugar content in wine. A higher density indicates a higher sugar level, which can suggest sweetness.

Impact on Taste: Affects mouthfeel; wines with higher density often feel fuller or richer. It’s also an indicator of the alcohol and sugar content balance.

    9. pH
Effect: Measures the acidity level. A lower pH means higher acidity, contributing to the wine’s stability and shelf life.

Impact on Taste: Lower pH wines taste sharper and more acidic, while higher pH wines can taste flabby or less vibrant. Most wines have a pH between 3.0 and 4.0, with whites generally being more acidic (lower pH) than reds.

    10. Sulphates
Effect: Often added to wine as a preservative to prevent oxidation and microbial growth.

Impact on Taste: Can enhance the wine’s flavor profile and longevity but, in excess, may lead to bitter or metallic notes.

    11. Alcohol
Effect: Produced during fermentation, where sugars are converted to ethanol. Alcohol content is a key factor in the body and warmth of the wine.

Impact on Taste: Higher alcohol levels contribute to a fuller body and a warming sensation. However, if the alcohol is too high relative to other components, it can make the wine taste hot or unbalanced.

### Summary:
Balance: The interplay between acidity, sugar, and alcohol determines the balance of the wine.
Aroma and Flavor: Volatile acidity, sulphates, and residual sugar can influence the aroma and complexity.
Mouthfeel: Factors like alcohol, sugar, and chlorides affect the texture and body of the wine.
