# 📊 TOPSIS Project Suite

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![PyPI](https://img.shields.io/badge/PyPI-Package-green?style=for-the-badge&logo=pypi&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

## 👨‍💻 Submitted By
**Name:** Devansh Chhabra  
**Roll Number:** 102317041  
**Subject:** Predictive Analysis (UCS654)

---

## 📝 Project Overview
This repository serves as the central hub for the TOPSIS (Technique for Order of Preference by Similarity to Ideal Solution) assignment. The project is divided into three distinct components, ranging from a basic Python implementation to a full-fledged web service.

### 📂 Submission Components

| Part | Component Name | Description | Repository Link |
| :---: | :--- | :--- | :---: |
| **I** | **CLI Implementation** | The core Python script to perform TOPSIS on local CSV files via command line. | [View Repo](https://github.com/Devansh-Chhabra/TOPSIS-Implementation) |
| **II** | **PyPI Library** | A publicly published Python package allowing anyone to install and use this tool. | [View Repo](https://github.com/Devansh-Chhabra/TOPSIS-PyPi-Package) |
| **III** | **Web Service** | A web application where users upload data and receive ranked results via email. | [View Repo](https://github.com/Devansh-Chhabra/TOPSIS-WEB-SERVICE) |

---

## 🚀 Component Details

### 1️⃣ Part I: Command Line Interface (CLI)
A robust python script that takes input data, weights, and impacts to calculate the TOPSIS score and rank.
* **Input:** CSV file with numerical data.
* **Validation:** Handles file not found, wrong parameter counts, and non-numeric values.
* **Usage:**
    ```bash
    python topsis.py <InputDataFile> <Weights> <Impacts> <OutputResultFileName>
    ```

### 2️⃣ Part II: PyPI Package
The TOPSIS logic was encapsulated into a library and published on the Python Package Index (PyPI).
* **Package Name:** `Topsis-Devansh-[RollNumber]`
* **Installation:**
    ```bash
    pip install Topsis-Devansh-[RollNumber]
    ```
* **Live Link:** [Click here](https://pypi.org/project/TOPSIS-Devansh-102317041/)

### 3️⃣ Part III: Web Service & Emailer
A backend service that abstracts the complexity. Users simply upload their file, and the server handles the processing and emails the results.
* **Features:** File upload interface, parameter validation, SMTP email integration.
* **Workflow:** Upload CSV $\rightarrow$ Process TOPSIS $\rightarrow$ Email Results.

* **Live Link:** [Click here](https://topsis-web-service.streamlit.app/)

---

## 🛠️ Technologies Used
* **Language:** Python
* **Libraries:** Pandas, NumPy, SMTP (Email)
* **Package Management:** Twine

---
*This repository is a compilation of assignments for the Thapar Institute of Engineering & Technology.*
