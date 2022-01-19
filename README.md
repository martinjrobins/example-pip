## Example repo demonstrating pip

This repository shows a simple example project that relies on pip and a 
`requirements.txt` file to allow users to install and use the software (in this case a 
simple `fancy-data-analysis.py` script

## Installation

First create a virtual environment

```bash
python -m venv env
source env/bin/activate
```

Then install the requirements

```bash
pip install -r requirements.txt
```

## Usage

```bash
python fancy-data-analysis.py
```
