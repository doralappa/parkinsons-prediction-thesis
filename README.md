# parkinsons-prediction-thesis

Αυτό το repository περιλαμβάνει τον πλήρη πηγαίο κώδικα, τα notebooks και τις οπτικοποιήσεις που χρησιμοποιήθηκαν για τη διπλωματική εργασία με θέμα:

**«Προσδιορισμός των χαρακτηριστικών της ομιλίας της νόσου του Πάρκινσον με τη χρήση τεχνικών βαθιάς μάθησης»**

## 📁 Δομή του Repository

- `LMM_and_LM_together.ipynb`: Ανάλυση με Μικτά Γραμμικά Μοντέλα (LMM) και απλά γραμμικά μοντέλα (LM) για όλα τα tasks.
- `Dyskinesia.ipynb`: Ειδική ανάλυση και οπτικοποίηση για την κλινική κατηγορία Dyskinesia (στατιστικά test Wilcoxon, XGBoost feature importance, χαρακτηριστικά δύσκολων ασθενών).
- `plots_for_thesis.ipynb`: Συγκεντρωτικές οπτικοποιήσεις των επιδόσεων των μοντέλων (Radar plots, πίνακες μετρικών).
- `low_accuracy_top20_patients.ipynb`: Radial bar chart για τους 20 ασθενείς με επαναλαμβανόμενη χαμηλή ακρίβεια πρόβλεψης.
- `analysi_katanomis_fylou_klinikes_metavlites.ipynb`: Κατανομή φύλου ανά κλινική κατηγορία, με εξαγωγή πινάκων σε Excel και εικόνες.
- `Final Visualizations of Core Evaluation Metrics per Model.ipynb`: Τελικές ραβδογραφικές οπτικοποιήσεις των βασικών μετρικών απόδοσης (Accuracy, F1 κ.λπ.).
- `UPDRS_III_dif_per.ipynb`, `UPDRS_III_dif_class.ipynb`, `H_Y_binary.ipynb`, `Fluctuations_HERAKLION.ipynb`: Εστιασμένα αρχεία ανάλυσης για κάθε εξαρτημένη κλινική μεταβλητή με ML μοντέλα και μετρικές.
- `eGeMAPS_Category_Distribution.ipynb`: Γράφημα με την κατανομή των 90 χαρακτηριστικών eGeMAPS σε 5 βασικές κατηγορίες (φωνητικά, φασματικά κ.λπ.).
- `Top20_Feature_Occurrence.ipynb`: Οριζόντιο γράφημα με τα 20 πιο συχνά στατιστικώς σημαντικά χαρακτηριστικά από όλα τα LMM.
- `loso_flowchart.ipynb`: Γραφική απεικόνιση της διαδικασίας Leave-One-Subject-Out cross-validation (με Graphviz).
- `methodology_flow_diagram.ipynb`: Οπτική αναπαράσταση της συνολικής μεθοδολογικής ροής από preprocessing μέχρι αξιολόγηση.
- `LMM_Diagram.ipynb`: Γράφος που συνδέει τις επιμέρους φωνητικές εργασίες (tasks) με την εφαρμογή των LMM.
- `radar_model_comparison.ipynb`: Radar plots ανά task με απόδοση 6 μοντέλων (Accuracy, Precision, Recall, F1-score).

## 📦 Απαιτούμενες Βιβλιοθήκες

Για να εκτελέσεις σωστά τα notebooks, εγκατέστησε τις εξής βιβλιοθήκες:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost openpyxl graphviz
