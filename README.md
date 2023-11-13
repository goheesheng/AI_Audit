# AI_Audit

# Langchain AI Model for Smart Contract Analysis and Vulnerability Detection

## Introduction

Welcome to Langchain, a powerful tool for building AI models to analyze smart contracts and scrape data on vulnerabilities. This README will guide you through the process of setting up the Langchain environment, utilizing open-source data sources such as Spearbit and ConsenSys, and combining them into a vector database. Additionally, we'll explore the integration of the FAISS search engine by Facebook for efficient querying.

#### P.S This was done a year ago, and I forgotten to upload to this repo, do update if required!

## Prerequisites

Before you begin, ensure that you have the following installed on your machine:

- Python 3.x
- Pip (Python package installer)
- Git

## Getting Started

1. Clone the Langchain repository to your local machine:

   ```bash
   git clone https://github.com/your-username/langchain.git
   ```

2. Navigate to the Langchain project directory:

   ```bash
   cd langchain
   ```

3. Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

## Data Collection

Langchain leverages open-source data on vulnerabilities, including Spearbit and ConsenSys. Ensure that you have access to these datasets or replace them with your preferred data sources.

### Spearbit

Visit the [Spearbit GitHub repository](https://github.com/spearbit) to obtain the latest version of the Spearbit dataset. Follow the provided instructions to download and preprocess the data.

### ConsenSys

Explore the [ConsenSys GitHub repository](https://github.com/consensys) for smart contract vulnerability data. Download and preprocess the ConsenSys dataset according to the provided guidelines.

## Building the Vector Database

Combine the processed data from Spearbit and ConsenSys into a unified vector database. Use the provided scripts in the `data_processing` directory to achieve this.

```bash
python data_processing/combine_data.py
```

## Integrating FAISS Search Engine

Langchain employs the FAISS search engine by Facebook for efficient and fast vector searches. Follow these steps to integrate FAISS into your project:

1. Download and install FAISS from the [official GitHub repository](https://github.com/facebookresearch/faiss).

2. Integrate FAISS into your Langchain project by updating the necessary configurations in the `config.yaml` file.

3. Implement FAISS-based search functionality using the provided scripts in the `faiss_integration` directory.

## Running the Langchain AI Model

Execute the Langchain AI model to analyze smart contracts and detect vulnerabilities:

```bash
python langchain_model.py
```

## Contributions

We welcome contributions from the community! If you discover issues or have suggestions for improvements, please open a GitHub issue or submit a pull request.

## Acknowledgments

Langchain acknowledges and appreciates the contributions of the open-source communities behind Spearbit, ConsenSys, and FAISS.

Happy coding! 🚀
