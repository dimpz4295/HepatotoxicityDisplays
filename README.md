---
title: "Hepatotoxicity White Paper"
output: md_document
date: "2025-07-13"
editor_options: 
  markdown: 
    wrap: 72
---

### [📊 Recommended Displays Associated with Hepatotoxicity Phase 2-4 Clinical Trials]{.underline}

#### [**📌 Description**]{.underline}

This R project is the development of an open-source tool and package to
enable generation of recommended interactive plots and tables for
clinical review and direct inclusion in submission for regulatory
agencies. These plots and tables are recommended displays associated
with hepatotoxicity phase 2-4 clinical trials.

#### [**📁 Project Structure**]{.underline} 

```         
/sourcedata # Raw and processed source data files 
/scripts    # R scripts for data processing and analysis 
/apps       # Shiny application source code 
/outputs    # Generated outputs like plots, reports 
README.md   # Project documentation
```

#### [**📦 Dependencies**]{.underline}

R version: \>= 4.1.0

Key Packages:

``` r
install.packages(c( "dplyr", "tern", "random.cdisc.data", "tidyverse", "magrittr", "formatters", "grid", "shiny", "plotly", "ggvis", "patchwork", "ggprism", "maditr", "gridExtra", "utile.visuals", "flextable", "cowplot", "sciplot", "DT", "gt", "rtables", "r2rtf", "rlang", "pdftools", "forestly", "ggrepel", "tidyr", "ggplot2" ))
```

#### [**🚀 Installation**]{.underline}

1.  Clone this repository:

git clone <https://github.com/dimpz4295/HepatotoxicityDisplays.git>

2.  Open R or RStudio and set the working directory:

setwd("<path-to-your-project>")

3.  Install required R packages listed in the Dependencies section.

#### [**📊 Example Output**]{.underline}

Screenshots are available for the following programs:

[Table 1: Overview of Reported Potential Liver Safety
Findings]{.underline}

![](Table1%20Screenshot.png)

[Figure 1: Plot of Maximum Total Bilirubin Versus Maximum
ALT]{.underline}

![](Figure%201%20Screenshot.png)

#### [**🧾 Documentation**]{.underline}

Full documentation is provided via in-code comments in the program code.

#### [📚References / Citations]{.underline}

-   **dplyr**: <https://dplyr.tidyverse.org/>

-   **tern**: <https://insightsengineering.github.io/tern/>

-   **random.cdisc.data**:
    <https://insightsengineering.github.io/random.cdisc.data/>

-   **tidyverse**: <https://www.tidyverse.org/>

-   **magrittr**:
    <https://cran.r-project.org/web/packages/magrittr/index.html>

-   **formatters**: <https://insightsengineering.github.io/formatters/>

-   **grid**:
    <https://stat.ethz.ch/R-manual/R-devel/library/grid/html/00Index.html>

-   **shiny**: <https://shiny.rstudio.com/>

-   **plotly**: <https://plotly.com/r/>

-   **ggvis**: <https://ggvis.rstudio.com/>

-   **patchwork**: <https://patchwork.data-imaginist.com/>

-   **ggprism**: <https://csdaw.github.io/ggprism/>

-   **maditr**:
    <https://cran.r-project.org/web/packages/maditr/index.html>

-   **gridExtra**:
    <https://cran.r-project.org/web/packages/gridExtra/index.html>

-   **utile.visuals**:
    <https://github.com/insightsengineering/utile.visuals>

-   **flextable**: <https://davidgohel.github.io/flextable/>

-   **cowplot**: <https://wilkelab.org/cowplot/>

-   **sciplot**:
    <https://cran.r-project.org/web/packages/sciplot/index.html>

-   **DT**: <https://rstudio.github.io/DT/>

-   **gt**: <https://gt.rstudio.com/>

-   **rtables**: <https://insightsengineering.github.io/rtables/>

-   **r2rtf**: <https://github.com/ganalytics/r2rtf>

-   **rlang**: <https://rlang.r-lib.org/>

-   **pdftools**:
    <https://cran.r-project.org/web/packages/pdftools/index.html>

-   **forestly**: <https://insightsengineering.github.io/forestly/>

-   **ggrepel**: <https://ggrepel.slowkow.com/>

-   **tidyr**: <https://tidyr.tidyverse.org/>

-   **ggplot2**: <https://ggplot2.tidyverse.org/>

#### [**📜 License**]{.underline}

Distributed under the MIT License. See the LICENSE file for details.

#### [👩‍💻 Author]{.underline}

Dimple Patel

GitHub: @dimpz4295
