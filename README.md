# nlp-524-project-2

## Table of Contents

- [About](#about)
- [Setup](#setup)
- [Project Structure](#project-structure)

## About

| # | Project Information |
|-|-|
| **Team Number** | **10** |
| **Team Members** | [Adam McDaniel](amcdan23@vols.utk.edu), [Ahmad Amirivojdan](aamirivo@vols.utk.edu), [Vincent Broda](vbroda@vols.utk.edu), [Mohamed Shatarah](mshatara@vols.utk.edu) |
| **Assigned Author** | *Agatha Christie* |
| **Project Task** | *Implement a complete chatbot for your novels using Hugging Face API/libraries.* |

This project is the second project for COSC 524 Natural Language Processing.

## Setup

To setup the environment, [install Python 3.11](https://www.python.org/downloads/release/python-3117/).
Then, run the following commands to create a `venv` and install the required packages:

```bash
$ python3.11 -m venv venv
$ venv/bin/pip install -r requirements.txt
```

Then, in your Jupyter Notebook, change the kernel to the `venv` kernel.

![Assets](assets/change_kernel.png)

To run the code, open the Jupyter Notebook and run the cells.

## Project Structure

The project is structured as follows:

- [`resources/`](resources/): Contains the resources for the knowledge base used in the project.
- [`project2.ipynb`](project2.ipynb): The interactive Jupyter Notebook containing the code for the project.
- [`assets/`](assets/): Contains the assets used in the README.
- [`requirements.txt`](requirements.txt): Contains the required packages for the project.
- `huggingface_token.txt`: Contains your Hugging Face API token. This file is not included in the repository, but you can create an account [here](https://huggingface.co/login), get an access token in your settings, and add it to the file.