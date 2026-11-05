# Apriori vs. FP-Growth Interactive Educational Visualizer

An interactive, self-contained educational bench designed to demystify Association Rule Mining (Market Basket Analysis) by running and comparing the **Apriori Algorithm** and the **FP-growth (Frequent Pattern Growth) Algorithm** side-by-side in real time.

Built as a single-page, dependency-light web application utilizing **D3.js** for hierarchical tree visualization and **KaTeX** for mathematical typesetting.

---

## 🌟 Key Features

- **Side-by-Side Dual Execution:** Compare candidate generation ($C_k$) and frequent itemsets ($L_k$) in Apriori directly against FP-Growth's prefix tree and header-table construction.
- **Interactive FP-Tree (D3.js):** Full zoom, pan, and dynamic node highlighting with support for transaction step-throughs.
- **Reverse Rule-to-Tree Back-Tracing:** Click any derived association rule ($A \Rightarrow B$) to trace its exact conditional pattern base path directly on the FP-Tree (nodes dynamically turn blue with highlighted links).
- **Step-by-Step Mathematical Derivation:** Detailed modal breakdowns for Rule Support, Confidence, and Lift calculations with explicit fractional substitutions.
- **Dynamic Dataset Controls:** Adjust Minimum Support ($\text{min\_sup}$), Minimum Confidence ($\text{min\_conf}$), switch between retail presets, or build/edit custom transaction databases on the fly.
- **Telemetry & Complexity Audit:** Real-time metrics tracking database scans, candidate counts, and computational overhead.

---

## 🚀 Quick Start

No installation, backend, or build step required:

1. Clone this repository:
   ```bash
   git clone [https://github.com/](https://github.com/)<your-username>/<your-repo-name>.git

## Core Application Development: 
- Generated with the assistance of Gemini Flash 3.8.

> **Usage Disclaimer**: This tool is designed primarily for educational, exploratory, and conceptual demonstrations. While the step-by-step algorithms reflect standard textbook implementations of Apriori and FP-Growth, edge cases in extreme custom inputs may exist. Please use with caution in production or formal academic evaluation contexts.

## Contributing
Contributions, issues, and feature suggestions are welcome!
- Fork the Project
- Create your Feature Branch (git checkout -b feature/AmazingFeature)
- Commit your Changes (git commit -m 'Add some AmazingFeature')
- Push to the Branch (git push origin feature/AmazingFeature)
- Open a Pull Request
