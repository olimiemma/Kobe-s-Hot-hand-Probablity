
# Basketball Hot Hand Analysis-The Kobe Bryant Case Study

## Overview
This project analyzes the "hot hand" phenomenon in basketball using statistical analysis and simulation. The study focuses on Kobe Bryant's performance in the 2009 NBA Finals, comparing his actual shooting patterns to simulated data to test the hot hand theory.

## Dataset
- `kobe_basket`: Contains 133 observations of Kobe Bryant's shots
- Variables include:
  - Shot outcomes (Hit/Miss)
  - Game information
  - Quarter
  - Time
  - Shot descriptions

## Analysis Components
1. **Streak Analysis**
   - Calculated shooting streaks (consecutive successful shots)
   - Generated visualizations of streak distributions
   - Compared actual vs simulated shooting patterns

2. **Simulation**
   - Created independent shooter simulation
   - Matched Kobe's shooting percentage (45%)
   - Generated comparable sample size (133 shots)

3. **Statistical Comparison**
   - Analyzed streak length distributions
   - Compared actual vs simulated streak patterns
   - Evaluated evidence for hot hand phenomenon

## Key Findings
- Most common streak length: 0 (immediate misses)
- Similar distributions between actual and simulated data
- Limited evidence supporting the hot hand theory
- Shooting patterns appear more consistent with independent events

## Technologies Used
- R Programming Language
- Libraries:
  - tidyverse
  - openintro
  - dplyr
  - ggplot2

## Setup and Running
1. Install required R packages:
```R
install.packages(c("tidyverse", "openintro", "dplyr"))
```

2. Load the data:
```R
library(openintro)
data(kobe_basket)
```

3. Run analysis scripts for:
   - Streak calculations
   - Simulations
   - Visualization generation

## Repository Structure
```
├── data/
│   └── kobe_basket.csv
├── R/
│   ├── streak_analysis.R
│   └── simulation.R
├── plots/
│   ├── kobe_streaks.png
│   └── simulated_streaks.png
└── README.md
```

## Contributing
Feel free to submit issues and enhancement requests.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
- Original hot hand research by Gilovich, Vallone, and Tversky (1985)
- OpenIntro project for the dataset
- Statistical analysis inspired by modern sports analytics methods

## Contact
For questions or collaboration opportunities, please open an issue in the repository.
![Screenshot from 2025-02-10 23-18-49](https://github.com/user-attachments/assets/569dc3ae-f722-4d3f-ac17-07a3e5331fdd)
![Screenshot from 2025-02-10 23-19-07](https://github.com/user-attachments/assets/d9951566-070a-4bbe-8ce4-3e7a7419a2dd)

