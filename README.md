
---

# Dataset Repository

This repository contains the datasets used in my projects. Each dataset is organized in separate folders for easy reference and use.

## Repository Structure

```
/
├── Project1/
│   ├── dataset-file1.csv
│   ├── dataset-file2.csv
│   └── README.md          # Optional dataset details
├── Project2/
│   └── data.json
└── README.md              # This file
```

## Usage

To use the datasets, clone the repository:

```bash
git clone https://github.com/your-username/your-repo-name.git
```

Then navigate to the folder containing the dataset you want to work with.

Example (Python):

```python
import pandas as pd

df = pd.read_csv('Project1/dataset-file1.csv')
print(df.head())
```

