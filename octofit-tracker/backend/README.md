OctoFit Tracker — Backend setup

This folder contains the backend requirements and basic setup notes for the OctoFit Tracker app.

Create the Python virtual environment (recommended):

```bash
# from the repository root (do not change directories when running automated agent commands)
python3 -m venv octofit-tracker/backend/venv

# activate the venv
source octofit-tracker/backend/venv/bin/activate

# install the pinned dependencies
pip install -r octofit-tracker/backend/requirements.txt
```

Notes
- The project is intended to use Django + Django REST Framework.
- The instructions and pinned dependencies are taken from the project guidelines.
- Use Django's ORM for database interactions; for local development you can use the default SQLite settings until a production DB is configured.

Next steps (suggested)
- Create a Django project: `django-admin startproject octofit_tracker octofit-tracker/backend` (or use your preferred layout)
- Add REST API endpoints, authentication, and models for users and activities.
- Add tests and CI (optional).
