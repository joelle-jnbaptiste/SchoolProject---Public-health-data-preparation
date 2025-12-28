<p align="center">
  <img src="https://img.shields.io/github/license/joelle-jnbaptiste/SchoolProject---Public-health-data-preparation?style=for-the-badge" />
  <img src="https://img.shields.io/badge/School%20Project-Data%20Preparation-blueviolet?style=for-the-badge" />
</p>

<h1 align="center">✨ Public Health Data Preparation ✨</h1>

<div align="center">
  <em>
     *Turning raw public data into reliable analytical assets*
  </em>
</br>

 <b>Data preparation and exploratory analysis for a public health use case, focusing on data cleaning, validation, and analytical insights using Python</b>
</br>
</br>
🗃️ **Dataset**  
 https://world.openfoodfacts.org/
  
</div>

---

<!-- TABLE OF CONTENTS -->
<details>
  <summary>🧭 Table of Contents</summary>
  <ol>
    <li><a href="#-built-with">Built With</a></li>
    <li><a href="#-about-the-project">About The Project</a></li>
    <li><a href="#-dataset">Dataset</a></li>
    <li><a href="#-data-preparation-overview">Data Preparation Overview</a></li>
    <li><a href="#-repository-structure">Repository Structure</a></li>
    <li><a href="#-getting-started">Getting Started</a></li>
    <li><a href="#-license">License</a></li>
    <li><a href="#-contact">Contact</a></li>
  </ol>
</details>

---

### ✨ Built With

[![Python][Python-shield]][Python-url]
[![Pandas][Pandas-shield]][Pandas-url]
[![NumPy][NumPy-shield]][NumPy-url]
[![Matplotlib][Matplotlib-shield]][Matplotlib-url]
[![Seaborn][Seaborn-shield]][Seaborn-url]
[![Jupyter][Jupyter-shield]][Jupyter-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

## 🎯 About The Project

This project focuses on **data preparation and exploratory data analysis** for a public health use case, based on the **Open Food Facts** dataset.

The objective is to transform raw, heterogeneous food product data into a **clean, consistent, and analyzable dataset** that can support:

- Public health studies
- Nutritional analysis
- Decision-making and reporting
- Downstream analytical or machine learning use cases

The project emphasizes **data quality**, **validation**, and **interpretability** rather than predictive modeling.

---

## 🗃️ Dataset

The dataset used in this project comes from **Open Food Facts**, an open and collaborative database of food products from around the world.

It contains information such as:

- Product categories
- Nutritional values
- Ingredients
- Labels and tags
- Country-specific metadata

The dataset is intentionally **noisy and incomplete**, making it well suited for data preparation and cleaning exercises.

---

## 🧹 Data Preparation Overview

The notebook covers the following steps:

- Initial data exploration and profiling
- Identification of missing, inconsistent, and invalid values
- Data cleaning and normalization
- Feature selection for analytical relevance
- Univariate and multivariate exploratory analysis
- Visualization of distributions and relationships

To improve readability, the repository also includes **exported HTML versions** of the analysis to visualize results without running the notebook.

The goal is to demonstrate **methodical data preparation** and **clear analytical reasoning**.

---

## 🗺️ Repository Structure

    SchoolProject---Public-health-data-preparation/
    ├── notebooks/
    │   ├── Jean_Baptiste_Joelle_1_notebook_032024.ipynb
    │   ├── before_cleaning_numeric.html
    │   ├── before_cleaning.html
    │   ├── after_cleaning_numeric.html
    │   └── after_cleaning.html
    ├── README.md

---

## ⚔️ Getting Started

This project runs locally using **Python** and **Jupyter Notebook**.

### Prerequisites

- Python 3.x
- pip
- Jupyter Notebook or JupyterLab

### Installation

1. Clone the repository:

       git clone https://github.com/joelle-jnbaptiste/SchoolProject---Public-health-data-preparation.git

2. Install dependencies:

       pip install pandas numpy matplotlib seaborn jupyter

3. Launch Jupyter Notebook:

       jupyter notebook

4. Open the notebook file and run the cells sequentially.

---

## ✒️ License

This project is provided for educational purposes.  
The dataset is publicly available under the **Open Food Facts license**.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

## 🕊️ Contact

Joëlle JEAN BAPTISTE  
LinkedIn: https://fr.linkedin.com/in/joëllejnbaptiste  

Project Link: https://github.com/joelle-jnbaptiste/SchoolProject---Public-health-data-preparation

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

[Python-shield]: https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white
[Python-url]: https://www.python.org/
[Pandas-shield]: https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white
[Pandas-url]: https://pandas.pydata.org/
[NumPy-shield]: https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white
[NumPy-url]: https://numpy.org/
[Matplotlib-shield]: https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge
[Matplotlib-url]: https://matplotlib.org/
[Seaborn-shield]: https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge
[Seaborn-url]: https://seaborn.pydata.org/
[Jupyter-shield]: https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white
[Jupyter-url]: https://jupyter.org/
