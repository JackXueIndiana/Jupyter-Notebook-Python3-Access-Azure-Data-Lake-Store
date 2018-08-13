# Jupyter-Notebook-Python3-Access-Azure-Data-Lake-Store
This is to show you how to access Azure Data Lake Store from a Python 3 Jupyter Notebook.

You need to first install three packages from Microsoft

pip install azure-mgmt-resource

pip install azure-mgmt-datalake-store

pip install azure-datalake-store

A good Microsoft document to follow is here: https://docs.microsoft.com/en-us/azure/data-lake-store/data-lake-store-data-operations-python

The interactive login is discussed here: https://stackoverflow.com/questions/48208389/python-code-to-access-azure-data-lake-store

Since the user has to provide his credentials at the time to connect to ADLS with multi-fact authentication, this is a very safe way for individual user to develop Python code with access to the data in ADLS.
