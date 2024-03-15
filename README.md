# Hurricanes prediction


## Table of Contents

- [Approach](#approach)
- [Results](#results)
- [Structure of the repository](#structure)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)


<a name="approach"></a>
## Approach

<a name="results"></a>
## Results

<a name="structure"></a>
## Structure of the repository

```bash
├── data
├── notebooks
├── src
├── tests                                     <-- Unit and integration tests (NOT IMPLEMENTED yet)
│
├── .gitignore
├── .pre-commit-config.yaml
├── Makefile
├── README.md
├── pyproject.toml
├── requirements.in
└── requirements.txt
```

<a name="prerequisites"></a>
## Prerequisites

Before you begin, ensure you have met the following requirements:

- [Python](https://www.python.org/downloads/) installed (version >=3.9 and <=3.11) and added to PATH
- [Make](https://www.gnu.org/software/make/) installed

If you're using a Unix-based OS, "make" should already be installed.
If you're using a Windows device, follow the steps below to install Make:

1. Open a PowerShell window with administrative privileges.

2. Ensure that your PowerShell execution policy allows script execution. Run the following command:

```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force
```

3. Install Chocolatey by running the following command:

```powershell
iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```

4. Install make

```powershell
choco install make
```

<a name="installation"></a>
## Installation

For the whole installation section, you have to run the following commands in a bash shell.

1. Clone this repository:

```bash
git https://github.com/Guillaumegg200/hurricanes_prediction_mlns.git;
cd hurricanes_prediction_mlns

```

2. Create a virtual environment:

```bash
make venv
```

3. Install dependencies (make sure to activate the venv created beforehand)

```bash
make install
```

4. (Optional) For dev only, install pre-commit hooks:

```bash
make install_precommit
```

<a name="usage"></a>

## Usage
```bash
make format
```