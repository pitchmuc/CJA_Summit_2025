# LXXX - From Data to Decisions: Data Science for Customer Journey Analytics Lab

Master Adobe Customer Journey Analytics (CJA) with data science and Python programming. This hands-on lab shows you how to build datasets, optimize integrations, and use analytics tools with Python.

You'll learn to streamline data processes, create efficient workflows, and maximize CJA's capabilities. Through guided exercises, instructors demonstrate how to improve data quality and implement advanced analytics using Python libraries. You'll learn to use Adobe's APIs for powerful data manipulation. This lab equips you to build scalable, high-performance data systems that provide actionable insights and business value.

In this repository, you'll find notebooks showing different methods for building and scaling efficient analyses and pipelines:

## Notebook 1 : Introduction to cjapy
In this notebook, learn about the concepts used in `cjapy` and how to connect to this tool.
We will show you how to get started with Python, cjapy, and obtain the required permissions to unlock their potential.

Covers:
* Creating a Developer Project in Adobe Environment
* Installing the cjapy, aepp, and notebook modules
* Getting started with cjapy

## Notebook 2 : Solution Design & Data Usage
In this notebook, we will build a Solution Design from scratch using cjapy to create readable metadata files. We will analyze which elements are being used (or not) and map them to XDM fields, allowing you to report on XDM paths instead of CJA dimensions and metrics.
This process creates a bridge between data analysts and data architects, helping both understand the schema composition of data collection methods.

Covers:
* Connecting to cjapy and retrieving dataviews
* Manipulating, cleaning and copying a dataframe
* Connecting to AEP via aepp
* Extracting Schema information via aepp
* Connecting Schema and Solution design

## Notebook 3 : Advance Analytics
In this notebook, we'll explore how to leverage the Python ecosystem after extracting data from `CJA` via the API and `cjapy`. We'll demonstrate additional capabilities that can provide deeper insights into your data.
External libraries can enhance your analysis and visualization, helping you extract more value from data processed by Customer Journey Analytics.

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

- `cjapy`
- `pandas`
- `plotly`
- `json`
- `jwt`
- `requests`
- `sqlalchemy`
- `datetime`
- `sklearn`
- `numpy`
- `statsmodels`
- `warnings`

These can be installed using pip:

```sh
pip install cjapy pandas plotly json jwt requests sqlalchemy datetime sklearn numpy statsmodels warnings
```

Note: cjapy might require additional setup as it is a custom library for Adobe's Customer Journey Analytics.

## Requirements
[requirements.txt](requirements.txt)

## Reference Links

- **cjapy GitHub Repository**: [https://github.com/pitchmuc/cjapy](https://github.com/pitchmuc/cjapy?tab=readme-ov-file)
- **CJA API Documentation**: [Adobe CJA APIs](https://www.adobe.io/cja-apis/docs/api/) | [Use Cases](https://www.adobe.io/cja-apis/docs/use-cases/)
- **Adobe Developer Console Guide**: [Getting Started](https://developer.adobe.com/developer-console/docs/guides/getting-started/)