# CV Offre Matching
Full-stack platform for matching candidate profiles with job offers using French NLP and machine-learning similarity.
## What it does
- Parses CV and job-offer text.
- Extracts skills and normalizes content.
- Computes TF-IDF similarity scores.
- Groups profiles or offers with K-Means and DBSCAN.
- Exposes a Django REST API and a React interface.
- Uses JWT authentication for protected endpoints.
## Stack
Django, Django REST Framework, React, JWT, Python, scikit-learn, TF-IDF, K-Means and DBSCAN.
## Architecture
- `backend/`: Django API, models and authentication.
- `frontend/`: React user interface.
- `ml/`: text preprocessing, vectorization and matching logic.
## Local development
```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```
Start the frontend separately from `frontend/` with the project package manager.
## Portfolio note
Collaborative academic project presented in Yahya Aferdi's portfolio. The repository history and contributions remain collective.
