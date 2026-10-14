# ShakespeareGPT

### Shakespeare-Inspired Text Generation with PyTorch

**Developed and maintained by Akhand Pratap**

ShakespeareGPT is a Python-based text-generation application that uses a Transformer language model and Streamlit to generate Shakespeare-inspired text from user-provided prompts.

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-ee4c2c)](https://pytorch.org/)
[![Streamlit](https://img.shields.io/badge/Streamlit-Web%20App-ff4b4b)](https://streamlit.io/)

[GitHub Repository](https://github.com/Akhandp10/ShakespeareGPT) · [Report an Issue](https://github.com/Akhandp10/ShakespeareGPT/issues)

---

## Overview

ShakespeareGPT is a text-generation application designed to produce text inspired by William Shakespeare's writing style. It uses a Transformer-based language model implemented with PyTorch and provides an interactive interface through Streamlit.

Users can provide an initial phrase and generate a continuation using the trained model.

## Features

- **Prompt-Based Generation:** Generate text from a user-provided starting phrase.
- **Transformer Architecture:** Use a neural language model built with PyTorch.
- **Interactive Web Interface:** Access text generation through Streamlit.
- **Model Checkpoint Support:** Load saved model parameters from `Shakespeare_model.pth`.
- **Python-Based Workflow:** Explore model implementation and experimentation using Python and Jupyter Notebook.

## Technology Stack

| Technology | Purpose |
|---|---|
| Python | Application and model implementation |
| PyTorch | Neural network and text generation |
| Streamlit | Interactive web interface |
| Jupyter Notebook | Model exploration and experimentation |

## Project Structure

```text
ShakespeareGPT/
├── app.py
├── axiosthingy.py
├── .gitignore
├── LICENSE
├── NOTICE.md
├── Readme.md
├── requirements.txt
├── Shakespeare_model.pth
└── shakespearemodel.ipynb
```

## Getting Started

### Prerequisites

Install the following before running the project:

- Python 3.10 or a compatible version supported by the dependencies
- Git
- pip

### 1. Clone the Repository

```bash
git clone https://github.com/Akhandp10/ShakespeareGPT.git
cd ShakespeareGPT
```

### 2. Create a Virtual Environment

**macOS / Linux**

```bash
python3 -m venv .venv
source .venv/bin/activate
```

**Windows PowerShell**

```powershell
python -m venv .venv
.venv\Scripts\Activate.ps1
```

### 3. Install Dependencies

```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

### 4. Launch the Application

```bash
streamlit run app.py
```

Once the application starts, open the local URL displayed in the terminal.

## How to Use

1. Launch the Streamlit application.
2. Enter a starting phrase in the interface.
3. Adjust any generation settings available in the application.
4. Generate and read the resulting text.

The available controls depend on the current implementation of `app.py`.

## Model Information

ShakespeareGPT uses a Transformer-based language model implemented with PyTorch.

The file `Shakespeare_model.pth` contains saved model parameters used by the application when loaded by the model code.

For the exact architecture, training procedure, and generation configuration, refer to `axiosthingy.py` and `shakespearemodel.ipynb`.

Generated text is produced by a language model and may contain repetition, inconsistencies, or language that differs from Shakespeare's original writing.

## Troubleshooting

**Streamlit command not found**

Activate your virtual environment and install the dependencies from `requirements.txt`.

**Missing Python module**

Ensure the dependencies are installed in the same Python environment used to launch Streamlit.

**Model checkpoint not found**

Verify that `Shakespeare_model.pth` exists at the path expected by the application.

**Model loading error**

Confirm that the saved checkpoint is compatible with the model architecture defined in the source code.

## License

See [LICENSE](LICENSE) for the applicable license terms and [NOTICE.md](NOTICE.md) for project attribution and contribution information.

## Maintainer

**Akhand Pratap**

<<<<<<< HEAD
- GitHub: [@Akhandp10](https://github.com/Akhandp10)
- Project: [ShakespeareGPT](https://github.com/Akhandp10/ShakespeareGPT)

## Acknowledgments

- The Python, PyTorch, and Streamlit communities.
=======
- **GitHub:** [@Akhandp10](https://github.com/Akhandp10)
- **Project:** [ShakespeareGPT](https://github.com/Akhandp10/ShakespeareGPT)
>>>>>>> ef86b3c (Update ShakespeareGPT README)
