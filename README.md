# Student Performance Analysis and Prediction

This project analyzes student performance data from quizzes and tests to identify weak topics, track improvement trends, generate personalized recommendations, and predict future performance using machine learning.

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)


## Project Overview

The project utilizes data from past and current student tests to:

- Calculate overall test accuracy.
- Identify weak topics where the student frequently makes mistakes.
- Analyze trends in accuracy and speed over time.
- Generate personalized recommendations for improvement.
- Build a machine learning model to predict future accuracy based on past performance.


## Data Sources

The project uses JSON data from the following sources:

- **Current Test Data:** `current_test_url = "https://jsonkeeper.com/b/LLQT"`
- **Overall Test Data:** `overall_test_url = "https://api.jsonserve.com/rJvd7g"`
- **Past Tests Data:** `past_tests_url = "https://api.jsonserve.com/XgAgFJ"`


## Dependencies

The project requires the following Python libraries:

- `requests`
- `numpy`
- `pandas`
- `datetime`
- `sklearn`
- `matplotlib`


You can install them using `pip`:

3. Run the Colab notebook:
   Open the `student_performance_analysis.ipynb` notebook in Google Colab and run all cells.



## Results

The project provides the following outputs:

- Overall test accuracy.
- List of weak topics with mistake percentages.
- Personalized recommendations for improvement.
- Model performance metrics (Mean Absolute Error, R^2 Score).
- Visualizations of accuracy and speed trends, topic-wise performance, and accuracy distribution.



## Contributing

Contributions are welcome! Please open an issue or submit a pull request.


## License

This project is licensed under the [MIT License](LICENSE).
