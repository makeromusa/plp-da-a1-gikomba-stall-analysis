# Gikomba Market Stall Performance Analysis

**Author:** Asman Makero Musa  
**Cohort:** PLP Data Analytics Cohort 7  
**Repository:** [plp-da-a1-gikomba-stall-analysis](https://github.com/makeromusa/plp-da-a1-gikomba-stall-analysis)

---

## Business Problem Summary

Wanjiku operates a fresh-produce retail stall at the bustling Gikomba Market in Nairobi, Kenya. For the past two weeks (14 days), she recorded her daily sales figures in a physical notebook and tracked stock levels across five key produce lines (Tomatoes, Onions, Sukuma, Potatoes, and Avocado). To transition from guesswork to data-driven operational decision-making, Wanjiku engaged a freelance data analyst to evaluate her overall business health, measure week-on-week revenue momentum, audit inventory against reorder safety thresholds, identify profit margins, and provide actionable strategies to eliminate stock-outs and maximize profitability.

---

## How to Run

Open the analysis notebook directly in Google Colab and run all cells sequentially via **Runtime → Run all** (or press `Ctrl + F9`):

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/makeromusa/plp-da-a1-gikomba-stall-analysis/blob/main/stall_analysis.ipynb)

*(Alternatively, clone this repository locally and run `stall_analysis.ipynb` using Jupyter Notebook, JupyterLab, or VS Code with standard Python 3.x — no external libraries such as pandas or NumPy are required.)*

---

## Top Three Findings

1. **Massive Weekend Sales Premium (+82.50%)**: Weekend sales averaged **KES 4,900.00** across Saturday and Sunday compared to the weekday average of **KES 2,685.00** across Monday to Friday, peaking on Saturday of Week 2 at **KES 5,600.00**.
2. **Positive Week-on-Week Revenue Growth (+10.66%)**: Total sales revenue grew from **KES 22,050.00** in Week 1 to **KES 24,400.00** in Week 2, delivering a net revenue expansion of **KES 2,350.00** and bringing total 14-day sales to **KES 46,450.00**.
3. **Critical Reorder Deficit in High-Margin Produce**: Two core commodities have fallen below safety inventory thresholds: **Tomatoes** (18 kg on hand vs. 25 kg reorder level; 33.3% margin) and **Sukuma** (9 kg on hand vs. 15 kg reorder level; 40.0% margin), posing immediate stock-out risks during peak shopping periods.

---

## Project Structure

```text
plp-da-a1-gikomba-stall-analysis/
├── README.md               # Executive summary, business context, run instructions, top findings
└── stall_analysis.ipynb    # Complete analysis notebook with executed outputs (Tasks 1–7)
```
