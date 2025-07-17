# 🛒 Frequent Itemsets Analysis in Supermarket Transactions

This project explores frequent itemsets in supermarket transaction data using classic data mining techniques. The workflow involves simulating transactions, performing one-hot encoding, and applying algorithms to discover frequent, closed, and maximal itemsets.

---

## 👥 Group Members and Responsibilities

| Name       | Contribution                                      |
|------------|---------------------------------------------------|
| Samuel     | Data simulation, transaction file generation       |
| Ambachow   | One-hot encoding, CSV handling, README docs       |
| Paul       | Frequent itemsets mining (Apriori algorithm)      |
| Misati     | Closed frequent itemsets interpretation           |
| Justice    | Maximal frequent itemsets generation              |
| Gathogo    | CSV file saving and output management             |

---

## 📁 File Structure

| File Name                          | Description                                         |
|------------------------------------|-----------------------------------------------------|
| `frequent_itemsets_analysis.ipynb` | Jupyter Notebook with all code and analysis          |
| `supermarket_transactions.csv`     | Simulated raw transaction dataset                    |
| `supermarket_one_hot_encoded.csv`  | One-hot encoded version of the transactions          |
| `frequent_itemsets.csv`            | Output of Apriori frequent itemsets                  |
| `maximal_frequent_itemsets.csv`    | Maximal frequent itemsets                            |
| `README.md`                        | Project documentation                               |

---

## 🧠 Project Overview

- Simulate a transactional dataset representing items bought by different customers
- Convert dataset into one-hot encoded format for mining algorithms
- Analyze using the **Apriori algorithm** to generate:
  - Frequent Itemsets
  - Closed Frequent Itemsets
  - Maximal Frequent Itemsets
- Interpret results to understand purchasing patterns
- Export cleaned and encoded data to `.csv` for future use

---

## 🧰 Requirements

- Python 3.x
- Jupyter Notebook
- `pandas`
- `mlxtend`

Install dependencies with:
```bash
pip install pandas mlxtend
```

---

## 📤 Outputs
- `supermarket_transactions.csv`: Simulated transactions
- `supermarket_one_hot_encoded.csv`: One-hot encoded transactions
- `frequent_itemsets.csv`: Frequent itemsets
- `maximal_frequent_itemsets.csv`: Maximal frequent itemsets

---
