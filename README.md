# TaxMate - Your AI-Powered Tax Assistant

## Overview

TaxMate is an AI-powered tax planning assistant designed to automate tax filing processes, simplify complex calculations, identify deductions, and minimize errors. Built using cutting-edge technologies such as Large Language Models (LLMs) and Retrieval-Augmented Generation (RAG), TaxMate provides personalized tax-saving strategies tailored to your financial data.

This project is developed for **Google Girl Hackathon 2025**, under the problem statement:

> "A Tax Assistant that can automate tax filing processes, simplifying complex calculations, identifying deductions, and minimizing errors."

## Features

- **Automated Tax Optimization**: Offers automatic suggestions for tax savings using the user’s financial information.
- **Streamlined Taxes**: Employs AI to analyze and break down complex tax laws.
- **Analytics**: Uses income, expenditure, and deductions to achieve maximum tax benefits.
- **Easy and Secure**:  Guarantees data and privacy protection through strengthened encryption.
- **Fast and Efficient**: Everything is done in one click with the help of a vector database (Chroma DB), which enables speedy storage and retrieval of financial data.

## Technologies Used

- **Python**
- **Hugging Face Transformers (Zephyr-7b-beta)**
- **Langchain**
- **Chroma DB (Vector Database)**
- **NumPy & Pandas**
- **Faker (For Data Simulation)**

## Getting Started

### Prerequisites

Ensure you have the following installed:

- Python (>=3.8)
- pip
- Jupyter Notebook (if running interactively)

### Installation

```sh
# Clone this repository
git clone https://github.com/krishikamehta/TaxMate-GGH-2025.git
cd TaxMate-GGH-2025

# Create a virtual environment
python -m venv env
source env/bin/activate   # On Windows use: env\Scripts\activate

# Install dependencies
pip install -r requirements.txt

## Running TaxMate

### 1. Run the Jupyter Notebook

```sh
jupyter notebook TaxMate.ipynb

## Usage

1. Enter your **income, expenses and tax details** within the system.
2. The AI will parse your finances and offer **tailored strategies for your tax saving measures**.
3. Go over suggestions to counsel them to your liking before moving on to the filing of your taxes.

## Project Architecture

1. **Data Collection**: Safely collects income, expenditure, and tax information.
2. **Data Processing**: Cleans, normalizes, and extracts useful financial features.
3. **AI Processing**:
   - Fetches tax laws from **Chroma DB**.
   - Utilizes **LLM (Zephyr-7b-beta)** to create customized tax-saving plans.
4. **Output & Insights**: Shows easy-to-understand tax suggestions and deductions.

## Example Output

```plaintext
Tax Summary for 2024:
- Estimated Taxable Income: $50,000
- Potential Deductions: $5,000 (Investments, Health Insurance, etc.)
- Recommended Tax Savings: $1,200

## Limitations

- Tax laws often change, and revisions are needed to ensure accuracy.
- Personalized suggestions rely on the quality of input data.
- Though AI gives insights, **you should consult a professional** in case of intricate tax situations.

### Contributors

**Krishika Mehta**

## Disclaimer

TaxMate is an AI-powered assistant intended for informational purposes only.  
Please consult a tax professional for official tax filings.


