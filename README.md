# CISAM-EHR: Medical Text Classification with Explainability

This project presents the CISAM-EHR dataset and a complete pipeline for clinical text classification using traditional and transformer-based models. The approach includes data preprocessing, model training, and explainability with SHAP and LIME. The dataset consists of annotated Portuguese-language EHRs from high-risk pregnancy cases.

---

## 📁 Repository Structure

```bash
cisam-ehr/
├── docs/
│   └── Template -Request-for-Access-CISAM-EHR.docx  # Request form for dataset access
├── LICENSE                                           # License information
├── notebooks/                                       # Jupyter notebooks for each pipeline step
│   ├── 00_Download_and_format_dataset.ipynb
│   ├── 01_EDA-Sessions.ipynb
│   ├── 02_Data_cleaning_and_conversion_to_BIO_format.ipynb
│   ├── 03_Data_Preprocessing.ipynb
│   ├── 04-validate_and_explain_lime.ipynb
│   └── 05-validate_and_explain_shap.ipynb
└── README.md                                        # Project documentation
```

---

## 🧠 Pretrained Models and Weights

You can download the trained model weights from the following link:

🔗 [Google Drive – Model Weights](https://drive.google.com/drive/folders/1BOxeu_QDfzz3fN0JymYy-KAAkOGI04-p?usp=drive_link)

---

## 📘 Notebooks Overview

Each notebook corresponds to a stage in the pipeline:

- `00_Download_and_format_dataset.ipynb` – Download and initial formatting of the raw EHR records.
- `01_EDA-Sessions.ipynb` – Exploratory Data Analysis based on session types and frequency.
- `02_Data_cleaning_and_conversion_to_BIO_format.ipynb` – Cleaning and conversion of texts to BIO format for NER tasks.
- `03_Data_Preprocessing.ipynb` – Tokenization, normalization, and preprocessing for training.
- `04-validate_and_explain_lime.ipynb` – Model evaluation and local interpretability using LIME.
- `05-validate_and_explain_shap.ipynb` – Model evaluation and global interpretability using SHAP.

---

## 🔐 Accessing the CISAM-EHR Dataset

The dataset contains sensitive information from clinical records and is available for academic use only. To request access, please fill out the form below and contact the dataset administrators.

📄 [Request for Access – Template](./docs/Template%20-Request-for-Access-CISAM-EHR.docx)

> **Ethics Approval**  
> CAAE: 80278024.3.0000.5191  
> Approval Date: September 16, 2024 AM  
> All data are anonymized and comply with Brazilian ethical standards.

---

## 📜 License

This project is released under the MIT License. See the [LICENSE](./LICENSE) file for more details.

---

## 📫 Contact

For questions or collaboration proposals, please contact:

- Tiago Lima (tabl [at] ecomp.poli.br)