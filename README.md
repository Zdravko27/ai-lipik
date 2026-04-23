# AI Receipt Expense Analyzer

## Problem i cilj
Ručno prepisivanje računa u Excel je sporo i sklono greškama. Cilj projekta je:
- automatski pročitati račune (OCR)
- izvući stavke i iznose
- klasificirati troškove u kategorije (Food, Drinks, Hygiene, ...)

## Podaci
- Dataset: ExpressExpense Large Receipt Image Dataset (SRD)
- Link: [ExpressExpense – FREE Receipt Images](https://expressexpense.com/datasets/receipts.zip)
- Sadrži ~200 slika računa (restorani), s nazivom trgovine, stavkama, cijenama, porezom i totalom.

## Što model radi
1. OCR nad slikama računa
2. Parsiranje linija s cijenama
3. Izgradnja tablice artikala
4. Treniranje ML modela za klasifikaciju kategorije troška
5. Predikcija kategorije za nove račune

## Kako pokrenuti projekt

### 1. Kloniranje
```bash
git clone https://github.com/<username>/ai-receipt-expense-analyzer.git
cd ai-receipt-expense-analyzer
