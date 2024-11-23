# Simple Data Lake Implementation

This project demonstrates a simple implementation of a data lake using Python. It is designed to ingest, process, and refine datasets through different layers: **raw**, **refined**, and **curated**. Each layer represents a stage in the data lifecycle, enabling better organization and transformation of data for analytical use.

---

## Table of Contents
- [Project Structure](#project-structure)
- [Features](#features)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)


---

## Features

- **Data Ingestion**: Copies datasets from the `data/` directory into the **raw layer** of the data lake.
- **Layered Transformations**:
  - **Refined Layer**: Adds a `Processed` column to datasets.
  - **Curated Layer**: Transforms data further (e.g., reverses `FirstName` values).
- **File Type Support**: Handles `.csv` and `.json` file formats.
- **Scalable Design**: Easily extendable for more layers and transformations.

---

## Setup Instructions

### Prerequisites
- Python 3.7 or later
- The following Python libraries:
  - `pandas`
  - `os`
  - `shutil`

Install required libraries using pip:
```bash
pip install pandas




