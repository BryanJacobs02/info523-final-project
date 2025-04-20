# Identifying Characteristics of Suspicious Transactions Using Association Rule Mining and Time Series Anomaly Detection
*Final project for [INFO 523: Data Mining and Discovery](https://infosci.arizona.edu/course/info-523-data-mining-and-discovery) — University of Arizona*

## Project Intro/Objective
The purpose of this project is to analyze financial transaction data in order to identify potentially suspicious activity that may indicate fraud or money laundering. Using association rule mining, we aim to discover common patterns in flagged transactions that could improve detection and prevention methods. We also apply time series anomaly detection techniques to assess whether suspicious transactions are increasing over time and to identify irregular spikes. 

Together, these methods provide a data-driven foundation for proactive monitoring and intervention. By uncovering these insights, the project contributes to enhancing transparency and accountability in financial systems, with clear implications for civic and regulatory efforts.

### Authors
**Bryan Jacobs** — Association Rule Mining  
**Anirudh K** — Time Series Anomaly Detection

### Languages/Packages:
* R
 * tidyverse (ggplot2, dplyr)
 * janitor
 * arules, arulesViz
 * anomalize
 * caret

### Software & Platforms
* RStudio / R Markdown
* GitHub

### Models
* Association Rule Mining
* Time Series Anomaly Detection

- **`data/`**: Contains raw data files for analysis. These are typically excluded from version control for privacy or size reasons and are added to `.gitignore`.
- **`docs/`**: Contains any documentation files relevant to the project, such as instructions, explanations, or reports.
- **`src/`**: The source code for the project. It's divided into directories based on different aspects of the project (e.g., association rule mining, anomaly detection).
- **`results/`**: Output from the analysis, such as generated charts, graphs, or final results. These are typically not tracked in version control.
- **`.gitignore`**: Specifies files or directories to be ignored by Git (e.g., `.DS_Store`, `.env`).
- **`README.md`**: Provides an overview of the project, installation instructions, and any relevant usage details.
- **`LICENSE`**: The license under which the project is distributed.
- **`requirements.txt`**: A file listing the necessary dependencies for the project (if applicable).
