# 🛒 E-Commerce Price Intelligence Engine
### Flipkart vs Amazon India — Built with Pure NumPy

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![NumPy](https://img.shields.io/badge/NumPy-1.26-orange)
![Status](https://img.shields.io/badge/Status-Complete-green)
![Dataset](https://img.shields.io/badge/Products-20-purple)

> "Which platform is actually cheaper?" — I built a NumPy engine to find out.

---

## 🎯 Business Problem

Indian consumers split their shopping across Flipkart and Amazon 
without a systematic way to know which platform wins on price — 
by category, by product type, and in total.

This project builds a **price intelligence engine** using pure NumPy 
that answers exactly that.

---

## 📊 What This Project Does

| Analysis | What It Finds |
|---|---|
| Price Diff Scanner | ₹ and % difference for every product |
| Category Winner | Which platform wins Audio / Mobile / Laptop / Appliances |
| Statistical Profile | Mean, Median, Std Dev per platform |
| Smart Buyer Algorithm | Optimal platform per product to minimise spend |
| Big Deal Detector | Products with >3% price gap — real savings opportunities |

---

## 🔑 Key Findings

- 💡 Smart shopping across both platforms saves ₹X,XXX vs sticking to one
- 📱 Amazon wins on Mobiles; Flipkart wins on Audio
- 💻 Laptop prices are virtually identical (< 2% avg gap)
- 🔥 Biggest deal: [product] is X% cheaper on [platform]

---

## 🧠 NumPy Concepts Demonstrated
```python
np.array()        # Structured datasets — products, prices, categories
Boolean indexing  # categories == "Mobile" — filter without loops
np.where()        # Smart buyer decision logic across 20 products
np.mean/std       # Platform-level statistical profiling
np.minimum()      # Element-wise best price selection
Broadcasting      # % difference across entire array in one line
```

---

## 📁 Files
📦 ecommerce-price-intelligence-numpy
┣ 📓 price_intelligence.ipynb   ← Main Colab notebook
┣ 📄 README.md
┗ 📊 sample_output.png          ← Screenshot of results--

## 📁 Files
