# Connecting the optical and infrared

## 🚀 What’s this about?  
Galaxies aren’t just a random mashup of independent components — they are **deeply interconnected** ecosystems. However, traditional models still assume that optical and infrared (IR) emission come from separate, weakly linked processes. 
Here we show that **they do not.**  

This repo contains a Jupyter Notebook that demonstrates how to **disprove the old paradigm** by using a **data-driven model** to predict **infrared photometry** from optical spectra with **excellent accuracy** (we’re talking **(χ² ≈ 1** for all WISE bands!).  

## 💡 Why should you care?  
- **Unlock Hidden Insights** – We prove that the separability assumption in galaxy modeling is fundamentally flawed.
- **Traditional Models Can’t Compete** – Our empirical approach **outperforms traditional SED fitting methods**, which struggle to capture the strong correlations across wavelength regimes.
- **No IR Data? No Problem.** If you have optical spectra, you can now **predict IR-derived properties** like AGN bolometric luminosities, scaling relation, as well as dust parameters (e.g., \(\mathrm{q_{PAH}}\)) without breaking a sweat.  

## 📌 What’s inside this repo?  
- **Data** - Crossmatched optical and IR data
- **Jupyter Notebook** – A fully documented walkthrough to replicate our results.  
- **Data Preprocessing Steps** – So your input spectra are good to go. This consists of a robost **autoencoding** step. 
- **Model Training & Predictions** – Learn how to transform your optical spectra into IR photometry. However, the ML used here is extremely simple.  

## ⚡ Quickstart  
Clone the repo and fire up the notebook:  
```bash
git clone https://github.com/astrockragh/IR_optical_demo.git
cd IR_optical_demo
pip install -r requirements.txt
jupyter notebook IR_optical_demo.ipynb
```

You can also run this notebook in Google Colab, but make sure to install the ```requirements.txt```.

[![Open the notebook in Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/astrockragh/IR_optical_demo/blob/main/IR_optical_demo.ipynb)
