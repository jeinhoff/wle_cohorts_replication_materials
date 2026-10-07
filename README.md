# Cohorts' Working Life Expectancies and Working Years Lost in 21 European Countries

Replication materials for the paper "Cohorts' Working Life Expectancies and Working Years Lost in 21 European Countries" by Jan Einhoff.

## Code

- `01_preprocessing.Rmd`: preparation of the EU-LFS data
- `02_sample.Rmd`: survival rates (HMD) and sample restrictions
- `03_estimation.Rmd`: working life expectancies and working years lost
- `04_figures.Rmd`: Figures 1–5 and A1–A5
- `05_regressions.Rmd`: Table 1
- `06_descriptives.Rmd`: Tables A3–A6 and Figures A6–A17

The scripts read data from `data/` and write results to `outputs/`. They require R 4.1 or later and the packages `tidyverse` (dplyr 1.1.0 or later), `ggh4x`, `openxlsx` and `ggflags` (github.com/jimjam-slam/ggflags).

## Data

The EU-LFS microdata (1983–2021, release 2022) can be requested from Eurostat and cannot be shared. The yearly files are expected in `data/eurostat/`. The cohort death rates (`cMx_1x1`) are available from the Human Mortality Database (www.mortality.org) and are expected in `data/hmd/`.

## Contact

Jan Einhoff, einhoff@demogr.mpg.de
