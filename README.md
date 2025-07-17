# 🛒 This Shows The Frequent Itemsets Analysis in Supermarket Transactions

This project explores frequent itemsets in supermarket transaction data using classic data mining techniques. The workflow involves simulating transactions, performing one-hot encoding, and applying algorithms to discover frequent, closed, and maximal itemsets.

---

## 👥 Each Group Member and Their Responsibility

| Name of Member | Their Contribution |
|-------------|--------------|
| Samuel      | Data simulation, transaction file generation |
| Ambachow    | One-hot encoding, CSV handling, README documentation |
| Paul        | Frequent itemsets mining (Apriori algorithm) |
| Randy       | Closed frequent itemsets interpretation |
| Justus      | Maximal frequent itemsets generation |
| Gathogo     | CSV file saving and output management |

---

## 📁 File Structure

### Folder Tree


### File Descriptions

| File Name                        | Description                                             |
|----------------------------------|---------------------------------------------------------|
| `frequent_itemsets_analysis.ipynb` | Jupyter Notebook containing all code and analysis      |
| `supermarket_transactions.csv`     | Simulated raw transaction dataset                      |
| `supermarket_one_hot_encoded.csv`  | One-hot encoded version of the transactions            |
| `README.md`                        | Project documentation including team contributions     |
| `.gitignore`                       | Specifies files and folders to be ignored by Git       |

---

## 🧠 The Project Overview

- Simulated transactional dataset representing items bought by different customers
- Converted dataset into one-hot encoded format for compatibility with mining algorithms
- Performed analysis using the **Apriori algorithm** to generate:
  - Frequent Itemsets
  - Closed Frequent Itemsets
  - Maximal Frequent Itemsets
- Interpreted results to understand purchasing patterns
- Exported cleaned and encoded data to `.csv` for future use

---

## 🧰 Requirements

- python 3.x
- jupyter notebook
- `pandas`
- `mlxtend`

> All dependencies can be installed via pip:
```bash
pip install pandas mlxtend
