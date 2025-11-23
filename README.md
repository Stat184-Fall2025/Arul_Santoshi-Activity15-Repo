# Activity 15 - GitHub Version Control Practice

**Author:** Arul Santoshi  
**Course:** STAT 184 - Introduction to R  
**Institution:** Penn State University  
**Semester:** Fall 2024

## About This Repository

This repository demonstrates proficiency in Git version control and GitHub collaborative workflows through the completion of Activity 15 for STAT 184. The project showcases proper branching strategies, issue tracking, commit practices, and comprehensive documentation while presenting statistical analyses on military personnel, baby naming trends, and optimization problems.

## Project Overview

This portfolio presents three distinct statistical analyses demonstrating data wrangling, visualization, and interpretation skills:

1. **US Armed Forces Personnel Analysis** - Examines the relationship between sex and rank among enlisted Army personnel using frequency table analysis
2. **Baby Names Trends** - Explores the popularity of classic literary names (Elizabeth, Jane, Emma, Charlotte, Margaret) from 1880 to 2014
3. **Box Volume Optimization** - Solves an optimization problem to maximize the volume of an open-top box constructed from a rectangular sheet of paper

### Research Questions

- Are sex and rank independent variables among US Army enlisted personnel?
- How have naming preferences for classic literary names evolved over 135 years?
- What cutout size maximizes the volume of a box made from a 36" × 48" sheet?

## Data Sources

### Primary Dataset: US Armed Forces Active Duty Personnel
- **Source:** Google Sheets (publicly accessible)
- **URL:** [Armed Forces Data](https://docs.google.com/spreadsheets/d/19xQnI1cBh6Jkw7eP8YQuuicMlVDF7Gr-nXCb5qbwb_E/edit?gid=597536282#gid=597536282)
- **Description:** Active-duty personnel counts by service branch, sex, and pay grade as of June 2025
- **Variables:** Pay Grade, Branch (Army, Navy, Marine Corps, Air Force, Space Force), Sex (Male, Female), Count

### Secondary Dataset: Baby Names Historical Data
- **Source:** dcData R package (BabyNames dataset)
- **Access:** `library(dcData); data("BabyNames")`
- **Description:** Historical baby name data for the United States from 1880 to 2014
- **Variables:** name, sex, year, count

### Mathematical Model: Box Volume Function
- **Type:** Derived mathematical function
- **Function:** V(x) = x(48 - 2x)(36 - 2x) where x is the side length of square cutouts in inches
- **Domain:** 0 < x < 18

## Repository Organization

```
Arul_Santoshi-Activity15-Repo/
├── README.md                 # This file - comprehensive project overview
├── PLAN.md                   # Detailed project and repository management plans
├── Activity15.qmd           # Quarto source file with complete analysis
├── Activity15.pdf           # Rendered PDF output document
└── .gitignore              # Git ignore rules for R projects
```

## Current Project Status

### Completed Tasks
- [x] Repository setup and initialization
- [x] Created and managed multiple GitHub issues
- [x] Implemented branching strategy (main and development branches)
- [x] Statistical analysis completed in QMD format
- [x] PDF output generated successfully
- [x] Comprehensive documentation finalized
- [x] Pull requests created and merged
- [x] All issues closed

### Project Timeline
- **Week 1:** Repository setup, data acquisition, initial analysis
- **Week 2:** Complete statistical analyses, create visualizations
- **Week 3:** Documentation, quality assurance, final submission

For detailed project planning information, see [PLAN.md](PLAN.md).

## How to Reproduce This Analysis

### Prerequisites
- R (version 4.0 or higher)
- RStudio
- Quarto
- Required R packages: tidyverse, googlesheets4, knitr, dcData

### Steps to Reproduce

1. **Clone the repository:**
   ```bash
   git clone https://github.com/YOUR-USERNAME/Arul_Santoshi-Activity15-Repo.git
   cd Arul_Santoshi-Activity15-Repo
   ```

2. **Install required R packages:**
   ```r
   install.packages(c("tidyverse", "googlesheets4", "knitr", "dcData"))
   ```

3. **Open the QMD file:**
   - Launch RStudio
   - Open `Activity15.qmd`
   - All file paths are relative and should work without modification

4. **Render the document:**
   - Click the "Render" button in RStudio, or
   - Run in R console: `quarto::quarto_render("Activity15.qmd")`

5. **View the output:**
   - The rendered PDF will be saved as `Activity15.pdf`

## Version Control Features Demonstrated

This repository showcases professional Git and GitHub practices:

### Branching Strategy
- **main branch:** Stable, production-ready code
- **development branch:** Active development work and feature additions

### Issue Tracking
- Issue #1: Complete Activity 15 analysis and documentation
- Issue #2: Set up repository structure and documentation
- Issues properly labeled and referenced in commits
- Issues closed via pull request merges

### Commit Practices
- Multiple meaningful commits with descriptive messages
- Commits follow best practices: "If applied, this commit will..."
- All commits reference relevant issue numbers
- Clear commit history showing project progression

### Pull Request Workflow
- Pull requests include detailed descriptions
- Changes reviewed before merging
- Issues automatically closed upon merge
- Clean merge history maintained

## Technologies and Tools Used

**Programming and Analysis:**
- R (version 4.x)
- RStudio IDE
- Quarto for reproducible documents

**Version Control:**
- Git for version control
- GitHub for remote repository hosting
- GitHub Desktop for GUI-based Git operations

**R Packages:**
- `tidyverse` - Data manipulation and visualization
- `ggplot2` - Advanced graphics and plotting
- `googlesheets4` - Google Sheets API access
- `knitr` - Dynamic report generation
- `dcData` - Educational datasets

## Coding Style

This project follows the **Tidyverse Style Guide** for all R code:
- Consistent naming conventions (snake_case for variables and functions)
- Proper indentation and spacing
- Meaningful variable and function names
- Comprehensive code comments
- Style guide reference: https://style.tidyverse.org/

## Key Findings

### Analysis 1: Sex and Rank in the US Armed Forces
Sex and rank are **not independent** among Army enlisted personnel. Female representation varies across ranks (12.1% at E9 to 18.9% at E3), suggesting systematic differences in career progression and retention between sexes.

### Analysis 2: Baby Names Trends
Classic literary names show diverse popularity patterns over 135 years:
- **Emma** experienced dramatic resurgence starting in the 1990s
- **Elizabeth** maintained consistent high popularity across generations
- **Margaret** and **Jane** followed peak-and-decline patterns
- **Charlotte** shows recent upward trend

### Analysis 3: Box Volume Optimization
The optimal square cutout size is approximately **6 inches**, yielding a maximum box volume of **5,184 cubic inches**. This demonstrates the practical application of calculus and optimization theory to real-world design problems.

## Contact Information

**Arul Santoshi**  
Penn State University  
Data Science  
STAT 184
Email: ajs10266@psu.edu
GitHub: Arul-Santoshi

## Acknowledgments

- STAT 184 course instruction and materials
- Tidyverse and Quarto development teams
- dcData package authors

## License

This project is submitted as coursework for STAT 184 at Penn State University. All analysis and code are original work by Arul Santoshi under MIT License.

---

**Repository Link:** https://github.com/YOUR-USERNAME/Arul_Santoshi-Activity15-Repo  
**Last Updated:** November 22, 2024  
**Status:** Complete
