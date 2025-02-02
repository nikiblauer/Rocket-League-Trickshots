# Rocket League Trick Shot Classification
![](rocket-league.jpg)

## Task Description

This repository contains a Jupyter Notebook for classifying trick shots in the video game *Rocket League*. The game involves advanced mechanics where players can jump, boost, and execute complex movements to score goals. The dataset used in this project consists of 297 separate trick shots, each containing various in-game metrics recorded at multiple timestamps. 

Each trick shot consists of:
- **Summary statistics** (median values and skew over the entire recorded window)
- **Time-series data** (metrics measured at different timestamps)

### Features in the Dataset
- **BallAcceleration**: The current acceleration of the ball.
- **DistanceWall**: The player's distance to the closest wall.
- **DistanceCar**: The player's distance to the ball.
- **BoostAmount**: Amount of boost available to the player.
- **Throttle, Steer, Jump, Boost, Handbrake**: Inputs from the player.
- **More in-game metrics...**

The goal of this project is to classify the trick shot performed using machine learning techniques.

---

## Installation & Setup

To run the notebook on your local machine, follow these steps:

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2. Create and Activate a Conda Environment
```bash
conda create --name rocket_env python=3.8
conda activate rocket_env
```

### 3. Install Dependencies
```bash
conda install numpy pandas matplotlib scikit-learn jupyter
```

### 4. Run Jupyter Notebook
```bash
jupyter notebook
```
Then open `rocket_classification.ipynb` and run the cells.

---

## Usage

- Load the dataset and explore the available features.
- Preprocess the data (handling missing values, normalization, etc.).
- Train and evaluate classification models.
- Visualize results and interpret model performance.
