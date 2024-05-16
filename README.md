{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "21febb72-fefe-4ae5-a5c2-d2b0b93288d5",
   "metadata": {},
   "source": [
    "# Air Quality Analysis Project\n",
    "\n",
    "## Overview\n",
    "This project utilizes Apache Spark to perform an analysis of air quality data. The analysis is carried out in a Jupyter Notebook environment, focusing on the exploration and processing of air quality measurements to derive insights about pollution levels.\n",
    "\n",
    "## Dataset\n",
    "The dataset used in this project is titled `air-quality-data.csv` and contains various air quality measurements such as CO, NOx, NO2, and other pollutants recorded over time. Data attributes include timestamps, gas concentrations, and related environmental conditions.\n",
    "\n",
    "## Setup Instructions\n",
    "To run this project, follow these steps:\n",
    "\n",
    "1. **Environment Setup**:\n",
    "   - Ensure that Java Development Kit (JDK) and Apache Spark are installed.\n",
    "   - Use the following commands to set up Spark:\n",
    "     ```\n",
    "     apt-get install openjdk-8-jdk-headless -qq > /dev/null\n",
    "     wget -q https://archive.apache.org/dist/spark/spark-3.5.0/spark-3.5.0-bin-hadoop3.tgz\n",
    "     tar xf spark-3.5.0-bin-hadoop3.tgz\n",
    "     ```\n",
    "\n",
    "2. **Python Dependencies**:\n",
    "   - Install Python dependencies using the following command:\n",
    "     ```\n",
    "     pip install -r requirements.txt\n",
    "     ```\n",
    "\n",
    "3. **Launching the Notebook**:\n",
    "   - Start the Jupyter Notebook environment and open `analysis-and-prediction.ipynb`.\n",
    "   - Follow the steps in the notebook to perform the analysis.\n",
    "\n",
    "## Running the Analysis\n",
    "Execute the cells in the notebook `analysis-and-prediction.ipynb` sequentially to load the data, perform exploratory data analysis, and run various data processing steps.\n"
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3 (ipykernel)",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.11.7"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
