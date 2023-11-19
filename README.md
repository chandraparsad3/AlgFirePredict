# AlgFirePredict

AlgFirePredict is an advanced Python-based project designed to predict fire occurrences in Algerian regions, with a specific focus on Bejaia (northeast) and Sidi Bel-abbes (northwest). Utilizing a dataset spanning from June 2012 to September 2012, this sophisticated project employs cutting-edge machine learning techniques to forecast the likelihood of a fire based on a plethora of weather-related features.

## Table of Contents

- [Introduction](#algfirepredict)
- [Dataset Information](#dataset-information)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Dataset Information

The dataset encompasses 244 instances, evenly distributed with 122 instances for each region. It includes 11 attributes related to weather and 1 output attribute indicating whether a fire occurred or not. The variables span from temperature and humidity to indices from the Fire Weather Index (FWI) system, providing a comprehensive set of features for accurate prediction.

### Classes
- "Fire": 138 instances
- "Not Fire": 106 instances

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/chandraparsad3/AlgFirePredict.git
   ```

2. **Navigate to the Project Directory:**
   ```bash
   cd AlgFirePredict
   ```

## Usage

1. **Load the Dataset:**
   Ensure the dataset file (`fire.csv`) is in the project directory.

2. **Build and Evaluate the Model:**
   Utilize the Jupyter notebook (`Algerian_fire.ipynb`) to build and evaluate the machine learning model. Leverage the pre-trained model (`ridge.pkl`) and scaler (`scaler.pkl`) for a streamlined process.
   ```bash
   jupyter notebook Algerian_fire.ipynb
   ```

## Contributing

Contributions are highly encouraged! If you identify a bug or have an innovative idea for an enhancement, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

