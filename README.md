# Ingrii

Ingrii is a Progressive Web Application (PWA) designed to help users better understand packaged food ingredients by scanning food labels and analyzing additives, preservatives, and E/INS codes.

The project aims to simplify ingredient interpretation and improve awareness about processed food consumption using OCR and machine learning techniques.

---

## Features

- OCR-based ingredient extraction from packaged food labels
- Detection and interpretation of E/INS codes
- Ingredient risk analysis using verified datasets
- Country-based restriction/banned ingredient lookup
- Progressive Web App (PWA) support
- Simple and user-friendly interface

---

## Tech Stack

### Frontend
- React

### Backend / Processing
- Python
- EasyOCR
- Scikit-learn
- Pandas

---

## How It Works

1. User uploads or scans a food label image
2. OCR extracts ingredient text from packaging
3. Ingredients and E/INS codes are parsed
4. Dataset lookup identifies:
   - additive information
   - potential risks
   - country restrictions
5. Results are displayed in a simplified readable format

---

## Machine Learning Experiments

The project experiments with Logistic Regression models for ingredient risk categorization and recommendation workflows.

---

## Installation

### Clone Repository

```bash
git clone https://github.com/go3-14/Ingrii_website 
cd ingrii
```

## Install dependencies
```
pip install -r requirements.txt
```

## Run app
```
npm install
npm start
```
