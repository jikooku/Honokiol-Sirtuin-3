# Honokiol-Sirtuin-3

This writing gives additional information for our manuscript regarding honokiol-mediated hearing protection in Sirtuin 3 knockout mice.

We describe the statistical modeling used to assess auditory brainstem response using various effects.

## Description

The supplementary text contains R commands with some guiding texts
- Preprocess data
- Clean categorical variables
- Fit generalized linear mixed models
- Rank models by AICc
- Evaluate results using ANOVA and pseudo-R² 

Repeated measures were accounted for by random intercepts by subject (`Id`) and we tested different data distributions (Gaussian, Gamma, inverse Gaussian) and link functions.

## Requirements

- R version 4.2.0 +
- Install packages:
  - `lme4`
  - `MuMIn`
  - `performance`
  - `car`
  - `broom.mixed`
  - `tidyverse`

## Access

The code is provided in narrative form within the supplementary file.

Procedures are reproducible following the text, but minor adjustments may be required (e.g. due to different number of frequencies investigated).

## License

This repository is licensed under the MIT License.  
You are free to use, modify, and distribute the contents with appropriate attribution.
