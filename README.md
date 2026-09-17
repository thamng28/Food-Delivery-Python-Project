# Global Restaurant & Food Delivery Intelligence Analysis

An end-to-end data analytics project evaluating operational logistics, pricing mechanics, and nutritional menu engineering across global food delivery platforms.

---

## Executive Summary

This project investigates core business dynamics in food delivery platforms by analyzing relational dataset records spanning restaurants, delivery performance metrics, pricing structures, and item-level nutritional data.

### Key Findings
* **Operational Bottlenecks & Surge Pricing:** High peak-hour surge multipliers (>1.5x) correlate with statistically significant increases in delivery delays ($p = 1.27 \times 10^{-218}$ via Mann-Whitney U test), while baseline delivery variance is driven by local metropolitan infrastructure rather than weather patterns.
* **Customer Rating Resilience:** Operational delivery delays exhibit no statistically significant relationship with customer restaurant ratings (Spearman $r = 0.032, p = 0.217$). Consumers separate platform-side logistics from restaurant product quality.
* **Amenity Independence:** Point-biserial correlation analysis demonstrates that physical restaurant amenities (e.g., WiFi, outdoor seating, parking) do not command measurable digital price premiums.
* **Menu Engineering Polarization:** Catalog segmentation reveals extreme inventory clustering in two quadrants: `Low Price / High Protein` (~28,950 items) and `High Price / Low Protein` (~28,950 items), exposing an under-supplied commercial opportunity in the `High Price / High Protein` tier (~2,250 items).

---

## Repository Structure

```text
├── Food Delivery Project.ipynb   # Main Jupyter Notebook containing EDA, statistical tests, and visualizations
├── data/                         # Relational CSV tables (restaurants, menus, delivery_metrics, etc.)
└── README.md                     # Project overview and executive summary
