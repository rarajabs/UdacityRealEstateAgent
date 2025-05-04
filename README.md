# HomeMatch

This project is Final Project for Udacity program in Generative AI course.

## Prerequisites

To run this project, you need to have the following installed:

- Python
- Jupyter Notebook (VS Code)
- Required Python libraries (listed in `pyproject.toml`)
- Update OpenAI key in `.env`

## Installation

1. Clone this repository:

   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

1. Install [uv](https://docs.astral.sh/uv/):

   ```bash
   python -m pip install uv
   ```

1. Install the required dependencies:

   ```bash
   uv sync
   ```

1. Run the project notebook file (`HomeMatch-CLIP.ipynb`).

## Note:

### Failed to import `CSVLoader`

If facing error when importing `CSVLoader`, follow steps below to resolve

1. Install next version for `langchain-community`

   ```bash
   uv pip install langchain-community==0.0.20
   ```

1. Rerun jupyter notebook on importing part

1. Another error will happen

1. Reinstall `langchain-community` with version stated in `pyproject.toml`
   ```bash
   uv pip install langchain-community==0.0.19
   ```
