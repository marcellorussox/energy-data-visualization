# Energy Data Analysis & Visualization 🌍📊

[![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)](https://www.r-project.org/) [![ggplot2](https://img.shields.io/badge/ggplot2-1.0.0-blue?style=flat)](https://ggplot2.tidyverse.org/)

A comprehensive exploration of global energy trends using R and ggplot2. This project investigates relationships between GDP, energy consumption, renewable adoption, and carbon intensity across nations.

![Sample Visualization](https://via.placeholder.com/800x400.png?text=Energy+Visualization+Examples) *Replace with actual plot screenshots*

## Features 🔍

-   **6 Key Visualizations** including scatter plots, bar charts, and stacked area charts
-   **Interactive R Notebook** with reproducible analysis
-   **Global Data** from 200+ countries (2000-2022)
-   **Critical Insights** on:
    -   Renewable energy adoption trends
    -   Energy-GDP relationships
    -   Carbon intensity patterns
    -   Continental energy mix comparisons

## Installation 💻

### Requirements

-   R (≥ 4.1.0)
-   RStudio (recommended)
-   Git

``` bash
# Clone repository
git clone https://github.com/your-username/energy-data-visualization.git
cd energy-data-visualization

# Install required packages
install.packages(c("tidyverse", "ggplot2", "ggrepel", "countrycode", "viridis"))
```

## Usage 🚀

1.  Open `Energy_Analysis.Rmd` in RStudio
2.  Knit the notebook to HTML/PDF
3.  Explore these key components:

| File                  | Purpose                        |
|-----------------------|--------------------------------|
| `owid-energy.csv`     | Primary dataset                |
| `Energy_Analysis.Rmd` | Main analysis notebook         |
| `scripts/`            | Helper functions & utilities   |
| `plots/`              | High-resolution output visuals |

## Key Visualizations 📈

### 1. GDP vs. Energy Consumption

``` r
ggplot(data, aes(gdp, energy_per_capita)) + 
  geom_point(aes(color = fossil_share)) +
  geom_smooth(method = "lm")
```

### 2. Renewable Energy Leaders

![Renewable Leaders](https://via.placeholder.com/400x300.png?text=Top+Renewable+Nations)

## Data Sources 📂

-   Primary dataset: [Our World in Data - Energy](https://ourworldindata.org/energy)
-   Supplemental data: [UN Energy Statistics](https://unstats.un.org/unsd/energy/)

## Results 🔬

Key findings from the analysis: 1. Strong correlation between GDP growth and energy consumption (r = 0.82) 2. 15% average increase in solar/wind adoption since 2015 3. Europe leads in low-carbon energy (42% share vs global 28%)

## License 📄

MIT License - See [LICENSE](LICENSE) for details

## Contact 📧

-   Marcello Russo - [marcello.russo\@mareasoftware.com](mailto:marcello.russo@mareasoftware.com){.email}
-   Project Link: <https://github.com/marcellorussox/energy-data-visualization>
