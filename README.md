# Student Alcohol Consumption

This repository contains an analysis of student alcohol consumption data from two Portuguese schools. The goal is to explore the factors associated with alcohol consumption among students, using data analysis techniques and machine learning models.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview

The **Student Alcohol Consumption** project aims to explore the relationship between various social, demographic, and academic factors and alcohol consumption levels among students. Using data analysis and machine learning, we predict alcohol consumption patterns.

## Dataset

The dataset used in this project is sourced from the UCI Machine Learning Repository. It includes features like:

- **School**: student's school (binary: "GP" - Gabriel Pereira, "MS" - Mousinho da Silveira)
- **Sex**: gender of the student (binary: "F" - female, "M" - male)
- **Age**: student's age (numeric: from 15 to 22)
- **Family Size**: size of the student's family (binary: "LE3" if <=3, "GT3" if >3)
- **Parents' Status**: cohabitation status of parents (binary: "T" - together, "A" - apart)
- **Weekday/Weekend Alcohol Consumption**: levels of alcohol consumption during weekdays and weekends (ordinal: from 1 - very low to 5 - very high)

The dataset can be accessed from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Student+Alcohol+Consumption).

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/ambati-chaitanya/Student-Alcohol-Consumption.git
    ```

2. **Navigate to the project directory**:
    ```bash
    cd Student-Alcohol-Consumption
    ```

3. **Install the dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Exploratory Data Analysis**:
   Open the Jupyter notebook to explore the data and visualize the trends:
   ```bash
   jupyter notebook analysis.ipynb

##  Project Stucture

Student-Alcohol-Consumption/
│
├── data/                      # Dataset folder (not included in the repository)
├── analysis.ipynb              # Jupyter notebook for EDA and visualizations
├── ml_model.py                 # Machine learning model training and testing
├── requirements.txt            # Python dependencies
├── README.md                   # Project documentation
└── visuals/                    # Generated plots and visualizations

## Contributing

Contributions are welcome! To contribute, follow these steps:

1. Fork the repository.
2. Create a new feature branch (git checkout -b feature-branch).
3. Commit your changes (git commit -m 'Add new feature').
4. Push to the branch (git push origin feature-branch).
5. Open a Pull Request.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

### Instructions for Uploading to GitHub

1. Create a file called `README.md` in the root of your repository.
2. Paste the above content into the `README.md` file.
3. Commit and push your changes to GitHub:
    ```bash
    git add README.md
    git commit -m "Add README file"
    git push origin main
    ```

This will add the `README.md` file to your GitHub repository, providing clear documentation for anyone accessing the project.
