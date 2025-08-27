# big_data_programming
# Big Data Programming – MPG Prediction

📊 **Studienarbeit im Modul Big Data Programming (Sommersemester 2025)**  
Hochschule XYZ  

Ziel: Vorhersage des Kraftstoffverbrauchs (*miles per gallon, mpg*) auf Basis des **Auto-Datensatzes** aus *An Introduction to Statistical Learning (ISLR)*.  
Vergleich klassischer lineare Regression mit skalierbaren Methoden (**pandas vs. Dask**).

---

## Inhalte
- Explorative Datenanalyse (EDA)
- Feature Engineering & Preprocessing
- Lineare Regression (scikit-learn + eigene Least-Squares-Implementierung)
- Cross-Validation & Modellbewertung (MAE, RMSE, R²)
- Big Data Skalierung: Performance-Vergleich pandas vs. Dask (~40k Zeilen)

---

## Ergebnisse (Kurzfassung)
- **Train/Test-Split:** MAE ≈ 3.0 mpg · R² ≈ 0.70  
- **Cross-Validation (5-fach):** MAE ≈ 3.64 mpg · R² ≈ 0.40  
- **Skalierung:** pandas und Dask liefern identische Ergebnisse; Dask bringt bei ~40k Zeilen keinen Vorteil → lohnt sich erst bei sehr großen Datenmengen.  
- **Fazit:** Das lineare Modell bildet erste Zusammenhänge ab, ist aber in der Generalisierung begrenzt. Für bessere Ergebnisse wären Feature-Auswahl und alternative Modellansätze nötig.

---

## Dateien
- 📄 `Public_Version.pdf` → Bereinigte Studienarbeit  
- 📓 `notebooks/analysis.ipynb` → Vollständige Analyse in Jupyter Notebook  
