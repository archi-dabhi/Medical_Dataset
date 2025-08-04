# Task 1: Data Cleaning – Medical Appointment Dataset

## ✅ Objective
Clean and preprocess a raw dataset with common data issues like missing values, duplicates, and inconsistent formatting.

## 🛠 Steps Performed

1. **Loaded** `medical_dataset.csv` using pandas.
2. **Removed** rows with missing values and duplicates.
3. **Standardized** text fields (`gender`, `no_show`).
4. **Converted** date columns (`scheduledday`, `appointmentday`) to datetime.
5. **Renamed** columns to lowercase with underscores.
6. **Fixed** data types (`age` as int, IDs as string).
7. **Saved** the cleaned file as `cleaned_medical_dataset.csv`.

## 📊 Tools Used
- Python (Pandas)
- Jupyter Notebook
- GitHub for submission

## 🔗 Dataset
Dataset used: [Medical Appointment No Shows](https://www.kaggle.com/datasets/joniarroba/noshowappointments)
