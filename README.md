# Customer Segmentation Analysis
## Project Overview
I analyzed 500,000+ real transactions to understand customer 
buying behavior and help businesses make smarter marketing 
decisions. This project identifies VIP customers, at-risk 
customers, and lost customers so marketing teams can take 
the right action for each group.

## Business Problem
Most businesses treat all customers the same way. This project identifies which customers are VIPs, which are at risk of leaving, and which are already lost — so marketing teams can take the right action for each group

##  Key Findings
- Analyzed **541,909 transactions** from 4,320 unique customers
- Identified **6 RFM segments** based on buying behavior
- Applied **K-Means clustering** to find 4 natural customer groups
- Found **6 VIP customers** generating avg £182,182 each!
- **1,062 lost customers** who need win-back campaigns

## Visualizations

### Customer Segments Distribution
![Customer Segments](outputs/figures/customer_segments.png)

### Revenue by Segment
![Revenue by Segment](outputs/figures/revenue_by_segment.png)

### RFM Heatmap
![RFM Heatmap](outputs/figures/rfm_heatmap.png)

### K-Means Clusters
![KMeans Clusters](outputs/figures/kmeans_clusters.png)

## Business Recommendations

| Segment | Customers | Strategy | Expected Impact |
|---------|-----------|----------|-----------------|
| VIP Champions | 6 | Personal account manager + early access to new products | Retain £182K avg spend |
| Loyal High Spenders | 110 | Exclusive membership + free shipping | Increase order frequency |
| Regular Customers | 3,142 | Bundle offers + loyalty points | Increase basket size |
| Lost Customers | 1,062 | Win-back email with 20% discount after 6 months inactive | Recover 10-15% customers |


## Tools Used
- Python, Pandas, NumPy
- Scikit-learn (K-Means)
- Matplotlib, Seaborn
- Jupyter Notebook

## Project Structure
```
customer_segmentation/
├── data/
│   ├── raw/          # Original dataset
│   └── processed/    # Cleaned & analyzed data
├── notebooks/        # Analysis notebooks
├── outputs/figures/  # All visualizations
└── README.md
```

## How to Run
1. Clone this repository
2. Install requirements: `pip install -r requirements.txt`
3. Run notebooks in order (01 → 05)


## About This Project
This is a personal project I built to demonstrate real-world 
data analysis skills. The entire pipeline — from raw data 
to business insights — was built from scratch using Python.