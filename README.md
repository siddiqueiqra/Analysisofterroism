# Title: "Analysis of Global Terrorism: Hot Zones and Threat Groups"

### Project Details:
### Objective:
- The objective of this project is to analyze global terrorism data and identify hot zones of terrorism. The project aims to explore patterns, trends, and key insights related to terrorist activities, including the number of attacks by year and region, fluctuating trends in the number of deaths, the total number of killed and wounded by attack type, the total casualties in different target types, visualizations of terrorist activities by region and year, countries with the highest casualties, and the top terrorist organizations based on reported killings.

### Code Overview:

### Importing necessary libraries:

pandas, numpy, seaborn, matplotlib.pyplot
Loading the dataset:
Read the dataset from a CSV file using pandas (df = pd.read_csv('globalterrorism.csv')).

### Data preprocessing:
Renaming columns for better understanding.
Creating a new DataFrame with selected columns.
Handling missing values by dropping rows with null values.
Dropping duplicate values.
Understanding Terrorism Hotspots with visualization:

### Visualizing the number of terrorist attacks by year using line and bar plots.
Analyzing fluctuating trends in the number of deaths over the years using a bar plot.
Total number of killed and wounded by attack type:

Creating a pivot table to calculate the total number of killed and wounded individuals by attack type.
Visualizing the results using a bar plot.
> Total casualties in attacks:

Creating a pivot table to calculate the total number of casualties by attack type.
Visualizing the results using a bar plot.
> Analysis by target type:

Creating a pivot table to calculate the total casualties by target type.
Visualizing the top 10 target types with the highest casualties using a bar plot.
> Analysis by country:

Creating a pivot table to calculate the total casualties by country.
Visualizing the top 10 countries with the highest casualties using a bar plot.
> Analysis by organization:

Creating a pivot table to calculate the total killings by terrorist organization.
Visualizing the top 10 organizations with the highest reported killings using a bar plot.
