# 📊 NPV & IRR Calculator (Project Comparison Tool)

A Python-based financial analysis tool that calculates Net Present Value (NPV) and Internal Rate of Return (IRR) for investment projects and compares them to support better financial decision-making.

This project is implemented in Python and was developed using Google Colab.

---

## 📌 Features

- Calculates Net Present Value (NPV)
- Calculates Internal Rate of Return (IRR)
- Compares two investment projects
- Provides recommendation based on NPV
- Simple and beginner-friendly Python implementation

---

## 🧠 Financial Concepts Used

Net Present Value (NPV)  
Measures the profitability of a project by discounting future cash flows.

Internal Rate of Return (IRR)  
The discount rate at which the NPV of a project becomes zero.

These concepts are widely used in capital budgeting and investment analysis.

---

## 🛠️ Technologies Used

- Python 3
- Google Colab
- Jupyter Notebook

---

## 📂 Project Structure

- Untitled0.ipynb   → Main Google Colab notebook
- README.md         → Project documentation

---

## ▶️ How to Run the Project

Google Colab:
1. Open Google Colab
2. Upload Untitled0.ipynb
3. Run all cells

Local Machine:
1. Install Python 3
2. Open the notebook using Jupyter Notebook
3. Run all cells

---

## 🧮 Example Cash Flows Used

Project A:
-1000, 300, 300, 300, 300, 300

Project B:
-1200, 400, 400, 400, 300, 300

Discount Rate:
0.08

---

## 📈 Sample Output

Project A - NPV: 196.27 | IRR: 18.95%  
Project B - NPV: 203.41 | IRR: 17.86%  
Project B is better based on NPV.

---

## 🧩 Core Functions

npv(cashflows, rate)  
Calculates the Net Present Value of a project.

irr(cashflows)  
Calculates the Internal Rate of Return using an iterative numerical method.


