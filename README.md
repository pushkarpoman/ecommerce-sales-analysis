# E-Commerce Sales Analysis
### Identifying profit drivers and loss sources in US retail data

---

## Project Overview
Analyzed 10,000+ rows of US e-commerce order data (2014–2017) to uncover
which products, regions, and customer segments drive profit — and which
ones destroy it despite generating revenue.

## Dataset
- **Source:** Sample Superstore Dataset (Kaggle)
- **Rows:** 9,994 orders
- **Columns:** 21 features (order date, category, region, sales, profit, discount, etc.)

## Tools & Libraries
| Tool | Purpose |
|------|---------|
| Python 3.11 | Core language |
| pandas | Data loading, cleaning, analysis |
| numpy | Numerical operations |
| matplotlib | Chart creation |
| seaborn | Statistical visualizations |
| VS Code + Jupyter | Development environment |

## Key Findings
1. **Technology = 50%+ of profit** on only 36% of sales — highest efficiency category
2. **Discounts above 20% produce negative profit** — a hidden margin killer
3. **Tables & Bookcases lose money** combined ($64K+ negative profit)
4. **West region has highest ROI** among all four regions
5. **Q4 sales are ~40% above average** — clear seasonal pattern

## Recommendations
- Cap all discounts at 20% maximum across the business
- Review pricing on Furniture sub-categories (Tables, Bookcases)
- Reallocate marketing toward Technology products in West region
- Begin Q4 inventory buildup in September

## Project Structure


## How to Run
```bash
git clone https://github.com/YOURNAME/ecommerce-sales-analysis
cd ecommerce-sales-analysis
pip install -r requirements.txt
jupyter notebook analysis.ipynb
```

---
Project by Pushkar Poman
"""

with open('README.md', 'w') as f:
    f.write(readme)

print("README.md written successfully!")

requirements = """pandas>=2.0.0
numpy>=1.24.0
matplotlib>=3.7.0
seaborn>=0.12.0
openpyxl>=3.1.0
jupyter>=1.0.0
"""

with open('requirements.txt', 'w') as f:
    f.write(requirements)

print("requirements.txt written!")
