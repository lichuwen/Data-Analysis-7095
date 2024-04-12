# README

## Artifact Description

This README file describes in detail the relevant information of the artifacts in this project, including dependencies, requirements, installation, and deployment processes, experimental workflow.

---

## Project：Study and prediction of factors affecting heart disease

## Abstract

This project aims to utilize big data technology to analyze data from patients with heart disease for prevention and diagnosis. By combining the Pandas data processing library with the MySQL relational database management system, we conduct a thorough analysis of the data to uncover potential patterns and trends of heart disease. Furthermore, we employ Spark MLlib to build a logistic regression model for heart disease prediction, providing guidance for the prevention and diagnosis of heart disease.

---

## Artifact Dependencies

##### Hardware and Software Requirements

**Hardware**：Since this project runs on Google Colab, users do not need to meet specific local hardware requirements. Colab provides the necessary computing resources, including CPUs, GPUs, and a programming environment.

**Software**
1.A valid Google account for logging into Google Colab.
2.A stable internet connection to access and use Colab.

Most required software and libraries, including Python, Pandas, NumPy, Matplotlib, etc., are preinstalled in the Colab environment. Users can also install additional libraries in Colab if needed.

---

## Installation and Deployment Process

1. **Log in to Google Colab** : Use your Google account to log in to [Google Colab](https://colab.research.google.com/).
2. **Upload Project Files** : Upload our project files to Colab.
3. **Configure Environment** : In Colab's code cell, run `!pip install` command to install all Python libraries.
4. **Run Code** : Execute Python code in each code cell.

### Experimental Workflow Description

In the Colab environment, you can follow these steps for your experiments:

1. Use the `data_cleanning.ipynb` notebook to process the data. This step requires uploading the `source_data.csv` file.
2. Perform feature selection using the `feature_selection.ipynb` notebook. For this step, you need to upload the `data_cleanning.csv` file.
3. Carry out visualization with the `visualization.ipynb` notebook. This step demands the upload of the `feature_selection.csv` file.
4. Conduct predictions by running the `logistic_regression.ipynb` notebook. In this step, you are required to upload the `encoding_data.csv` file.

Please note that all file upload operations will be prompted within the code blocks, and you just need to execute the code blocks in sequence.

---

### Contributor

**Group-07**

**Student Names and IDs**：

Wan Xiaoxi (Student ID: 23434120)

Li Chuwen (Student ID:  23464283)

Ye Ruizhe (Student ID: 23450746)
