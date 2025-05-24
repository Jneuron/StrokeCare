# StrokeCare: MATLAB-based Stroke Risk Evaluation System

This project provides a user-friendly MATLAB program for assessing stroke risk based on DALY data from the GBD 2021 China dataset.

## Features

- Multi-user input system for stroke risk assessment
- Personalized health reports based on user data (age, gender, SBP, BMI, smoking status)
- Data visualization of stroke burden by age and sex
- Data preprocessing pipeline included (`generateCleanedData.m`)

## Files

| File                               | Description                                        |
|------------------------------------|----------------------------------------------------|
| `StrokeCare.m`                     | Main function for risk assessment and reporting   |
| `RunStrokeCare.m`                  | Script to launch the StrokeCare program easily    |
| `generateCleanedData.m`            | Script for cleaning and preparing GBD data        |
| `chinastrokeDaly2021BySexCleaned.csv` | Cleaned dataset used in the project             |
| `userDataAll.mat` (not generated)       | Saved user data for multiple sessions             |

## How to Use

1. Run `RunStrokeCare.m` to start the program.
2. Follow the prompts in the MATLAB Command Window to provide user information.
3. The program will generate a text report and a visualization of stroke risk.
4. To clean the data yourself, run `generateCleanedData.m` before using `StrokeCare.m`.

## License

MIT License.

By Neuron | 2025
