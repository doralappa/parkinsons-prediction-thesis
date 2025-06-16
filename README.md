# parkinsons-prediction-thesis

Αυτό το repository περιλαμβάνει τον πλήρη πηγαίο κώδικα, τα notebooks και τις οπτικοποιήσεις που χρησιμοποιήθηκαν για τη διπλωματική εργασία με θέμα:

**«Προσδιορισμός των χαρακτηριστικών της ομιλίας της νόσου του Πάρκινσον με τη χρήση τεχνικών βαθιάς μάθησης»**

## 📁 Δομή του Repository

- `LMM_and_LM_together.ipynb`: Ανάλυση με Μικτά Γραμμικά Μοντέλα (LMM) και απλά γραμμικά μοντέλα (LM) για όλα τα tasks.
- `Dyskinesia.ipynb`: Ειδική ανάλυση και οπτικοποίηση για την κλινική κατηγορία Dyskinesia.
- `plots_for_thesis.ipynb`: Συγκεντρωτικές οπτικοποιήσεις (π.χ. radar plots, σημαντικότητα χαρακτηριστικών).
- `low_accuracy_top20_patients.ipynb`: Radial bar chart για ασθενείς με επαναλαμβανόμενη χαμηλή ακρίβεια.
- `analysi_katanomis_fylou_klinikes_metavlites.ipynb`: Κατανομή φύλου ανά κλινική κατηγορία.
- `Final Visualizations of Core Evaluation Metrics per Model.ipynb`: Τελικές οπτικοποιήσεις των μοντέλων.
- `UPDRS_III_dif_per.ipynb`, `UPDRS_III_dif_class.ipynb`, `H_Y_binary.ipynb`, `Fluctuations_HERAKLION.ipynb`: Εστιασμένα αρχεία ανάλυσης ανά μεταβλητή.

## 📦 Απαιτούμενες Βιβλιοθήκες

Για να εκτελέσεις τα notebooks, εγκατέστησε τα παρακάτω:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost openpyxl graphviz
