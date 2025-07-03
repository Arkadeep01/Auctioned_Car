# Auctioned_Car 🚗

A machine learning model to predict whether cars sold at auction will be classified as *good* or *bad* deals.

---

## 🔍 Project Overview

This repository contains:

- **Jupyter Notebook**: `Auctioned_Cars.ipynb` — end-to-end training & evaluation.
- **Pre-trained model**: `Predicting_Good_Bad_Auction.pkl`
- **Sample files**: including `rf_Submissions.csv` for Kaggle-style output.
- **Data files**: in `DontGetKicked/` — raw & processed `.csv`/`.zip` datasets.

Our goal is to create an accurate classifier that identifies promising auctioned car deals by analyzing historical features and sales data.

---

## 🛠️ Installation & Setup

**Prerequisites**:
- Python 3.8+
- pip (package manager)
- [Git LFS](https://git-lfs.github.com/) (already configured)

**Steps**:
```bash
git clone https://github.com/Arkadeep01/Auctioned_Car.git
cd Auctioned_Car
python -m venv venv
source venv/bin/activate      # On Windows: `venv\Scripts\activate`
pip install -r requirements.txt
