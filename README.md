# VPIINSDataProcessing4Graph
# Data to Neo4j Pipeline

This repository contains data, Jupyter notebooks, and scripts to process data, convert it from datatable format to CYPHER queries, and load it into a Neo4j database.

## Table of Contents

- [Introduction](#introduction)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Introduction

This project aims to provide a streamlined process for transforming data tables into CYPHER queries, facilitating the loading of data into a Neo4j graph database. The repository includes data samples, Jupyter notebooks for data processing and transformation, and scripts to automate the data loading process.

## Requirements

- Python 3.x
- Jupyter Notebook
- Neo4j, Pandas, OpenAI
- Neo4j AuraDB Account, OpenAI API Key
- Required Python packages (listed in `requirements.txt`)

## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/Vietnam-Petroleum-Institute-1/VPIINSDataProcessing4Graph.git
    cd VPIINSDataProcessing4Graph
    ```

2. Create a virtual environment (optional but recommended):
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Install Neo4j and ensure it's running.

## Usage

### Jupyter Notebooks

1. Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

2. Open the notebooks in the `notebooks/` directory in the following order:
    - `create_cypher.ipynb`: Process raw data to Nodes.
    - `create_relations.ipynb`: Process raw data to Relationships.
    - `neo4j_loader.ipynb`: Load the generated CYPHER queries into Neo4j.
    - `neo4j_online.ipynb`: Load the generated CYPHER queries into Neo4j.
    - `query_neo4j.ipynb`: Querying the Neo4j DB using nature language.


## Contributing

Contributions are welcome! Please open an issue or submit a pull request with your improvements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

