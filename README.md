# Invisible Bridges of Credit: Exchange Rate Integration, Paper Assignats, and Metallic Anchors between St. Petersburg and Europe, 1763–1913

[![License: MIT](https://shields.io)](LICENSE)

This repository contains the reproducible Python/Jupyter pipeline, metallic parity calibrations, high-resolution figures, and LaTeX manuscript sources for the study:

> **Avtonomov, P. (2026c).** *Invisible Bridges of Credit: Exchange Rate Integration, Paper Assignats, and Metallic Anchors between St. Petersburg and Europe, 1763–1913.*

This work is the third study in a three-layer empirical research cycle auditing early modern and modern European market integration across commodity prices (`doi:10.5281/zenodo.24436177`), maritime shipping passages (`doi:10.5281/zenodo.24455763`), and foreign exchange markets.

## Key Empirical Findings
* **Metallic Anchors vs. Paper Assignat Depreciation (`1763–1913`, $T = 151$):** Paper *assignat* issuance after `1769` and Napoleonic war finance drove the St. Petersburg market exchange rate to `23.39` rubles per pound sterling in `1825` (`4.02x` its `18.0g` silver mint parity of `5.81` rubles/£), until Count Kankrin's `1839` monetary reform restored metallic parity (`6.08` rubles/£, `1.05x`). Following late-nineteenth-century global silver depreciation, Count Witte's `1897` gold reform anchored the ruble tightly at its statutory gold parity of `9.46` rubles/£ (`0.99–1.00x`).
* **Staged Financial Integration:** During the assignat era (`1764–1839`), Russia stood outside the Western European exchange rate core (`1.87%` of Mode 1 variance vs. `23.05%` for the Netherlands and `22.50%` for Germany; `Mode 2 = +0.503`). After Kankrin's stabilization (`1840–1896`), Russia's Mode 1 share jumped nearly eightfold to `14.62%`, culminating in broad network convergence under the classical gold standard (`1897–1913`, $\mathrm{PR}(v_1) = 0.778$).
* **Crisis Localization vs. Multi-Year Arbitrage:** In the uninterpolated post-Napoleonic panel (`1816–1913`, $M = 98$), `56.7%` of Mode 1 variance is localized in the `1816` post-Waterloo stabilization ($\mathrm{PR}(u_1) = 0.020$), while annual lead--lag cross-correlations (`±1`, `±2` years) between St. Petersburg and Western European hubs are statistically zero ($|r| \le 0.128, p > 0.21$).

## Repository Structure
* `reproduce_fx_study.ipynb` / `reproduce_fx_study.py` — End-to-end reproducible pipeline.
* `Figure_1_FX.png`, `Figure_2_FX.png` — High-resolution (`300 dpi`) figures.
* `paper/main.tex` & `paper/Invisible_Bridges_of_Credit.pdf` — Complete LaTeX source and compiled preprint.
* `ExchangeRatestoUKPound_Compact.xlsx`, `Silver_value_of_1273-1977.xls`, `Russia_Ag_content_ruble_1535-1913.xls` — Open-access Clio Infra and GPIHG source datasets.
