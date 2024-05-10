# Retrieval Augmented Generation using Large Language Model

This repository contains code for a project focused on Retrieval Augmented Generation using a Large Language Model (LLM). The project utilizes Python 3.8.19 and includes a Jupyter notebook with the following functionalities:

1. Extracting data from a specified PDF file.
2. Storing the extracted information in a Chroma DB Vector Store.
3. Enforcing an LLM (GPT3.5 Turbo) to answer user queries based on relevant information from the Vector Store.

## Installation

To install the required Python packages, follow these steps:

1. Make sure you have Python 3.8.19 installed. If not, you can download it from the [official Python website](https://www.python.org/downloads/release/python-3819/).

2. Clone this repository to your local machine.

3. Navigate to the project directory in your terminal.

4. Install the required packages using pip:

    ```bash
    pip install -r requirements.txt
    ```

   This command will install all the necessary dependencies listed in the `requirements.txt` file.
   
5. To download the Menu card on which I experimented, run:

    ```
    mkdir data

    curl -O data/https://losteria.net/fileadmin/user_upload/losteria_ernaehrungsfibel_032022_interim_AT_website.pdf
    ```

## Usage

Once the required packages are installed, you can explore the functionalities provided in the Jupyter notebook. Open the notebook using Jupyter Notebook or JupyterLab and execute the cells to interact with the project. There is also extensive instructions, information and references provided inside the Notebook to follow along.

