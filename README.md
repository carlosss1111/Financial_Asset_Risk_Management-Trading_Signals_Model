[![DOI](https://zenodo.org/badge/1172849598.svg)](https://doi.org/10.5281/zenodo.18868266)

# Financial Asset Risk Management and Trading Signals Model

This repository contains the reproducible code used in the financial experiment and the trading signals model presented in the article:

**“A unifying approach to orders on hesitant fuzzy elements with applications to financial risk management and trading signals.”**

The goal of the experiment is to illustrate how order-based comparisons of hesitant fuzzy elements can be applied to model **financial stress and switching decisions between Bitcoin and Ethereum**. 

The goal of the trading signal model is to get trading signals (BUY/SELL/HOLD) from (α, k)-cuts on finite interval-valued hesitant fuzzy numbers.

The repository includes the implementation used to:

- construct the hesitant fuzzy representations of market stress,
- compute order-based comparisons,
- generate switching decisions between BTC and ETH,
- reproduce the trading signal experiment reported in the paper.

---

## Repository structure

The repository currently contains:

- `Financial_Asset_Risk_Management_BTCvsETH.ipynb`  
  Main notebook implementing the financial risk experiment.

- `Trading_Signals_Model.ipynb`  
  Notebook implementing the trading signal generation model.

- `LICENSE`  
  MIT license for the code.

---

## Reproducibility

The experiments are fully reproducible.

To run the notebooks you only need a standard Python environment with common scientific libraries (NumPy, Pandas, Matplotlib).

The notebooks can also be executed directly in **Google Colab**.

---

## Related article

This code accompanies the research article:

*Carlos Salvatierra, Pedro Huidobro*

"A unifying approach to orders on hesitant fuzzy elements with applications to financial risk management and trading signals."

---

## License

This project is released under the **MIT License**.
