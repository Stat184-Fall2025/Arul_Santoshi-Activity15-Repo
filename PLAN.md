# Project and Repository Management Plan

**Repository:** Arul_Santoshi-Activity15-Repo  
**Author:** Arul Santoshi  
**Course:** STAT 184 - Introduction to R  
**Date:** November 22, 2024

---

# Part 1: Activity 15 Project Plan

## Goals

**Primary Goal:** Complete a comprehensive statistical portfolio demonstrating data wrangling, visualization, and interpretation skills across three distinct analyses.

**Secondary Goals:**
- Create professional, accessible visualizations with proper captions and alt text
- Produce clear narrative explanations of statistical findings
- Ensure complete reproducibility of all analyses

**Tertiary Goals:**
- Demonstrate proper coding style (Tidyverse) throughout
- Apply statistical concepts to real-world datasets
- Build portfolio piece showcasing technical skills

## Needs

### Data Requirements
1. **US Armed Forces Personnel Data** - Google Sheets dataset with personnel counts by branch, sex, and pay grade
2. **Baby Names Historical Data** - dcData R package (BabyNames dataset, 1880-2014)
3. **Box Optimization Model** - Mathematical function V(x) = x(48-2x)(36-2x)

### Software and Tools
- **R & RStudio** - Statistical computing and IDE
- **Quarto** - Document rendering system
- **Git/GitHub** - Version control
- **R Packages:** tidyverse, googlesheets4, knitr, dcData

### Knowledge and Skills
- Data wrangling with tidyverse (pivoting, filtering, grouping, summarizing)
- ggplot2 visualization (lines, functions, themes, accessibility features)
- Statistical interpretation (independence testing, time series, optimization)
- Quarto document creation with proper YAML, chunk options, and formatting

### Resources
- STAT 184 course materials
- Tidyverse documentation: https://www.tidyverse.org/
- Quarto documentation: https://quarto.org/
- Tidyverse Style Guide: https://style.tidyverse.org/

## Steps

### Phase 1: Data Acquisition and Exploration (Days 1-2)
1. Install all required R packages
2. Access Google Sheets Armed Forces dataset via googlesheets4
3. Load BabyNames dataset from dcData package
4. Examine data structures and identify any cleaning needs
5. Document data sources and verify data quality

### Phase 2: Data Wrangling (Days 2-3)
1. **Armed Forces:** Clean columns, remove summary rows, reshape wide to long, create derived variables (Category, Rank)
2. **Baby Names:** Filter to five literary names, aggregate by name and year
3. **Box Function:** Define volume function with proper domain constraints
4. Verify data integrity with validation checks

### Phase 3: Analysis and Visualization (Days 3-4)
1. Create frequency table for Army enlisted personnel by sex and rank
2. Generate time series plot for baby name trends with color-blind friendly palette and multiple line types
3. Plot box volume function showing optimization curve
4. Add all required chunk options: labels, fig-cap, fig-alt, tbl-cap

### Phase 4: Interpretation and Writing (Days 4-5)
1. Analyze frequency table for evidence of independence between sex and rank
2. Describe temporal patterns in baby name popularity and cultural influences
3. Explain optimization problem, identify maximum volume point, discuss trade-offs
4. Write clear narrative text with proper headers and section structure

### Phase 5: Documentation and Quality Assurance (Days 5-6)
1. Organize code with descriptive labels, comments, and consistent style
2. Create manual code appendix showing all analysis code
3. Configure YAML header with title, author, date, PDF output, toc, number-sections
4. Test rendering from clean environment to ensure reproducibility
5. Proofread all narrative text for clarity and errors

---

# Part 2: Repository Setup and Maintenance Plan

## Goals

**Primary Goal:** Demonstrate mastery of Git version control and GitHub workflows through proper branching, commits, issues, and pull requests.

**Secondary Goals:**
- Maintain clear, organized repository structure
- Create comprehensive documentation (README, PLAN)
- Showcase professional development practices

**Tertiary Goals:**
- Practice collaborative workflows with branches and PRs
- Build reusable template for future projects
- Create portfolio evidence of technical proficiency

## Needs

### Technical Requirements
- Git installed locally
- GitHub account with repository access
- GitHub Desktop (optional, for GUI-based operations)
- Understanding of: commit, branch, merge, push, pull

### Repository Standards
- Clear naming: `Arul_Santoshi-Activity15-Repo`
- Appropriate .gitignore for R projects
- README covering: project overview, data sources, current plan, organization, contact info
- PLAN covering: both project AND repository plans with Goals, Needs, and Steps

### Workflow Requirements
- **Branching:** Main (stable) + development (active work)
- **Issues:** At least 2 issues, properly labeled, referenced in commits, closed via PRs
- **Commits:** Meaningful messages in present tense, reference issue numbers
- **Pull Requests:** Detailed descriptions, reviews before merging

## Steps

### Phase 1: Initial Setup
1. **Create repository on GitHub.com:**
   - Name: `Arul_Santoshi-Activity15-Repo`
   - Visibility: Public
   - Initialize with README and R .gitignore

2. **Clone repository locally:**
   - Use GitHub Desktop: File → Clone repository
   - Local path: `C:\Users\asant\OneDrive - The Pennsylvania State University\STAT184\`

3. **Create issues on GitHub:**
   - Issue #1: "Complete Activity 15 Analysis and Documentation" (labels: enhancement, documentation)
   - Issue #2: "Set up repository structure and documentation" (label: documentation)

### Phase 2: Development Workflow
1. **Create development branch:**
   - GitHub Desktop: Current Branch → New Branch → "development"
   - Publish branch to GitHub

2. **Add analysis files:**
   - Copy Activity15.qmd to repo folder
   - Render in RStudio to generate Activity15.pdf

3. **Commit analysis files:**
   - Commit 1: `Add Activity 15 QMD file with complete analysis - addresses #1`
   - Commit 2: `Add rendered PDF output - closes #1`
   - Push to GitHub

4. **Create and merge first PR:**
   - Title: "Add Activity 15 analysis files"
   - Description: Details what's included, "Closes #1"
   - Merge to main branch

### Phase 3: Documentation
1. **Stay on development branch** (or switch back to it)

2. **Add documentation files:**
   - Create README.md with all required sections
   - Create PLAN.md with both project and repo plans

3. **Commit documentation:**
   - Commit: `Add comprehensive documentation - closes #2`
   - Push to GitHub

4. **Create and merge second PR:**
   - Title: "Add comprehensive documentation"
   - Description: Details documentation added, "Closes #2"
   - Merge to main branch

### Phase 4: Final Verification
1. **Verify on GitHub.com:**
   - README displays on main page
   - All files present: QMD, PDF, README, PLAN
   - Both issues closed
   - Two merged pull requests
   - Multiple meaningful commits
   - Main branch up-to-date

2. **Test reproducibility:**
   - Clone to fresh location
   - Open QMD in RStudio and render
   - Verify all paths work correctly

---

# Timeline

**Week 1:** Repository setup, issue creation, data acquisition, initial wrangling  
**Week 2:** Complete analyses, create visualizations, write interpretations  
**Week 3:** Documentation, quality assurance, final verification, submission

---

# Success Criteria

## Project Success
✅ All three analyses complete with clear findings  
✅ Professional visualizations with proper accessibility features  
✅ Clean, reproducible code following Tidyverse style  
✅ PDF renders without errors  

## Repository Success
✅ All rubric elements demonstrate proficiency  
✅ Clear commit history showing project progression  
✅ Issues properly tracked and closed  
✅ Comprehensive documentation (README and PLAN)  
✅ Professional Git/GitHub workflow practices  
