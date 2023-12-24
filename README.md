
# Car Evaluation ML (7th SEMESTER PROJECT)
Machine learning project using a random forest classifier to predict car acceptability.

This repository contains the code for a machine learning model that can evaluate the condition of a car based on certain features.

## Problem

The problem this project aims to solve is to predict the condition of a car based on certain features such as buying price, maintenance price, number of doors, number of seats, luggage boot size, and safety rating.

## Solution

We have developed a machine learning model that can predict the condition of a car based on the features mentioned above. The model has been trained on a dataset of cars with known conditions, and it has achieved an accuracy of 95%.

## Dependencies

The following dependencies are required to run the program:

- Python 3.6 or higher
- Pandas
- Scikit-learn

## Usage

To use the program, you need to provide a CSV file with the following columns:

- buying_price
- maintenance_price
- number_of_doors
- number_of_seats
- luggage_boot_size
- safety_rating

The program will output a CSV file with the predicted condition of each car.

You can run the program by executing the following command:

```
python main.py input_file.csv output_file.csv
```

## Contributing

If you'd like to contribute to this project, please fork the repository and create a new branch. You can then make your changes and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
