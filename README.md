![Logo](https://img.freepik.com/vector-premium/copa-mundial-fifa-qatar-2022-logotipo-estilizado-vector-ilustracion-aislada-futbol_633888-128.jpg?w=740)

---

![Data Science](https://img.shields.io/badge/-Data%20Science-black?style=for-the-badge&logo=jupyter&logoColor=white&color=FF8F00)
![Python](https://img.shields.io/badge/-Python-black?style=for-the-badge&logo=python&logoColor=white&color=2F73BF)
![Selenium](https://img.shields.io/badge/-Selenium-black?style=for-the-badge&logo=selenium&logoColor=white&color=A1DD70)
![NumPy](https://img.shields.io/badge/-NumPy-black?style=for-the-badge&logo=numpy&logoColor=white&color=2F73BF)
![Pandas](https://img.shields.io/badge/-Pandas-black?style=for-the-badge&logo=pandas&logoColor=white&color=2F73BF)

---

## 📋 Table of Contents

1. 📕 [What is this repo?](#Description)
2. 🧰[Requeriments](#Requirements)
3. 🔨[Installation](#Installation)
4. ⚙ [Usage](#Usage)
5. 🧎 [Acknowledgements](#Acknowledgements)
6. © [License](#License)


---

## Description

This data science project aims to predict the winner of the FIFA World Cup Qatar 2022. The project includes all stages of a data science pipeline, from data extraction to model creation.
## Requirements 

To run this project, you need to have the following Python libraries installed: 
- Selenium 
- Pickle 
- NumPy 
- Pandas 
- Seaborn 

You can install all dependencies using the provided `requirements.txt` file.
## Installation

Clone this repository and navigate to the project directory: 

```bash 
git clone https://github.com/yourusername/Qatar2022-MachineLearning.git 
cd fifa-qatar-2022-prediction
```

Install the dependencies:

```bash
pip install -r requirements.txt
```

## Usage

### 1. Data Extraction

The first step is to extract the statistics data for the World Cup using Selenium and BeautifulSoup from Wikipedia.
```bash 
python src/missingdata.py
python src/results&Fixture.py
python notebooks/1.get_tables_groupstage.ipynb
```
### 2. Data Preprocessing and EDA

Then, clean and preprocess the data for analysis.
```bash
python src/2.data_cleaning.ipynb
```
### 3. Model Training

Train the prediction model using the prepared data.
```bash
python src/3.model_creation.ipynb
```

## Acknowledgements

 - [Frank Andrade](https://www.youtube.com/watch?v=EuZ4gwNNYwg)

## License

[MIT](https://choosealicense.com/licenses/mit/)