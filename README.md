# Attack chains of sensors on a water-treatment system

![Illustration from the HAI Dataset](hai_illustration.jpg)

## Using `uv`

[`uv`](https://github.com/astral-sh/uv) is a fast Python package manager designed for reproducible environments. It will automatically create and manage an isolated environment for you.

**Step 1 :** In order to install `uv` on your system, you can simply run the following command on MacOS and Linux :

```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

and for Windows :

```powershell
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```

**Step 2 :** In order to both setup your environment an run the program, you can run the following command in your terminal in the project's directory :

```bash
uv run jupyter notebook
```

**Step 3 :** Double-click on the `hai.ipynb` file when the Jupyter web page has been opened in your browser.

## Using `pip`

**Step 1 :** Ensure you have **Python 3.11.8** or higher installed :

```bash
python3 --version
```

**Step 2 :** Create a virtual environment in the project's directory, and activate it :

```bash
python3 -m venv .venv

# For MacOS and Linux
source .venv/bin/activate

# For Windows
.venv\Scripts\activate
```

**Step 3 :** Download and install the required dependencies for the project inside the virtual environment :

```bash
pip install -r requirements.txt
```

**Step 4 :** Simply run the following command in order to start the project :

```bash
jupyter notebook
```

**Step 5 :** Double-click on the `hai.ipynb` file when the Jupyter web page has been opened in your browser.

## Using `Google Colab`

You can run this notebook directly in [Google Colab](https://colab.research.google.com), without any local installation :

**Step 1 :** Open [Google Colab](https://colab.research.google.com), and log in with a Google Account if needed.

**Step 2 :** In the `Open notebook` welcoming modal, in the menu on the left, select the `GitHub` option, and enter the following URL in the search bar : `https://github.com/ninolt/ai-attack-analysis`.

**Step 3 :** Click on the `hai.ipynb` file in order to open the project.

## Datasets

You can just run the first cell in the Jupyter notebook, but in case this doesn't work, you have to:

- Download the following files :
  - https://raw.githubusercontent.com/icsdataset/hai/master/hai-20.07/test1.csv.gz
  - https://raw.githubusercontent.com/icsdataset/hai/master/hai-20.07/test2.csv.gz
  - https://raw.githubusercontent.com/icsdataset/hai/master/hai-20.07/train1.csv.gz
  - https://raw.githubusercontent.com/icsdataset/hai/master/hai-20.07/train2.csv.gz

- Unzip them
- Place them in a "/data" folder, which should be right next to the jupyter file

