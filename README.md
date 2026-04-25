# PoznejFI

# Abstrakt:
Zajímá Vás, jak v digitálním světě skutečně ověřujeme identitu? Společně se podíváme na to, jak funguje autentizace v praxi – od hesel přes biometriku až po moderní dvoufaktorové metody. Ukážeme si, proč lidé stále volí slabá hesla, jak se ukládají pomocí hashovacích funkcí a jak je útočníci dokážou prolomit.

Na konkrétních příkladech si vyzkoušíte limity biometrie: pochopíte, jak funguje rozpoznávání otisků prstů a proč ani tato technologie není neprůstřelná. Uvidíte, jak lze otisk získat a zneužít, a proč je potřeba kombinovat více faktorů autentizace.

Dále si vysvětlíme principy dvoufaktorové autentizace (např. mobilní aplikace generující jednorázové kódy) a ukážeme, jak zvyšují bezpečnost účtů. Nakonec se podíváme na základy bezpečné komunikace: digitální podpisy, certifikáty a šifrování – tedy technologie stojící za „zámkem“ v prohlížeči i za systémy jako Bitcoin.

Cílem je pochopit nejen jak věci fungují, ale hlavně kde jsou jejich limity – a jak se v digitálním světě skutečně chránit.

Workshop notebooks for the FI MUNI security lab.

| Notebook | Topic |
|---|---|
| `PoznejFI.ipynb` | Passwords, OTP, certificates|
| `biometrics.ipynb` | Reproduction of a real-world attack: fingerprint processing & fake-print DIY |

---

## Run without installation

Launch the notebooks directly in your browser — no setup needed:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sysox/PoznejFI/HEAD)

> **Note:** Binder works for `PoznejFI.ipynb` (passwords, OTP, certificates).  
> It is **not suitable** for `biometrics.ipynb`, which requires uploading your own finger photos and local hardware access.

---

## Requirements

- Python **3.10+**
- Jupyter Lab or Jupyter Notebook

---

## Quick start

```bash
bash StartNotebook_Linux_or_MacOS.sh
```

Jupyter Notebook opens in your browser automatically.

---

## Usage

1. Select kernel **Python (poznejfi)**.
2. Open a notebook and run cells top to bottom.

For `biometrics.ipynb`: put your finger photo(s) in the `data/` folder before starting.

The notebook reproduces the attack described in:
- BBC News — [Hacker 'fakes' German minister's fingerprints using photos](https://www.bbc.com/news/technology-30623611)
- Ars Technica — [Politician's fingerprint reproduced using photos of her hands](https://arstechnica.com/information-technology/2014/12/politicians-fingerprint-reproduced-using-photos-of-her-hands/)

---

## Keyboard shortcuts

| Shortcut | Action |
|---|---|
| `Ctrl + T` | Open a new terminal |
