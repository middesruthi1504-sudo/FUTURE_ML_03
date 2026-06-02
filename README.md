# Resume Screening System

## Overview

This project implements a simple AI-powered Resume Screening System using Python and Machine Learning techniques. It compares multiple resumes against a given Job Description (JD) and ranks candidates based on similarity scores.

The system uses:

* TF-IDF Vectorization
* Cosine Similarity
* Pandas for data handling
* Matplotlib for visualization

## Features

* Load resume dataset from CSV/Excel file
* Accept a job description
* Convert text into numerical vectors using TF-IDF
* Calculate similarity between resumes and job description
* Rank resumes based on match score
* Visualize ranking results using a bar chart

## Project Structure

```text
FUTURE_ML_03/
│
├── data/
│   └── resume_dataset.csv.xlsx
│
├── images/
│   └── resume_ranking.png
│
├── notebooks/
│   └── resume_screening.ipynb
│
├── README.md
└── requirements.txt
```

## Installation

1. Clone the repository:

```bash
git clone <repository_url>
cd FUTURE_ML_03
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

## Dataset

The dataset should contain a column named:

```text
Resume
```

Each row should contain the textual content of a candidate's resume.

## Usage

1. Place the resume dataset in the project folder.
2. Update the job description inside the notebook.
3. Run the notebook:

```bash
jupyter notebook resume_screening.ipynb
```

4. The system will:

* Calculate similarity scores
* Rank resumes
* Generate a visualization chart

## Sample Output

```text
Resume Ranking:

Resume_ID    Match_Score
5            0.78
2            0.71
1            0.65
...
```

## Technologies Used

* Python
* Pandas
* Scikit-learn
* Matplotlib
* Jupyter Notebook

## Future Enhancements

* Resume parsing from PDF/DOCX
* Advanced NLP techniques
* Skill extraction
* Candidate recommendation system
* Web-based interface using Flask or Streamlit

## Author

MIDDE SRUTHI
