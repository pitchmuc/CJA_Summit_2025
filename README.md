# LXXX - From Data to Decisions: Data Science for Customer Journey Analytics Lab

Welcome to the repository for **LXXX - From Data to Decisions: Data Science for Customer Journey Analytics Lab** at Adobe Summit 2025. Learn how to master Adobe Customer Journey Analytics (CJA) through data science and Python programming. In this hands-on lab, you'll discover how to build datasets, optimize integrations, and leverage analytics tools with Python. Our instructors will guide you through practical exercises designed to enhance data quality, improve workflows, and implement advanced analytics using Python libraries. You'll also learn how to interact with Adobe's APIs for sophisticated data manipulation. This lab empowers you to create scalable, high-performance data architectures that drive actionable insights and business value—all using Python.

## Introduction

The materials contained in this repository, presented at Adobe Summit 2025, aim to provide an end-to-end understanding of analyzing and leveraging customer journey data. In this repository, you'll find notebooks showing different methods for building and scaling efficient analyses and pipelines. The notebooks cover the following topics:

## Notebook 1 : Introduction to cjapy
In this notebook, learn about the concepts used in `cjapy` and how to connect to this tool.
We will show you how to get started with Python, cjapy, and obtain the required permissions to unlock their potential.

**[01. Introduction.ipynb](https://github.com/pitchmuc/CJA_Summit_2025/blob/fee46ddf820614bf7fdfaf1e655838985c5f9593/notebooks/01.%20Introduction.ipynb)**

Covers:
* Creating a Developer Project in Adobe Environment
* Installing the cjapy, aepp, and notebook modules
* Getting started with cjapy

## Notebook 2 : Solution Design & Data Usage
In this notebook, we will build a Solution Design from scratch using cjapy to create readable metadata files. We will analyze which elements are being used (or not) and map them to XDM fields, allowing you to report on XDM paths instead of CJA dimensions and metrics.
This process creates a bridge between data analysts and data architects, helping both understand the schema composition of data collection methods.

**[02. Solution Design.ipynb](https://github.com/pitchmuc/CJA_Summit_2025/blob/73e22b988b56bee3f51f70a377dd1ecfae0aab9e/notebooks/02.%20Solution%20Design.ipynb)**

Covers:
* Connecting to cjapy and retrieving dataviews
* Manipulating, cleaning and copying a dataframe
* Connecting to AEP via aepp
* Extracting Schema information via aepp
* Connecting Schema and Solution design

## Notebook 3 : Advance Analytics
In this notebook, we'll explore how to leverage the Python ecosystem after extracting data from `CJA` via the API and `cjapy`. We'll demonstrate additional capabilities that can provide deeper insights into your data.
External libraries can enhance your analysis and visualization, helping you extract more value from data processed by Customer Journey Analytics.

**[03. Advance Analytics.ipynb](https://github.com/pitchmuc/CJA_Summit_2025/blob/e8ff50efc235b6e90b0a08e82e6120413ef7bc2e/notebooks/03.%20Advance%20Analytics.ipynb)**

Covers:
* Creating data requests for CJA API via cjapy
* Understanding data request responses
* Complex data extraction use cases
* Data visualization with external tools
* Advanced data analysis with external tools


## Notebook 4 : Ingestion in AEP
In this notebook, we will use the data that are 

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
- `aepp`
- `openpyxl`
- `notebook`
- `jupyter`

These can be installed using pip:

```sh
pip install cjapy>=0.2.4 matplotlib numpy pandas plotly PyJWT requests scikit-learn bokeh seaborn aepp openpyxl notebook jupyter
```

Note: cjapy might require additional setup as it is a custom library for Adobe's Customer Journey Analytics.

## Requirements
[requirements.txt](requirements.txt)

## Reference Links

- **cjapy GitHub Repository**: [https://github.com/pitchmuc/cjapy](https://github.com/pitchmuc/cjapy?tab=readme-ov-file)
- **aepp Github Repository**: [https://github.com/adobe/aepp](https://github.com/adobe/aepp/blob/main/README.md)
- **CJA API Documentation**: [Adobe CJA APIs](https://www.adobe.io/cja-apis/docs/api/) | [Use Cases](https://www.adobe.io/cja-apis/docs/use-cases/)
- **Adobe Developer Console Guide**: [Getting Started](https://developer.adobe.com/developer-console/docs/guides/getting-started/)