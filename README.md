# 💎 Multi-Diamond Carat Calculator

A professional Python-based tool to calculate total carat weight and price for multiple diamond or gemstone shapes.  
Supports **Princess, Baguette, Oval, Heart, and Marquise** cuts with automatic CSV export — designed for luxury jewelry businesses.

---

## ✨ Features

- 🔹 Supports multiple diamond/gem shapes:
  - Princess (P)
  - Baguette (B)
  - Oval (O)
  - Heart (H)
  - Marquise (M)
- 🔹 Calculates **individual and total carat weight**
- 🔹 Option to include **price per carat** for accurate total valuation
- 🔹 Exports all details (Shape, Dimensions, Quantity, Carat, Total Carat, Price) to CSV
- 🔹 Simple command-line interface — ideal for Google Colab or desktop Python
- 🔹 Designed and developed by **Ramprasad Ghosh — SVARNA Luxury Tools™**

---

## 🧮 Formula Reference

The tool uses standardized diamond shape factors for accurate estimation:

| Shape     | Factor |
|------------|---------|
| Princess   | 0.0060  |
| Baguette   | 0.0080  |
| Oval       | 0.0062  |
| Heart      | 0.0059  |
| Marquise   | 0.0058  |

These values represent shape-based proportional constants derived from standard diamond weight calculations.

---

## 🚀 How to Use

### 🧰 Option 1: Run in Google Colab
1. Open [Google Colab](https://colab.research.google.com/drive/1u51cA9YN2fQoT_GTonUJRKIVzZmCzAEB?usp=sharing).
2. Copy and paste the full script from this repository.
3. Run all cells.
4. Follow the prompts to:
   - Enter diamond/gem details (shape, size, depth, quantity)
   - Optionally add price per carat
   - Export the full summary to a downloadable CSV

### 💻 Option 2: Run Locally
```bash
python multi_diamond_carat_calculator.py


## 🏷️ License

This project is released under the **MIT License**.  
Attribution is appreciated:  
**Developed by Ramprasad Ghosh — SVARNA Luxury Tools™**
