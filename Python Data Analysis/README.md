# This repository contains code examples for "Data Analysis using Python"

This repository contains the code examples from the book "Python for Data Analysis, 3rd Edition" by Wes McKinney.

## About the Book

* **Title:** Python for Data Analysis: Data Wrangling with pandas, NumPy, and Jupyter
* **Author:** Wes McKinney
* **Edition:** Third Edition (Updated for Python 3.10 and pandas 1.4)
* **Publisher:** O'Reilly Media
* **Focus:** This book provides a definitive handbook for manipulating, processing, cleaning, and crunching datasets in Python. It covers fundamental libraries like pandas, NumPy, IPython, and Jupyter, along with introductions to data visualization with matplotlib/seaborn and modeling with statsmodels/scikit-learn.

## Getting Started

These examples are designed to be run interactively, ideally using Jupyter notebooks or the IPython shell.

### Prerequisites

* Python 3.9 or higher (the book is updated for 3.10).
* Miniconda or Anaconda is recommended for managing packages and environments.

### Setup

1.  **Clone the repository:**
    ```bash
    git clone <your-repository-url>
    cd <repository-directory>
    ```
    *(Replace `<your-repository-url>` and `<repository-directory>` with the actual URL and local directory name)*

2.  **Create a Conda Environment (Recommended):**
    The book suggests using `conda-forge` and creating a dedicated environment.
    ```bash
    # Add conda-forge channel and set priority
    conda config --add channels conda-forge
    conda config --set channel_priority strict

    # Create the environment (using Python 3.10 as specified in the book)
    conda create -n pydata-book python=3.10

    # Activate the environment
    conda activate pydata-book
    ```

3.  **Install Dependencies:**
    Install the core libraries used throughout the book:
    ```bash
    conda install pandas jupyter matplotlib seaborn statsmodels scikit-learn
    ```
    You might also need additional libraries for specific chapters (check the book's setup instructions or install as needed):
    ```bash
    conda install lxml beautifulsoup4 html5lib openpyxl requests sqlalchemy pytables numba xlrd pyarrow
    # Or using pip for packages not found easily via conda
    # pip install <package_name>
    ```

4.  **Launch Jupyter:**
    Navigate to the repository directory in your terminal (ensure the `pydata-book` environment is active) and run:
    ```bash
    jupyter notebook
    ```
    This will open the Jupyter interface in your web browser, allowing you to navigate and run the `.ipynb` notebook files corresponding to the book chapters.

### Data Files

The datasets required for running the examples are typically included within the repository, often in a `datasets` or `examples` directory. Refer to the book's instructions for obtaining the official datasets if they are not present here.

## Official Book Repository

The official code repository maintained by the author, Wes McKinney, can be found at:

* **GitHub:** [https://github.com/wesm/pydata-book](https://github.com/wesm/pydata-book)
* **Gitee Mirror:** [https://gitee.com/wesmckinn/pydata-book](https://gitee.com/wesmckinn/pydata-book)

It's recommended to refer to the official repository for the most up-to-date code and data.

## License

Please refer to the Preface section of "Python for Data Analysis, 3rd Edition" regarding the usage policy for the code examples provided in the book. Consider adding a standard open-source license file (e.g., MIT, Apache 2.0) to this repository if you intend to modify or distribute the code further.

