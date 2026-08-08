<div align="center">

# 🧠 AI Material Science Laboratory
### 🚀 Python • Pandas • NumPy • Matplotlib • Data Analysis

<img src="https://readme-typing-svg.herokuapp.com?font=Poppins&size=24&pause=1000&color=00C2FF&center=true&vCenter=true&width=700&lines=Welcome+to+AI+Material+Science+Labs!;Python+for+Material+Engineering;Data+Analysis+%7C+Visualization+%7C+Machine+Learning;Learn+by+Hands-on+Jupyter+Notebooks" />

![Python](https://img.shields.io/badge/Python-3.12-blue?style=for-the-badge&logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Scientific-blue?style=for-the-badge&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green?style=for-the-badge)

---

> 📚 Practical AI & Material Science notebooks for learning Python programming, data analysis, material properties, and scientific visualization.

</div>

---

# 📂 Repository Structure

```
📦 AI-Material-Science
 ├── 📓 Module 1 S01.ipynb
 ├── 📓 Module 1 S02.ipynb
 ├── 📓 Module 1 S03.ipynb
 ├── 📓 Module 1 S04.ipynb
 ├── 📓 Module 1 S05.ipynb
 ├── 📓 Module 1 S06.ipynb
Module 1 S07
 └── 📄 README.md
```

---

# 📘 Notebook Overview

## 📓 Module 1 S01.ipynb
### 🏗️ Material Properties using Python

✨ Topics Covered

- Dictionary Creation
- Material Database
- Atomic Number
- Density
- Material Properties
- Python Basics
- Data Storage

🎯 Learning Outcome

✔ Learn how to organize engineering material data using Python dictionaries.

---

## 📓 Module 1 S02.ipynb
### 📊 Material Data Processing

✨ Topics Covered

- NumPy
- Arrays
- Scientific Computation
- Material Dataset Handling
- Data Processing
- Engineering Calculations

🎯 Learning Outcome

✔ Understand numerical computing techniques used in Material Science.

---

## 📓 Module 1 S03.ipynb
### 📈 Periodic Table Visualization

✨ Topics Covered

- Matplotlib
- Transition Metals
- Charts
- Graphs
- Scientific Visualization

🎯 Learning Outcome

✔ Visualize engineering datasets with professional graphs.

---

## 📓 Module 1 S04.ipynb
### 🔥 Thermal Conductivity Analysis

✨ Topics Covered

- Thermal Conductivity
- Material Comparison
- Bar Charts
- Data Visualization

🎯 Learning Outcome

✔ Compare thermal properties of different engineering materials visually.

---

## 📓 Module 1 S05.ipynb
### 📋 Multi-Material Dataset

✨ Topics Covered

- Pandas DataFrame
- Multiple Materials
- Material Database
- Engineering Data Analysis

🎯 Learning Outcome

✔ Build and analyze structured material datasets.

---

## 📓 Module 1 S06.ipynb
### 🤖 AI Workflow & Git Basics

✨ Topics Covered

- Pandas
- Dataset Creation
- Git Commands
- Version Control
- AI Project Workflow

🎯 Learning Outcome

✔ Learn professional project management using Git with AI notebooks.

---
### Materials Project Data Retrieval & Analysis

This repository contains Python workflows and Jupyter Notebooks designed to securely authenticate, query, and analyze material properties using the [Materials Project API](https://docs.materialsproject.org/) (mp-api). 

### 🛠️ Environment Setup

The notebooks are configured to run inside an Anaconda virtual environment named materials using **Python 3.12**. 

### 1. Install Dependencies

Activate your environment and run the following command to install the required data processing, visualization, and API client libraries: 

bash

pip install mp-api pandas matplotlib seaborn python-dotenv

Use code with caution.

### 2. Secure API Key Configuration

To safeguard your Materials Project credentials, this repository utilizes python-dotenv to manage secret keys without hardcoding them into the codebase. 

1. Create a file named .env in the root folder of this project: 

bash

touch .env

Use code with caution.
2. Open the .env file and add your official Materials Project API Key: 

env

MP_API_KEY=your_actual_api_key_here

Use code with caution.

### 📂 Repository Structure

### 🔬 Notebook 1: Initialization & Visualizations

* **File:** 01_environment_and_plotting.ipynb
* **Purpose:** Validates package installation integrity and loads the data visualization baseline.
* **Core Libraries:** pandas, matplotlib.pyplot, seaborn

### 🔑 Notebook 2: Secure API Authentication

* **File:** 02_api_authentication.ipynb
* **Purpose:** Sets up environment configuration frameworks and loads the MPRester client securely via environment variables.
* **Core Libraries:** os, python-dotenv, mp_api.client

### 🚀 Usage Example

Once your .env configuration file is active, you can securely query data through the MPRester context manager client without exposing your token keys: 

python

import os
from dotenv import load_dotenv
from mp_api.client import MPRester

# Load environment variables from the .env file
load_dotenv()
api_key = os.getenv("MP_API_KEY")

# Query materials safely
with MPRester(api_key) as mpr:
    # Example: Search for materials by chemical formula
    docs = mpr.summary.search(formula="GaAs")
    print(f"Successfully retrieved {len(docs)} entries for GaAs!")

Use code with caution.

### 📄 License

This project is open-source and available under the [MIT License](LICENSE).
# 🛠 Technologies Used

| Technology | Purpose |
|------------|----------|
| 🐍 Python | Programming |
| 📊 Pandas | Data Analysis |
| 🔢 NumPy | Numerical Computing |
| 📈 Matplotlib | Visualization |
| 📒 Jupyter Notebook | Interactive Coding |
| 🌳 Git | Version Control |

---

# 🎯 Learning Objectives

✅ Python Programming

✅ Material Property Analysis

✅ Engineering Data Handling

✅ Scientific Visualization

✅ Dataset Management

✅ AI-ready Data Processing

---

# 🚀 Getting Started

```bash
git clone <repository-url>

cd AI-Material-Science

jupyter notebook
```

Open any notebook and execute the cells one by one.

---

# 🌟 Skills You'll Gain

- Python Programming
- Engineering Data Analysis
- Material Science Concepts
- Scientific Visualization
- Data Processing
- Git Workflow
- Jupyter Notebook Usage

---

# 📚 Course Modules

| Module | Status |
|---------|--------|
| Material Properties | ✅ |
| Data Processing | ✅ |
| Visualization | ✅ |
| Thermal Analysis | ✅ |
| Material Dataset | ✅ |
| AI Workflow | ✅ |

---

<div align="center">

## ⭐ If you found this repository useful, don't forget to Star it!

### Happy Learning 🚀

Made with raghav kumar using jupiter notebook.

</div>
