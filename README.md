# Converts Colab Notebooks 📙 to PDFs 📋

Simple utility function that lets you convert your colab notebook(s) to PDF(s). Just give it a notebook file name or notebook regex pattern and it will convert it for you.

## Usage

1. Verify the notebook you want to convert is executed and saved.
2. Copy & Paste the below code in new colab notebook or new code cell of the notebook you want to convert.
3. Replace the `r"sample_notebook\.ipynb"` with your notebook name or regex pattern. 
```
!wget https://raw.githubusercontent.com/hurshd0/colab_notebook_to_pdf/master/colab_to_pdf.py
from colab_to_pdf import colab_to_pdf
colab_to_pdf(r"sample_notebook\.ipynb")
```
