# Komprese obrazu – SVD vs Wavelety

##  Popis projektu
Projekt porovnává dvě metody komprese obrazu:

- **SVD (Singular Value Decomposition)**
- **Waveletová transformace**

Vyhodnocuje se:
- kvalita rekonstrukce (PSNR),
- kompresní poměr,
- časová náročnost komprese a dekomprese.


## Spuštění projektu

Projekt je odevzdán jako **Jupyter Notebook**.

### 1️Požadavky

Je potřeba mít nainstalovaný **Python 3** a následující knihovny:

```bash
pip install numpy matplotlib opencv-python pywavelets
```

### 2️Spuštění notebooku

V terminálu:

```bash
jupyter notebook
```

Poté otevřít:

```
experiments.ipynb
```

A spustit celý notebook najednou:

**Kernel → Restart & Run All**

Notebook je připraven tak, aby běžel od začátku do konce bez úprav.


## Vstupní obrázky

Notebook pracuje se třemi testovacími obrazy:

- přirozený obraz  
- strukturovaný vzor  
- obraz se šumem  

Cesty k obrázům jsou nastaveny přímo v notebooku.


Notebook automaticky:

- provede SVD kompresi pro různé hodnoty parametru **k**
- provede waveletovou kompresi pro různé kompresní poměry
- spočítá **PSNR**
- spočítá **kompresní poměr**
- změří **čas komprese a rekonstrukce**
- vytvoří grafy a vizuální porovnání výsledků


Notebook je plně spustitelný a obsahuje všechny výpočty i vizualizace.
