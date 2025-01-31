# SMS Spam Detector





## Table of Contents

- [Introduction](#introduction)

- [Features](#features)

- [Installation](#installation)

  - [Prerequisites](#prerequisites)
  - [Clone the Repository](#clone-the-repository)
  - [Install Dependencies](#install-dependencies)
  - [Run the Application](#run-the-application)

- [Usage](#usage)

- [File Structure](#file-structure)

- [Technologies Used](#technologies-used)

- [Contributing](#contributing)

- [Author](#author)

- [Acknowledgments](#acknowledgments)

## Introduction

The **SMS Spam Detector** is a machine learning-based web application that classifies SMS messages as **spam** or **ham** (not spam). It utilizes **TF-IDF vectorization** and **Linear Support Vector Classification (SVC)** for text classification and is deployed using **Gradio**.

## Features

- **Train a model** to classify SMS messages.
- **User-friendly Gradio UI** for easy message classification.
- **Real-time spam detection** through a simple text input.
- **Locally hosted web app** with an option to share publicly.

## Installation

### Prerequisites

Ensure you have **Python 3.10+** and **pip** installed on your system.

### Clone the Repository

```sh
git clone https://github.com/your-username/sms_spam_detector.git
cd sms_spam_detector
```

### Install Dependencies

```sh
pip install -r requirements.txt
```

### Run the Application

```sh
python app.py
```

After running the command, the application will be available locally at:

```sh
Running on local URL: http://127.0.0.1:7860
```

To create a public link, set `share=True` in `launch()`.

## Usage

1. **Enter an SMS message** in the text input field.
2. Click the "Submit" button.
3. The app will classify the message as **spam** or **ham**.

## File Structure

```
├── sms_spam_detector
│   ├── app.py                 # Main application file
│   ├── sms_classification.py   # Model training script
│   ├── SMSSpamCollection.csv   # Dataset
│   ├── README.md               # Documentation
│   ├── requirements.txt        # Required libraries
```

## Technologies Used

- **Python** - Programming language
- **Scikit-learn** - Machine learning library
- **Pandas** - Data manipulation
- **Gradio** - Web interface for ML models

## Contributing

Feel free to fork this repository and submit a pull request with enhancements or fixes.

## Author

Asif Mahmud

---

## Acknowledgments

- [Scikit-learn Documentation](https://scikit-learn.org/)
- [Gradio Documentation](https://www.gradio.app/)
- [Python Official Website](https://www.python.org/)

# sms_spam_detector