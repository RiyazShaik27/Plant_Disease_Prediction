# Deep Learning-Based Plant Disease Detection An Engineering Project in Community Service (EPICS)

*Username:* RiyazShaik27 <br>
*Name:* Shaik Riyaz <br>
*Email:* shaikriyaz11011@gmail.com <br>
*Repository:* Predicting-Customer-Propensity <br>

---

### Table of Contents

* [Features 🌱](#-Features)
* [Getting Started 🚀](#-Getting-Started)
* [Prerequisites](#-Prerequisites)
* [Installation](#️-Installation)
* [File Structure 📁](#-File-Structure)
* [Model Training and Evaluation 🧠](#-Model-Training-and-Evaluation)
* [Team Contributions](#-Team-Contributions)
* [Individual-Contributions 👨‍💻](#-Individual-Contributions)
* [Acknowledgments 🙏](#-Acknowledgments)

---  

## Features 🌱
**Image-Based Disease Recognition**: Upload an image of a plant to predict potential diseases.

**User-Friendly Interface**: A simple and intuitive web application built with Streamlit.

**Multi-Class Classification**: The model is trained to recognize a wide variety of diseases across multiple plant types.

**Deep Learning Model**: Utilizes a Convolutional Neural Network (CNN) for high-accuracy predictions.

---

## Getting Started 🚀
To get a local copy of the project up and running, follow these simple steps.

---
## Prerequisites

Make sure you have Python installed on your system. This project uses a virtual environment to manage dependencies.

- **Python 3.8+**
- `pip` (Python package installer)

---

## Installation

1. **Clone the repository:**

    ```
    git clone https://github.com/your-username/your-repository-name.git
    cd your-repository-name
    ```
    *(Note: Replace `your-username/your-repository-name` with the actual repository URL)*

2. **Create and activate a virtual environment:**

    ```
    # For Windows
    python -m venv venv
    venv\Scripts\activate

    # For macOS/Linux
    python3 -m venv venv
    source venv/bin/activate
    ```

3. **Install the required packages:**

    ```
    pip install -r requirement.txt
    ```

4. **Run the Streamlit application:**

    ```
    streamlit run main.py
    ```

The application will automatically open in your default web browser.


---

## File Structure 📁
1. **main.py**: The main Streamlit web application file. This is the entry point for the project.

2. **trained_plant_disease_model.keras**: The pre-trained deep learning model used for disease prediction.

3. **Train_plant_disease.ipynb**: A Jupyter Notebook containing the code and process for training the CNN model.

4. **Test_plant_disease.ipynb**: A Jupyter Notebook for testing and evaluating the performance of the trained model.

5. **requirement.txt**: A list of all necessary Python libraries and their versions.

6. **training_hist.json**: A JSON file containing the training history (loss and accuracy) of the model.

7. **home_page.jpeg**: The image used on the home page of the Streamlit application.

---

## Model Training and Evaluation 🧠
The model was trained on a comprehensive dataset of plant images, with details of the training process and evaluation metrics documented in the Train_plant_disease.ipynb and Test_plant_disease.ipynb notebooks. The final model is saved as trained_plant_disease_model.keras.

---

## Team Contributions 👨‍💻
This project was developed as a part of the Engineering Project in Community Service (EPICS) program. The following team members contributed to its successful completion:

| Name                  | Registration No. |
|-----------------------|------------------|
| B Lalith              | 22BAI10060       |
| T.S.Hrushikesh        | 22BAI10076       |
| Adwaith Shyju M       | 22BAI10292       |
| C Vijaya Krishna      | 22BAI110406      |
| Chollangi Chaitanya   | 22BCE11453       |
| Navya Pillai          | 22BCY10001       |
| Shaik Riyaz           | 22BCY10140       |
| Jebaslin H            | 22BOE10104       |
| Teja M                | 22BOE10113       |
| Balaga Bala Krishna   | 22BSA10248       |

## Individual Contributions

- **B Lalith:**
    *Responsible for data collection and preprocessing.*

- **T.S.Hrushikesh:**
   *Contributed to the web application logic and deployment.*

- **Adwaith Shyju M:**
    *Managed project documentation and report writing.*

- **C Vijaya Krishna:**
   *Wrote the code for the CNN model architecture.*

- **Chollangi Chaitanya:**
     *Led the development of the Streamlit user interface.*

- **Navya Pillai:**
    *Managed project documentation and report writing.*

- **Shaik Riyaz:**
    *Assisted with debugging and performance optimization.*

- **Jebaslin H:**
    *Wrote unit tests for the application functions.*

- **Teja M:**
    *Supported with dataset curation and feature engineering.*

- **Balaga Bala Krishna:**
    *Supported with dataset curation and feature engineering.*

---

## Acknowledgments 🙏
We would like to extend our gratitude to the EPICS program at VIT BHOPAL UNIVERSITY for providing us with the opportunity and resources to work on this impactful project.

Enjoy exploring the project!
