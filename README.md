# SPFL Manager Survival Analysis

Kaplan-Meier and Cox Proportional Hazards survival analysis of managerial 
tenure across Scottish Premiership clubs from 2000 onwards.

## Overview
- Manually compiled dataset of 174 permanent managerial spells from Transfermarkt
- Kaplan-Meier survival curves overall and by departure reason
- Cox Proportional Hazards model estimating effects of PPG, matches in charge, and dismissal type
- Median managerial tenure identified as 460 days (~15 months)

## Key Findings
- Managers who resigned survived nearly twice as long as those sacked (707 vs 368 days)
- Tenure momentum is the strongest predictor of survival — longer serving managers face dramatically lower ongoing risk
- PPG shows no significant effect on tenure length

## Libraries
pandas, numpy, matplotlib, statsmodels

## Data
Manually compiled from Transfermarkt.co.uk
