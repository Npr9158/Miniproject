# PSY6422_Mini-project

### Overview

This project is an mini-project assignment for the PSY6422 module.

This mini-project analyses the relationship between time spent in nature and mental health, whether 'connection to nature' holds an influence over the effect, and potential gender differences.

Data was used from [Haywood and Stiller (2024)](https://openpsychologydata.metajnl.com/articles/10.5334/jopd.122) data paper, and the aforementioned variables were chosen to run the final analysis for this mini-project. Raw data and code book can be accessed through the paper.

The final visualization is an animated scatterplot that shows that more time spent in nature was correlated to higher mental health scores.

![Final visualization](miniproject_animated_graph.gif)

The analysis is written in R using Quarto to produce a fully reproducible, self-contained HTML report.

**Key features**

-   Data cleaning and wrangling using tidyverse and naniar packages.

-   Interactive visualization using ggplot2 and plotly

-   Animating and converting to gif format using gganimate and gifski

-   Reproducible reporting via Quarto

### Repository Structure

-   data/: Contains raw data used for analysis (connection_to_nature_data.csv)

-   PSY6422_Miniproject_250197565.qmd : Main Quarto document containing analysis, narrative and visualization

-   PSY6422_Miniproject_250197565.html : Rendered output file (viewable in browser)

-   miniproject_animated_graph.gif : Final visualization as an animated scatterplot

### Prerequisites

To reproduce this analysis, you will need the following installed:

-   tidyverse

-   naniar

-   ggplot2

-   plotly

-   gganimate

-   gifski
