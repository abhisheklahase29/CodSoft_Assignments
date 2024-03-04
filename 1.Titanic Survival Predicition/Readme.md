

# Titanic Survival Prediction

This project aims to predict the survival of passengers aboard the Titanic using machine learning techniques. The dataset used for this analysis contains information about passengers such as their age, gender, class, fare, and whether they survived the disaster or not.

## Table of Contents

- [Dataset Description](#dataset-description)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Dataset Description

The dataset used for this project is sourced from [Kaggle](https://www.kaggle.com/c/titanic/data) and contains the following columns:

- PassengerId: Unique identifier for each passenger
- Survived: Whether the passenger survived (0 = No, 1 = Yes)
- Pclass: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- Name: Passenger's name
- Sex: Passenger's gender
- Age: Passenger's age
- SibSp: Number of siblings/spouses aboard
- Parch: Number of parents/children aboard
- Ticket: Ticket number
- Fare: Ticket fare
- Cabin: Cabin number
- Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Installation

To run this project locally, you need to have Python installed. Clone this repository to your local machine:

```bash
git clone https://github.com/abhisheklahase29/titanic-survival-prediction.git
```

Then navigate to the project directory and install the required dependencies using pip:

```bash
cd titanic-survival-prediction
pip install -r requirements.txt
```

## Usage

After installing the dependencies, you can run the project using Jupyter Notebook or any Python IDE. The main file is `titanic_survival_prediction.ipynb`. This notebook contains the code for data preprocessing, model training, and evaluation.

## Results

The project uses logistic regression for prediction and achieves an accuracy score of approximately 100% on the test data.

## Contributing

Contributions to this project are welcome. To contribute, please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add feature'`)
5. Push to the branch (`git push origin feature`)
6. Create a new Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
