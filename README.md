# Another Marčenko-Pastur law for Kendall's tau

Code used in our paper: [![arXiv](https://img.shields.io/badge/arXiv-2503.18645-b31b1b.svg)](https://arxiv.org/abs/2503.18645) P. Bousseyroux, T. Espana, M. Smerlak (2025). 

Published in *Electronic Communications in Probability (ECP)*.

## 📄 Abstract

Bandeira et al. (2017) show that the eigenvalues of the Kendall correlation matrix of n i.i.d. random vectors in $`\mathbb{R}^p`$ are asymptotically distributed like $`1/3 + (2/3)Y_q`$, where $`Y_q`$ has a Marčenko-Pastur law with parameter $`q=\lim(p/n)`$ if $`p, n\to\infty`$ proportionately to one another. Here we show that another Marčenko-Pastur law emerges in the "ultra-high dimensional" scaling limit where $`p\sim q'\, n^2/2`$ for some $`q'>0`$: in this quadratic scaling regime, Kendall correlation eigenvalues converge weakly almost surely to $`(1/3)Y_{q'}`$.

## 🚀 Setup Instructions

### 1. Clone the repo

```bash
git clone https://github.com/TomasEspana/kendall_eigenvalues.git
cd kendall_eigenvalues
```

### 2. Virtual env and dependencies

```bash
python -m venv .venv
# macOS / Linux
source .venv/bin/activate
# Windows (PowerShell)
# .\.venv\Scripts\activate
python -m pip install --upgrade pip
pip install -r requirements.txt
python -m pip install -e .
```

### 3. Run the notebook `main.ipynb`. 