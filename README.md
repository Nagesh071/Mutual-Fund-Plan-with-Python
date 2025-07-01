# Creating a Mutual Fund Investment Simulator in Python

**A comprehensive, hands-on Jupyter Notebook project** to design, simulate, and visualize Systematic Investment Plans (SIPs) for mutual funds using real NAV (Net Asset Value) data.

---

## 🚀 Project Overview

Retail investors often find it challenging to forecast and compare long-term mutual fund performance. This notebook bridges that gap by:

* **Ingesting** historical NAV data for multiple mutual funds
* **Computing** key metrics (CAGR, volatility, max drawdown)
* **Modeling** periodic SIP contributions over custom time horizons
* **Visualizing** portfolio growth curves and comparative performance
* **Exporting** simulation results for reporting

By the end of this tutorial, you’ll have a reusable Python framework to evaluate different funds and SIP strategies.

---

## 🔍 Repository Structure

```text
mutual-fund-simulator/             # Root directory
├── data/                          # Sample NAV CSV files
├── notebooks/                     # Jupyter Notebooks
│   └── sip_simulator.ipynb        # Main analysis & simulation workflow
├── src/                           # Python modules (data loader, metrics, visuals)
│   ├── loader.py
│   ├── metrics.py
│   └── simulation.py
├── requirements.txt               # Python dependencies
└── README.md                      # Project overview and instructions
```

---

## 🛠️ Installation & Setup

1. **Clone the repository**:

   ```bash
   git clone https://github.com/<your-username>/mutual-fund-simulator.git
   cd mutual-fund-simulator
   ```

2. **Create and activate a virtual environment** (recommended):

   ```bash
   python3 -m venv venv
   source venv/bin/activate    # Linux/macOS
   venv\Scripts\activate     # Windows
   ```

3. **Install required packages**:

   ```bash
   pip install -r requirements.txt
   ```

4. **Launch Jupyter Notebook**:

   ```bash
   jupyter notebook notebooks/sip_simulator.ipynb
   ```

---

## ⚙️ Usage Guide

1. **Load NAV data**: Place your CSV files in the `data/` folder. Each file should contain `Date` and `NAV` columns.
2. **Configure parameters**: In the notebook, set:

   * Fund CSV filenames
   * SIP amount and frequency (e.g., monthly)
   * Investment start and end dates
3. **Run simulation cells**: Execute step-by-step to:

   * Clean and align time series
   * Calculate periodic investments and compounding
   * Compute performance metrics
4. **Visualize results**: Generate growth curves, drawdown charts, and comparative bar plots.
5. **Export outputs**: Save results to CSV or PNG for reporting.

---

## 📈 Key Features

* **Modular code**: Separate loader, metrics, and simulation modules for easy reuse
* **Customizable**: Adjust SIP schedules, timeframes, and fund lists
* **Interactive analysis**: Leverage Jupyter widgets to tweak parameters on-the-fly
* **Insightful visuals**: Publication-ready Matplotlib charts

---

## 🤝 Contributing

Contributions are welcome! To propose new features or report issues:

1. **Fork** the repository
2. **Create a feature branch**: `git checkout -b feature/awesome-feature`
3. **Commit your changes**: `git commit -m "Add awesome feature"`
4. **Push to your branch**: `git push origin feature/awesome-feature`
5. **Open a Pull Request**

Please ensure all new code includes unit tests and follows PEP8 style guidelines.

---

## 📄 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## 📬 Contact & Support

For questions or support, please reach out to:

* **Maintainer**: Bhukya Nagesh ([bhukyanagesh444@gmail.com](mailto:bhukyanagesh444@gmail.com))
* **GitHub Issues**: [https://github.com/](https://github.com/)<your-username>/mutual-fund-simulator/issues

Happy investing! 📊
