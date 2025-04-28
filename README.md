# PLS Implementation and Dimensionality Reduction Benchmarking

This project focuses on the implementation of Partial Least Squares (PLS) regression, followed by a simple linear example demonstrating PLS in practice. Additionally, it benchmarks the runtime and error of Linear Regression and Gaussian Process models under three different settings:
- No dimensionality reduction
- Dimensionality reduction using PLS
- Dimensionality reduction using PCA

## Contents

- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Author](#author)

## Installation

Clone the repository and install the required Python packages:

```bash
git clone https://github.com/your-username/your-project.git
cd your-project
pip install -r requirements.txt
```

## Usage

After installing the requirements, you can run the main Jupyter Notebook to:

- Test the PLS regression implementation.
- Perform a simple linear example with PLS.
- Compare the performance (runtime and error) of Linear Regression and Gaussian Process models:
  - without dimensionality reduction,
  - with dimensionality reduction using PLS,
  - and with dimensionality reduction using PCA.

The main controller is located in the section titled **"Main"** within the Jupyter Notebook.  
There you can configure important parameters such as:
- Number of dimensions,
- Number of components for dimensionality reduction,
- Type and method of data sampling.

Example:

```bash
jupyter notebook ba.ipynb
```

## License
Licensed under the MIT License – see LICENSE file for details.


## Author

This project was created by **Yan Muller** as part of a Bachelor's thesis in Computer Science at Rheinland-Pfälzische Technische Universität Kaiserslautern (RPTU) (2025).
