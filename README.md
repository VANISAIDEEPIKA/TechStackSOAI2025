# TechStackSOAI2025 - Summer of AI 2025 
## Overview

This Python script automates the setup of a complete development environment for the **Summer of AI 2025** internship. It ensures that essential tools and packages are installed and configured on your Windows system so you can jump straight into coding without headaches.

---

## What it does

- Checks if **Git**, **Python 3.11+**, and **UV** tool are installed.
- Installs **Visual Studio Code** via `winget` if it’s not already present.
- Installs key Python packages: `numpy`, `pandas`, `streamlit`, `jupyterlab`, and `ruff` using the UV tool.
- Prompts you to install the Ruff VS Code extension for enhanced Python linting.
- Runs simple tests to launch Streamlit and JupyterLab to verify successful installation.

---

## Prerequisites

- Windows OS with `winget` available for package installation.
- Python 3.11 or higher installed.
- Internet connection to download packages and VS Code.

---

## How to use

1. Clone this repository:

   ```bash
   git clone https://github.com/VANISAIDEEPIKA/TechStackSOAI2025.git
   cd TechStackSOAI2025 

2. Run the setup script:

```bash
python setup_soai_env.py
          0r
python setup_soai_env.py.txt
