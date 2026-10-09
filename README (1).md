# After Dark on a Country Road: Australian road deaths, 1989 to 2021

A data visualisation project that asks whether the 70 per cent fall in Australian road deaths
was shared evenly, or whether progress stalled in particular places and times.

**Live interactive dashboard:** https://shaplaakter.shinyapps.io/road-fatalities/

## What is in this repository
| File | Description |
|---|---|
| [`Data_story.pdf`](Data_story.pdf) | The finished data story: six figures and the narrative around them |
| [`annotated_code.qmd`](annotated_code.qmd) | The R code behind all six figures, with comments explaining each step |

## The six figures
1. Filled line chart: national fatality trend
2. Calendar heatmap: year by month pattern
3. Slope chart: state comparison, 1989 vs 2021
4. Stacked bar chart: time slot and crash type
5. Lollipop chart: road user totals
6. Diverging bar chart: age group and gender

## Tools
R, ggplot2, dplyr, tidyr, forcats, scales, ggrepel, Quarto, Shiny.

## Data
Australian Road Deaths Database 1989 to 2021, Bureau of Infrastructure and Transport Research
Economics (BITRE), accessed through Kaggle. The data file is not included here. To rerun the code,
download it from Kaggle, save it as `Crash_Data.csv` next to the `.qmd` file, and set
`eval: true` in the file header.

## Author
Shapla Akter, Master of Data Science, Adelaide University.
