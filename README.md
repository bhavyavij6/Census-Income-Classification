# Census Income Classification

A machine learning project to predict income levels based on the 1994 U.S. Census data.

## Introduction

The income dataset was extracted from the 1994 U.S. Census database.

### The Importance of Census Statistics

The census is a special, wide-range activity that takes place once a decade across the entire country. It gathers information about the general population to present a full and reliable picture of the population's housing conditions and demographic, social, and economic characteristics. This information helps plan better services, improve the quality of life, and solve existing problems. It also serves as the basis for constructing planning forecasts, essential for the democratic process by enabling citizens to examine governmental and local decisions.

## Objective

The goal of this machine learning project is to predict whether a person makes over $50K a year given their demographic variation. To achieve this, several classification techniques are explored, with the random forest model yielding the best prediction result.

## Features Description

### Categorical Attributes
- **workclass**: Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked.
- **education**: Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool.
- **marital-status**: Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse.
- **occupation**: Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces.
- **relationship**: Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried.
- **race**: White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black.
- **sex**: Female, Male.
- **native-country**: United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands.

### Continuous Attributes
- **age**: Age of an individual
- **fnlwgt**: Final weight
- **capital-gain**: Capital gain
- **capital-loss**: Capital loss
- **hours-per-week**: Working hours per week

## Tech Stack

- **Programming Language**: Python
- **Libraries**:
  - **Data Processing**: Pandas, NumPy
  - **Data Visualization**: Matplotlib, Seaborn
  - **Machine Learning**: Scikit-learn (Random Forest, Logistic Regression, etc.)
  - **Model Evaluation**: Scikit-learn (cross-validation, metrics)

## Project Structure

- `Census_Income_Harsha_ADV.ipynb`: Jupyter notebook containing the project code and analysis.
- `data/`: Directory containing the dataset used for the project.

## How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/Census-Income-Classification.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Census-Income-Classification
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Open and run the Jupyter notebook:
    ```bash
    jupyter notebook Census_Income_Harsha_ADV.ipynb
    ```

## Results

- Summary of the results and key findings from the project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
