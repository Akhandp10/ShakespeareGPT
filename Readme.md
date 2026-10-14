# ShakespeareGPT

### Generate Shakespeare-inspired text with a Transformer language model

A Python and Streamlit application that generates Shakespeare-inspired text using a PyTorch Transformer language model.

[GitHub Repository](https://github.com/Akhandp10/ShakespeareGPT) · [Report an Issue](https://github.com/Akhandp10/ShakespeareGPT/issues)

---

## Overview

**ShakespeareGPT** is a text-generation project that uses a Transformer-based language model implemented with PyTorch to produce text inspired by William Shakespeare's writing style. Enter a starting phrase and let the model generate a continuation.

This repository is a customized version of the original [Axios-2.0 project](https://github.com/NeonKazuha/Axios-2.0). The original code and contributions remain subject to their applicable licenses and attribution requirements.

## Features

- **Prompt-based generation:** Start with your own text.
- **Transformer model:** Uses PyTorch for neural text generation.
- **Interactive interface:** Run the application through Streamlit.
- **Saved model weights:** Uses `Shakespeare_model.pth` when available and compatible.
- **Notebook:** Includes a Jupyter notebook for model exploration.

## Technology Stack

| Technology | Purpose |
|---|---|
| Python | Application and model code |
| PyTorch | Neural network and inference |
| Streamlit | Interactive web interface |
| Jupyter Notebook | Model experimentation |

## Project Structure

```text
ShakespeareGPT/
├── app.py
├── axiosthingy.py
├── LICENSE
├── NOTICE.md
├── Readme.md
├── requirements.txt
├── Shakespeare_model.pth
└── shakespearemodel.ipynb
```

## Getting Started

### Prerequisites

- Python 3.10 or a compatible version supported by the dependencies
- Git
- pip

### 1. Clone the repository

```bash
git clone https://github.com/Akhandp10/ShakespeareGPT.git
cd ShakespeareGPT
```

### 2. Create a virtual environment

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

### 3. Install dependencies

```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

### 4. Run the application

```bash
streamlit run app.py
```

Open the local URL printed by Streamlit in your browser.

If the application reports a missing dependency or model checkpoint, verify that the required files are present and that your installed packages match `requirements.txt`.

## How to Use

1. Start the Streamlit application.
2. Enter a starting phrase.
3. Adjust the generation options available in the interface.
4. Generate and read the resulting text.

The available controls depend on the current implementation of `app.py`.

## Model Information

The project uses a Transformer-based language model implemented with PyTorch. The checkpoint `Shakespeare_model.pth` stores model parameters used for generation when configured in the application.

Refer to the model implementation and notebook for the exact architecture, training process, and generation settings.

Generated text may be repetitive, inconsistent, or unlike Shakespeare's original writing.

## Troubleshooting

- **`streamlit: command not found`:** Activate your virtual environment and install the dependencies.
- **Missing Python module:** Verify that the dependencies are installed in the same environment used to run the application.
- **Checkpoint not found:** Confirm that `Shakespeare_model.pth` exists at the path expected by the code.
- **Model loading error:** Check that the checkpoint matches the architecture defined in the source code.

## License and Attribution

This project is derived from [Axios-2.0](https://github.com/NeonKazuha/Axios-2.0).

The original MIT license and applicable copyright notices must be retained for the material covered by that license. See [LICENSE](LICENSE) and [NOTICE.md](NOTICE.md) for licensing and attribution information.

Third-party assets, including model weights and datasets, may be subject to separate licensing terms.

## Maintainer

**Akhand Pratap**

- GitHub: [@Akhandp10](https://github.com/Akhandp10)
- Project: [ShakespeareGPT](https://github.com/Akhandp10/ShakespeareGPT)

## Acknowledgments

- The original [Axios-2.0 repository](https://github.com/NeonKazuha/Axios-2.0) and its contributors.
- The Python, PyTorch, and Streamlit communities.
