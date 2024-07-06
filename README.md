Sure! Here's a README file for your project:

---

# Web Enabled Efficient Tea Leaf Disease Detection System

## Overview

This project aims to develop a web-enabled system for the efficient detection of tea leaf diseases using machine learning. The primary goal is to accurately identify different classes of tea leaf diseases to aid in early detection and treatment, ultimately improving crop yield and quality.

## Objectives

- **Disease Identification:** Use machine learning to identify tea leaf diseases.
- **Data Collection:** Curate a dataset containing images of tea leaves with 7 distinct disease classes.
- **Model Development:** Build and train a Convolutional Neural Network (CNN) model for disease classification.
- **Web Platform:** Develop a user-friendly web application using Flask, allowing users to upload images and receive instant disease classification results.

## Features

- **Image Upload:** Users can upload images of tea leaves through the web interface.
- **Disease Classification:** The system uses a CNN model to classify the uploaded images into one of the 7 disease classes.
- **Results Display:** The classified results are displayed to the user, indicating the identified disease.

## Technologies Used

- **Python:** Programming language for model development and web application.
- **TensorFlow & Keras:** Libraries used to build and train the CNN model.
- **Flask:** Web framework for developing the web application.
- **HTML/CSS:** Technologies for building the front-end of the web application.

## Project Structure

- `app.py`: Main Flask application file.
- `model.py`: Script for building, training, and saving the CNN model.
- `templates/`: Directory containing HTML templates for the web application.
- `static/`: Directory containing static files such as CSS and images.
- `data/`: Directory containing the dataset of tea leaf images.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/tea-leaf-disease-detection.git
    cd tea-leaf-disease-detection
    ```

2. Create and activate a virtual environment:
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Download and prepare the dataset (ensure it is placed in the `data/` directory).

5. Train the CNN model:
    ```bash
    python model.py
    ```

6. Run the Flask application:
    ```bash
    python app.py
    ```

7. Open your web browser and go to `http://127.0.0.1:5000` to use the application.

## Usage

1. Open the web application in your browser.
2. Upload an image of a tea leaf.
3. Click on the "Classify" button.
4. View the classification results displayed on the web page.

## Results

- The CNN model achieved high accuracy in classifying tea leaf diseases.
- The web application provides an easy-to-use interface for users to detect diseases in tea leaves.

## Contributions

Contributions to this project are welcome. Feel free to open issues or submit pull requests for improvements.

## Contact

For any questions or suggestions, please contact Danswrang Basumatary at [dansw222@example.com].

---
