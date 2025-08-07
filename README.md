# Kali AutoML Engine

A user-friendly desktop application built with Python, Tkinter, and PyCaret for automating machine learning tasks on Kali Linux, with a focus on cybersecurity use cases.

## Features:

*   **Load Dataset**: Easily load data from a CSV file.
*   **Select Target Variable**: Choose the column you want to predict.
*   **Choose ML Task**: Select between Classification and Regression tasks.
*   **Run AutoML**: Automatically train and compare multiple machine learning models using PyCaret.
*   **View Results**: Display detailed performance metrics and the best model found.

## Requirements:

*   Python 3.x
*   Kali Linux (or another Linux distribution with a graphical environment)
*   The following Python libraries:
    *   `pycaret`
    *   `pandas`
    *   `tk` (usually included with Python, but may need to be installed separately depending on your system)

## Installation:

1.  **Install Python 3** (if not already installed):
    *(Instructions for installing Python 3 vary by distribution, e.g., `sudo apt update && sudo apt install python3` on Debian/Ubuntu)*
2.  **Install required Python libraries**:

```bash
pip install pycaret pandas tk
```

3.  **Save the code**: Save the application code (the original Python script) as a Python file, for example, `automl_app.py`.
4.  **Run the application**: Open a terminal in the directory where you saved the file and run:

```bash
python3 automl_app.py
```

## Usage:

1.  **Load Data**: Click the "Load CSV File..." button to select your dataset.
2.  **Select Target**: Choose the column you want to predict from the dropdown menu.
3.  **Choose Task**: Select "Classification" or "Regression" based on your problem.
4.  **Run AutoML**: Click "Start AutoML Experiment" to train models.
5.  **View Results**: The results and best model information will appear in the text area.

## Cybersecurity Use Cases:

This application is particularly useful for automating ML tasks in cybersecurity, such as:

*   Malware classification based on file features.
*   Network intrusion detection based on traffic data.
*   Spam filtering based on email content/headers.
*   Predicting vulnerability scores for systems.

## Note:

This is a desktop application and requires a graphical environment to run. It cannot be run directly within environments like Google Colab that lack a display.
