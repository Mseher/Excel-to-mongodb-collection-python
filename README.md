
# **Fitness App Data Conversion**

## **Overview**
This project aims to convert data from an Excel file to MongoDB for the Fitness App. The Excel data has been saved as a CSV file ('final.csv') and is processed using a Jupyter Notebook.

## **Dependencies**
1- Python 3.x
2- pandas
3- pymongo
4- PIL (Python Imaging Library)

## **Installation**
Clone this repository to your local machine.
Install the required dependencies using pip:
```
pip install pandas pymongo Pillow
```

## **Usage**
Place the 'final.csv' file in the project directory.
Open the provided Jupyter Notebook file ('data_conversion.ipynb') using Jupyter Notebook or JupyterLab.
Execute each cell in the notebook to convert and insert data into MongoDB.
Ensure that you have MongoDB installed and running on your local machine.

## **File Structure**
_final.csv:_ CSV file containing the data to be converted and inserted into MongoDB.
_data_conversion.ipynb:_ Jupyter Notebook file containing the data conversion and insertion code.
_README.md:_ This README file.

1- Data Conversion Process

2- Read the data from the 'final.csv' file using pandas.

3- Connect to MongoDB using pymongo.

4- Iterate through each row of the data, converting images to binary data using PIL.

5- Insert each row's data into the MongoDB database.

6- Optionally, query the MongoDB database to verify data insertion.

## **Note**
Make sure to replace the MongoDB connection details (e.g., hostname, port) with your actual MongoDB server information.
Ensure that the 'final.csv' file contains all necessary data fields in the expected format.
