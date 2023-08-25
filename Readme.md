# ASL to English Converter

(https://github.com/deepthumar81/ASL-to-English-Converter/assets/125574212/5cfe57ad-d61f-48de-92f2-532be687fdc5)

This project is an ASL (American Sign Language) to English Converter that utilizes various libraries such as Flask, TensorFlow (Keras), NumPy, Pillow (PIL), and Bootstrap. The goal of this project is to convert American Sign Language gestures captured through a camera into corresponding English text.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Demo Video](#demo-video)
- [Technologies Used](#technologies-used)
- [Contributors](#contributors)
- [License](#license)

## Introduction

American Sign Language (ASL) is a vital form of communication for individuals with hearing impairments. This project aims to bridge the communication gap by converting ASL gestures into English text, allowing a seamless interaction between the hearing-impaired and those who communicate using spoken language.

The project utilizes machine learning techniques to recognize and translate ASL gestures, making use of TensorFlow (Keras) to train a model that can classify different gestures.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/deepthumar81/ASL-to-Engliah-Converter.git
   cd ASL-to-Engliah-Converter
   ```

2. Set up a virtual environment (recommended):
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the Flask app:
   ```bash
   python app.py
   ```

2. Open a web browser and navigate to `http://localhost:9000`.

3. Allow camera access if prompted, and start performing ASL gestures in front of the camera.

4. The app will recognize the ASL gesture and display the corresponding English text.

## Demo Video

https://github.com/deepthumar81/ASL-to-English-Converter/assets/125574212/d2dbb7be-98c2-4193-9611-84f513456eef

## Technologies Used

- Flask: Web framework for building the user interface and handling requests.
- TensorFlow (Keras): Machine learning library used to train the ASL gesture recognition model.
- NumPy: Library for numerical computations in Python.
- Pillow (PIL): Python Imaging Library for opening, manipulating, and saving images.
- Bootstrap: Front-end framework for creating responsive and visually appealing web pages.

Feel free to contribute to the project by opening issues or pull requests.
