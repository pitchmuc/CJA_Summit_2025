# L123 - From Data to Decisions: Data Science for Customer Journey Analytics Lab

Welcome to the repository for **L123 - From Data to Decisions: Data Science for Customer Journey Analytics Lab** at Adobe Summit 2025. Learn how to master Adobe Customer Journey Analytics (CJA) through data science and Python programming. In this hands-on lab, you'll discover how to build datasets, optimize integrations, and leverage analytics tools with Python. Our instructors will guide you through practical exercises designed to enhance data quality, improve workflows, and implement advanced analytics using Python libraries. You'll also learn how to interact with Adobe's APIs for sophisticated data manipulation. This lab empowers you to create scalable, high-performance data architectures that drive actionable insights and business value—all using Python.

## Introduction

The materials contained in this repository, presented at Adobe Summit 2025, aim to provide an end-to-end understanding of analyzing and leveraging customer journey data. In this repository, you'll find notebooks showing different methods for building and scaling efficient analyses and pipelines. The notebooks cover the following topics:

## Notebook 1 : Introduction to cjapy
In this notebook, learn about the concepts used in `cjapy` and how to connect to this tool.
We will show you how to get started with Python, cjapy, and obtain the required permissions to unlock their potential.

**[01. Introduction.ipynb](https://github.com/pitchmuc/CJA_Summit_2025/blob/main/notebooks/01.%20Introduction.ipynb)**

Covers:
* Creating a Developer Project in Adobe Environment
* Installing the `cjapy`, `aepp`, and notebook modules
* Getting started with `cjapy`

## Notebook 2 : Solution Design & Data Usage
In this notebook, we will build a Solution Design from scratch using cjapy to create readable metadata files. We will analyze which elements are being used (or not) and map them to XDM fields, allowing you to report on XDM paths instead of CJA dimensions and metrics.
This process creates a bridge between data analysts and data architects, helping both understand the schema composition of data collection methods.

**[02. Data View exploration and AEP schema comparison.ipynb](https://github.com/pitchmuc/CJA_Summit_2025/blob/main/notebooks/02.%20Data%20View%20exploration%20and%20AEP%20schema%20comparison.ipynb)**

Covers:
* Connecting to `cjapy` and retrieving Data Views
* Manipulating, cleaning and copying a dataframe
* Connecting to AEP via `aepp`
* Extracting Schema information via `aepp`
* Connecting Schema and CJA Data View

## Notebook 3 : Advance Analytics
In this notebook, we'll explore how to leverage the Python ecosystem after extracting data from `CJA` via the API and `cjapy`. We'll demonstrate additional capabilities that can provide deeper insights into your data to create complex data requests.

**[03. Advance Analytics.ipynb](https://github.com/pitchmuc/CJA_Summit_2025/blob/main/notebooks/03.%20Advance%20Analytics.ipynb)**

Covers:
* Creating data requests for CJA API via `cjapy`
* Understanding data request responses
* Complex data extraction use cases
* Advanced data analysis with external tools


## Notebook 4 : Visualization & Forecasting
In this notebook we will explore how to visualize data extracted from `CJA` via the API and `cjapy`. We will demonstrate how to create visualizations and forecasts using external tools like `matplotlib`, `plotly`, and `seaborn`.

**[04. Visualizations & Forecasting.ipynb](https://github.com/pitchmuc/CJA_Summit_2025/blob/main/notebooks/04.%20Visualizations%20%26%20Forecasting.ipynb)**

* Data Extraction using `cjapy` for CJA metrics
* Data Preprocessing and date formatting
* Time Series Analysis with Prophet model
* Visualization techniques including:
  - Line plots
  - Histograms
  - Interactive Plotly plots
  - Rolling statistics
  - Seasonal decomposition
  - Heatmaps
  - Boxplots
* Statistical Analysis and time series decomposition
* Volatility Modeling with GARCH


## Notebook 5 : Summary Data to Adobe Experience Platform (AEP)

In this notebook, we will explore how to extract data from CJA and via `aepp` load it into AEP. We will demonstrate how to create a data pipeline to extract data from CJA, transform it, and load it into AEP.

**[05. Summary Data to AEP.ipynb](https://github.com/pitchmuc/CJA_Summit_2025/blob/main/notebooks/05.%20Summary%20Data%20to%20AEP.ipynb)**

Covers:
* Setup and initialization of environment
*  Data loading procedures
*  Schema and dataset creation
    - Field group setup
    - Schema definition
    - Dataset configuration
* AEP data ingestion preparation
* Data ingestion process
* Connection and DataView setup


## Notebook 6 : CJA Data View Solution Design Reference

A revamped tool to assist in the design of CJA Data View Solution Design Reference Documentation. It automates the generation of a comprehensive spreadsheet detailing all metrics and dimensions available in a selected CJA Data View.

**[06. CJA Data View Solution Design Reference Generator.ipynb](https://github.com/pitchmuc/CJA_Summit_2025/blob/main/notebooks/06.%20CJA%20Data%20View%20Solution%20Design%20Reference%20Generator.ipynb)**

Covers:
* Initial `cjapy` Setup
* Data View Selection
* Retrieves CJA Metadata, Data View Information, Data View Metrics and Dimensions
* Generates a Detailed CJA Data View Solution Design Reference Excel Spreadsheet


## Getting Started

To explore these materials, ensure you have Jupyter Notebook installed. Clone this repository and open the notebooks in Jupyter to interact with the pre-configured code cells and conduct your analyses.

## Dependencies

Ensure the following Python libraries are installed to fully utilize the notebooks:

- `cjapy>=0.2.4`
- `matplotlib`
- `numpy`
- `pandas`
- `plotly`
- `PyJWT`
- `requests`
- `scikit_learn`
- `bokeh`
- `seaborn`
- `aepp>=0.3.9.post4`
- `openpyxl`
- `notebook`
- `jupyter`
- `prophet`
- `ipython`
- `statsmodels`
- `arch`
- `pytz`

These can be installed using pip:

```sh
pip install cjapy>=0.2.4 matplotlib numpy pandas plotly PyJWT requests scikit-learn bokeh seaborn aepp>=0.3.9.post4 openpyxl notebook jupyter prophet ipython statsmodels arch pytz
```

Note: cjapy might require additional setup as it is a custom library for Adobe's Customer Journey Analytics.

## Requirements
[requirements.txt](requirements.txt)

## Reference Links

- **cjapy GitHub Repository**: [https://github.com/pitchmuc/cjapy](https://github.com/pitchmuc/cjapy?tab=readme-ov-file)
- **aepp GitHub Repository**: [https://github.com/adobe/aepp](https://github.com/adobe/aepp/blob/main/README.md)
- **CJA API Documentation**: [Adobe CJA APIs](https://www.adobe.io/cja-apis/docs/api/) | [Use Cases](https://www.adobe.io/cja-apis/docs/use-cases/) | [Quick Start Guide](https://developer.adobe.com/cja-apis/docs/getting-started/) | [CJA API GitHub](https://github.com/AdobeDocs/cja-apis)
- **Adobe Developer Console Guide**: [Getting Started](https://developer.adobe.com/developer-console/docs/guides/getting-started/)