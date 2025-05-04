# Analysis of Crime and Temperature Data

This project explores the evolving relationship between crime patterns and temperature trends, aiming to provide insights for public safety strategies, law enforcement, and urban planning. By analyzing crime and temperature data, this project investigates whether temperature trends have an impact on crime rates.

## 📂 Project Structure
- `analysis.Rmd`: R Markdown file containing the data exploration, analysis, and visualization steps.
- `report.pdf`: Report with detailed explanations of findings and visualizations.
- `data/`: Folder containing the raw and cleaned datasets.

## 📊 Dataset
The datasets used in this project include crime and temperature data:

- **Crime Data**: Contains information on various types of crimes reported over time.
- **Temperature Data**: Includes temperature records corresponding to the same time periods and geographic locations as the crime data.

The datasets are combined to analyze the relationship between temperature trends and crime patterns.

## ⚙️ Workflow
1. **Data Preparation**
   - Cleaned and transformed the crime and temperature datasets into a usable format for analysis.
2. **Independent Dataset Analysis**
   - Analyzed crime data for trends, seasonality, and patterns.
   - Examined temperature data for fluctuations, seasonal variations, and possible correlations with crime.
3. **Combined Dataset Analysis**
   - Merged the crime and temperature datasets to investigate correlations between the two.
   - Analyzed if temperature trends have a direct impact on crime rates.
4. **Visualizations**
   - Generated stroboscopic visualizations to illustrate the relationship between crime rates and temperature variations.
   - Used statistical plots (e.g., scatter plots, heat maps) to visually analyze trends and correlations.

## 📈 Results
- **Crime and Temperature Trends**: Found varying correlations between specific temperature ranges and types of crimes.
- **Visualizations**: The stroboscopic visualizations helped demonstrate patterns over time, showing how temperature fluctuations could potentially influence crime rates.
  
## ✅ Requirements
- **R 4.x**
- **R Libraries**:
  - `tidyverse`
  - `ggplot2`
  - `dplyr`
  - `scales`
  - `knitr`
  - `rmarkdown`
  
  Install dependencies using:
  
  ```R
  install.packages(c("tidyverse", "ggplot2", "dplyr", "scales", "knitr", "rmarkdown"))


## 📌 Conclusion

By combining crime and temperature data, this project reveals valuable insights into the potential impact of temperature on crime patterns. The findings contribute to the understanding of how environmental factors like temperature can influence criminal behavior, which can be useful for law enforcement and urban planning.
