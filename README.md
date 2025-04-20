# Identifying Characteristics of Suspicious Transactions Using Association Rule Mining and Time Series Anomaly Detection
*Final project for [INFO 523: Data Mining and Discovery](https://infosci.arizona.edu/course/info-523-data-mining-and-discovery) — University of Arizona*
  
  
## Project Intro/Objective
The purpose of this project is to analyze financial transaction data in order to identify potentially suspicious activity that may indicate fraud or money laundering. Using association rule mining, we aim to discover common patterns in flagged transactions that could improve detection and prevention methods. We also apply time series anomaly detection techniques to assess whether suspicious transactions are increasing over time and to identify irregular spikes. 

Together, these methods provide a data-driven foundation for proactive monitoring and intervention. By uncovering these insights, the project contributes to enhancing transparency and accountability in financial systems, with clear implications for civic and regulatory efforts.
  
  
## Dataset
The Kaggle dataset used for this project can be accessed using the following link:
- [Dataset Link](https://www.kaggle.com/datasets/waqi786/global-black-money-transactions-dataset)
  
  
## Authors
**Bryan Jacobs** — Association Rule Mining  
**Anirudh K** — Time Series Anomaly Detection
  
  
## Languages/Packages:
* R
 * tidyverse (ggplot2, dplyr)
 * janitor
 * arules, arulesViz
 * anomalize
 * caret
  
  
## Software & Platforms
* RStudio / R Markdown
* GitHub


## Models
* Association Rule Mining
* Time Series Anomaly Detection
  
  
## Repository Structure
- **`data/`**: Contains raw data file for analysis.
- **`code/`**: Contains `.Rmd` and `.html` files of code documentation with generated visuals.
- **`report/`**: Contains `.Rmd` and `.html` files of final report, including relevant code and generated visuals.
- **`README.md`**
  
  
## How To Run
#### For Simple Viewing
1. Download and open desired `.html` files

#### To Run Yourself
1. Clone the repository.
2. Open `info523_project_code.Rmd` in RStudio.
3. Download `Big_Black_Money_Dataset.csv` from `data/` folder and place in correct directory.
4. Run the code as usual.
