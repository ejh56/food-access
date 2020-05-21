<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Food Access in the US
*Emily Horton*

*Data Analytics, Berlin, March 2020*

## Content
- [Project Description](#project-description)
- [Questions and Hypotheses](#questions-and-hypotheses)
- [Dataset](#dataset)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

## Project Description
The US has a food problem - almost half the population is obese, with a third of the population prediabetic. Food policy is made at state and county-level, but there is a lack of communication between similar counties about successful outcomes of these policy decisions. The project goal is to create a tool that will help different counties access successful food policies. 

## Questions and Hypotheses
My initial question was regarding the number of fast food restaurants, the number of grocery stores, and the number of convenience stores. My hypothesis was that the lower the number of grocery stores in a county, the higher the number of fast food and convenience stores. However, I found that the correlation was inconsistent. I decided there must be some connection between other variables. 

Because of the large number of variables (around 177), I decided that finding these connections would be a task best suited for ML clustering. With this development my question changed from ‘could I find a correlation’ to ‘how could I create a tool out of these clustered counties.’

## Dataset
I used the USDA’s Food Environment Atlas Dataset. It is an Excel document that has sheets for each sub-topic area (access, health, local, restaurants, etc). I chose to use state-level information as guidance and county-level data for analysis. 

## Workflow
1. Import data
2. Clean Data
3. Visualize
4. Analysis - redirect to ML
5. Clustering
6. Tableau 
7. Presentation 

## Organization
File Structure: 
* Notebooks: contain all jupyter notebooks for the project
* Datasets:
  * Standardized: contains all standardized data
  * Clustered-data: contains all data with clusters as a column
* Remaining data has been cleaned and saved in pickles

Recommended Notebook Order:
1. [Cleaning-FEA](https://github.com/ejh56/food-access/blob/master/Notebooks/Cleaning-FEA.ipynb)
2. [Exploration-FEA](https://github.com/ejh56/food-access/blob/master/Notebooks/Exploration-FEA.ipynb)
3. [Standardizing-Data](https://github.com/ejh56/food-access/blob/master/Notebooks/Standardizing-Data.ipynb)
4. [Correlation-Matrix](https://github.com/ejh56/food-access/blob/master/Notebooks/Correlation-Matrix.ipynb)
5. [Kmeans-clustering](https://github.com/ejh56/food-access/blob/master/Notebooks/Kmeans-clustering.ipynb)
6. [Clustering-Models-Exploration](https://github.com/ejh56/food-access/blob/master/Notebooks/Clustering-Models-Exploration.ipynb)

Optional: 
[Pipeline-FEA](https://github.com/ejh56/food-access/blob/master/Notebooks/Pipeline-FEA.ipynb)
[Top-5-Insecure-States](https://github.com/ejh56/food-access/blob/master/Notebooks/Top-5-Insecure-States.ipynb)


## Links
[Data](https://www.ers.usda.gov/data-products/food-environment-atlas/data-access-and-documentation-downloads/)
[Repository](https://github.com/ejh56/food-access)  
[Slides](https://docs.google.com/presentation/d/1DfowPzsA4-Mkxa1osxbEuvXzym5K_hvVPZHJy9NZBG4/edit?usp=sharing)  
[Tableau Tool](https://public.tableau.com/profile/emily.horton3683#!/vizhome/CountyExplorationTool/Dashboard1)


