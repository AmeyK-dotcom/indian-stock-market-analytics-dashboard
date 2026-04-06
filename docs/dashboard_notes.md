# 📊 Dashboard Design Notes

This document explains the structure, design logic, and visualization choices used in the Indian Stock Market Analytics Dashboard.

---

## 🧱 Dashboard Layout

The dashboard is designed in a **3-layer structure** to mimic real-world financial analytics tools.

### 🔹 Top Section (Summary View)

- **Signal Distribution (Pie Chart)**
  - Shows overall market sentiment
  - Distribution of BUY / SELL / HOLD signals

- **Stock Risk Ranking (Volatility Bar Chart)**
  - Displays volatility of each stock
  - Sorted in descending order
  - Helps identify high-risk stocks

---

### 🔹 Middle Section (Core Analysis)

- **Price Trend & Moving Average Signals**
  - Line chart with:
    - Close Price
    - MA 7
    - MA 30
  - Price line is colored based on trading signals
  - Serves as the **main (hero) chart**

---

### 🔹 Bottom Section (Deep Analysis)

- **Market Returns Movement**
  - Multi-line chart showing daily returns
  - Represents overall market volatility

- **Performance Heatmap**
  - Stock vs Date grid
  - Color-coded daily returns
  - Red → Negative | Green → Positive
  - Provides pattern recognition across stocks

- **Risk vs Return Analysis (Scatter Plot)**
  - X-axis: Volatility (Risk)
  - Y-axis: Average Return
  - Color: Return (Red–White–Green)
  - Size (optional): Volatility
  - Used for portfolio-level decision making

---

## 🎨 Color Design

Consistent color logic is used across all charts:

### 📈 Trading Signals
- STRONG BUY → Dark Green  
- BUY → Light Green  
- HOLD → Grey  
- SELL → Orange  
- STRONG SELL → Red  

### 📊 Returns & Heatmap
- Red → Negative returns  
- White → Neutral  
- Green → Positive returns  

---

## 📐 Dashboard Size

- Recommended size: **1400 x 900**
- Fixed size ensures proper layout and readability

---

## 🧠 Design Principles

- **Hierarchy First**  
  → Price chart is the most important visual

- **Density Over Simplicity**  
  → Multiple charts provide deeper insights

- **Consistency in Colors**  
  → Same logic across all sheets

- **Minimal Clutter**  
  → Remove unnecessary gridlines and labels

- **Balanced Layout**  
  → Equal spacing using containers

---

## ⚙️ Tableau Implementation Notes

- Use **containers (horizontal + vertical)** for layout
- Avoid floating elements
- Keep all sheets **connected to a single data source**
- Ensure filters are applied to all sheets

---

## 🔍 Analytical Focus

This dashboard focuses on:

- Trend Analysis (Moving Averages)
- Risk Measurement (Volatility)
- Signal Generation (MA crossover logic)
- Performance Comparison (Heatmap & Returns)
- Portfolio Insights (Risk vs Return)

---

## 🚀 Future Enhancements

- Add RSI (Relative Strength Index)
- Add MACD indicator
- Integrate real-time data
- Add sector-wise analysis
- Build predictive model for signals

---
