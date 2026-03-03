Dieses Projekt prognostiziert den Erfolg von Telefonmarketing-Kampagnen zur Akquise von Termineinlagen bei einer portugiesischen Bank. Es entstand als Seminararbeit im Machine Learning Lab an der TH Ingolstadt.
📊 Kernpunkte

    Ziel: Binäre Klassifikation (Abo: Ja/Nein) zur Effizienzsteigerung der Akquise.

    Modelle: Vergleich von Logistischer Regression (Baseline), Random Forest und XGBoost.

    Preprocessing: Behandlung von Klassen-Ungleichgewicht, Entfernung von Data Leakage (duration) und Reduktion von Multikollinearität.

🏆 Ergebnisse

    Bestes Modell: Der optimierte XGBoost erzielte einen ROC AUC von 0,81.

    Performance: Ein Recall von 0,64 bei der Zielgruppe ermöglicht eine gezielte Kundenansprache.

    Wichtigste Treiber: Die Vorhersage wird primär durch makroökonomische Faktoren (besonders nr.employed) und die bisherige Kontakthistorie gesteuert.

🛠 Tech-Stack

    Sprache: Python (Pandas).

    Bibliotheken: Scikit-Learn (Pipeline, ColumnTransformer), XGBoost.
