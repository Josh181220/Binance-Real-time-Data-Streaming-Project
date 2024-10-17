# Binance-Real-time-Data-Streaming-Project
This project involves building a data pipeline to extract real-time data of selected cryptocurrencies from the Binance website. Additionally, it uses the Marketstack API to collect stock and commodities data, enabling comparative analysis between the behavior of cryptocurrencies and traditional financial instruments.


**1. BinanceNotebook Final.ipynb**
This Jupyter notebook contains all the Python code used for data extraction, transformation, and analysis of selected cryptocurrencies from the Binance website. It includes the code for fetching real-time data, performing data cleaning, and conducting a comparative analysis between cryptocurrency behavior and traditional financial instruments such as stocks and commodities.

**2. Modern Data Project.pdf**
This PDF is a detailed presentation that outlines the complete end-to-end process of the data pipeline, from data sourcing to final analysis. It explains each stage, including:

Source: Real-time data extraction from the Binance website.
Ingestion: Data ingestion process using Apache NiFi.
Storage: Data storage in Hadoop clusters.
Processing: Data processing steps for analysis.
Serving: How the processed data is prepared for visualization and further analysis.
This document is intended to provide a clear, step-by-step explanation of the entire project workflow.

**3. Data Streaming Pipeline.xml**
This XML file contains the Apache NiFi pipeline configuration. It defines the workflow used to automate the streaming of real-time cryptocurrency data from the Binance website to Hadoop clusters. The pipeline handles tasks such as data ingestion, transformation, and loading into storage systems, ensuring seamless real-time data flow for further analysis and processing.
