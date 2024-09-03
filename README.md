# azure_blob_storage
This repository contains a Jupyter notebook that demonstrates how to interact with Azure Blob Storage using Python. It covers basic operations such as creating a container,  uploading, downloading, accessing and managing blobs in Azure's cloud storage service. 

# Azure Blob Storage with Python

This repository provides a comprehensive guide to working with Azure Blob Storage using Python. It includes a Jupyter notebook that walks through the basic operations you can perform with blobs, such as uploading, downloading, and managing files in Azure's cloud storage service.

## Overview

Azure Blob Storage is a service for storing large amounts of unstructured data, such as text or binary data. The notebook in this repository demonstrates how to use Python to perform common tasks with Azure Blob Storage, making it easier for developers and data scientists to integrate cloud storage into their workflows.

## Features

- **Connecting to Azure Blob Storage:** Learn how to authenticate and connect to your Azure Blob Storage account using Python.
- **Uploading Files:** Step-by-step instructions to upload files from your local system to Azure Blob Storage.
- **Downloading Files:** Instructions on how to retrieve files from Azure Blob Storage to your local system.
- **Managing Blobs:** Explore how to list, delete, and perform other management tasks on blobs within your storage containers.

## Prerequisites

To run the code in this notebook, you will need:

- An Azure account with an active subscription.
- The Azure Blob Storage account name and access key.
- Python 3.x installed on your local machine.
- The following Python packages:
  - `azure-storage-blob`
  - `os`
  - `sys`
  - `logging`
  - `dotenv` (if using environment variables for credentials)

You can install the required packages using pip:

```bash
pip install azure-storage-blob python-dotenv
