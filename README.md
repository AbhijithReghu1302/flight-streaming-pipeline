Real-Time Spark Streaming Pipeline
📌 Overview

This project implements a real-time data streaming pipeline using PySpark, designed to read live flight-related JSON data, process it continuously, and prepare it for downstream analytics.
The notebook simulates real-time ingestion, performs schema handling, and includes a loop that pulls data at fixed intervals.

🚀 Features

Live data fetching using requests

Continuous streaming with thread-based ingestion

JSON normalization

Schema-based processing in PySpark

Data display and validation

Basic ETL structure for a streaming pipeline

🧩 Project Workflow

Setup & Installation

Install PySpark in Google Colab

Configure Java environment

Initialize SparkSession

API Integration

Fetch live JSON data

Handle response failures

Convert response into structured data

Real-Time Streaming Logic

Threaded fetch loop

Append new records continuously

Infinite streaming simulation

Data Processing with PySpark

Convert JSON → DataFrame

Display schema

Show processed output

🔧 Technologies Used

Python

PySpark

Google Colab

JSON Data Handling

REST API Requests

Threading (Python)

📚 How to Run the Project

Upload the notebook to Google Colab

Run the installation cell (Java + PySpark)

Start the Spark session

Run the API streaming cell

Watch the data stream in real time
