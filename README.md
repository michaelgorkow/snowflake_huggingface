# Running Custom Hugging Face Models in Snowflake

This repository demonstrates how to deploy and run custom Hugging Face models within Snowflake using its new model registry feature.  
The focus is to provide a seamless integration between Hugging Face’s advanced models and Snowflake's powerful data handling capabilities.

## Prerequisites

Before you begin, ensure you have the following:
- A Snowflake account.
- Conda installed on your machine (Anaconda or Miniconda).

## Setup

Follow these steps to set up and run the demonstration:

### Step 1: Create a Conda Environment

Create a new Conda environment using the `conda_env.yml` file provided in this repository. This environment will contain all the necessary dependencies for the project.

```bash
conda env create -f conda_env.yml
```

### Step 2: Configure Authorization
Adapt the code to align with your authorization process for Snowflake.  
This example assumes the presence of a .env file in the working directory containing the credentials for your Snowflake account.

### Step 3: Run the Notebook
Launch the multilanguage_embeddings.ipynb notebook to see the integration in action.  
This Jupyter notebook contains all necessary steps to load, deploy, and query Hugging Face models directly within Snowflake.

### Learn More
For a deeper dive into how this integration works and the benefits it offers, check out our detailed blog article:

[Read the Blog Article](https://medium.com/@michaelgorkow/custom-embedding-models-from-hugging-face-in-snowflake-fd9cc79e25c8)


