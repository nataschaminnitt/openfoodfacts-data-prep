# openfoodfacts-data-prep

**Description:** Data cleaning, exploratory and multivariate analysis for a missing-value suggestion system using the OpenFoodFacts dataset, prepared for Santé publique France.

## Project Overview
Santé publique France aims to enhance the OpenFoodFacts database by implementing an auto-completion system to help users fill in missing fields more efficiently. This project focuses on cleaning and exploring the OpenFoodFacts data to assess the feasibility of such a system.

## Repository Structure
- **Data_processing.ipynb**  
  Contains the data ingestion and preparation pipeline: importing the OpenFoodFacts raw dataset, selecting variables with high missingness, and applying at least three strategies for missing-value imputation and outlier detection, all encapsulated in reusable functions or classes.

- **Exploratory_analysis.ipynb**  
  Presents the exploratory data analysis: univariate summaries and diverse visualizations (histograms, boxplots, pie charts, scatter plots), multivariate investigations (correlation matrices, statistical tests), and application of PCA to condense the nutritional features into principal components.

- **Presentation_of_analysis.pptx**  
  A slide deck designed for non-technical stakeholders, summarizing the data processing workflow, key analytical findings, PCA results, feasibility conclusions, and a section explaining adherence to GDPR principles.

## Data Source
- **Download URL:** https://world.openfoodfacts.org/ 
- **Variable documentation:** https://world.openfoodfacts.org/data

### Data Sections
1. General product information (name, identifiers, dates)
2. Tags (categories, origin, geographic data)
3. Ingredients and additives
4. Nutritional information (nutrient amounts per 100 g)
