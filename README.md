# 📊 Quality of Earnings Analyzer

Python-Tool zur automatisierten Quality of Earnings (QoE) Analyse — 
Kernbestandteil jeder Financial Due Diligence.

## Was das Tool macht

1. **Ticker eingeben** — beliebiges börsennotiertes Unternehmen (z.B. SIE.DE, BMW.DE)
2. **QoE-Kennzahlen** — berechnet Gross Margin, EBIT Margin und Cash Conversion über 4 Jahre
3. **QoE Score** — automatisierter 0-100 Score zur Bewertung der Earnings Quality
4. **Excel-Export** — professionell formatierter DD-ready Report

## Beispiel-Output: Siemens AG
```
Gross Margin:      38,5–39,3%  (stabil → positives Signal)
EBIT Margin:       10,9–15,8%  (steigender Trend)
Cash Conversion:   1,38–2,75x  (>1,0 = Gewinne sind echter Cash)
Free Cash Flow:    €8,1–10,8 Mrd. (wachsend, positiv)

QoE Score:   90/100
QoE Rating:  HIGH ✅ — Earnings appear sustainable and reliable
```

## Installation
```bash
pip install yfinance pandas numpy openpyxl
python qoe_analyzer.py
```

## Tech-Stack
- Python 3.9+
- yfinance, pandas, numpy, openpyxl

---
*Erstellt von Daniel Reiger | Lernprojekt Transaction Services & Financial Due Diligence*
