Create a fresh virtual environment and reinstall project dependencies. Set DJANGO_SECRET_KEY in your shell before running Django. .env.example documents the variable; Django does not load it automatically. The old database and cached bytecode were removed because they can contain personal data and secrets. Run python manage.py migrate to create an empty database. Generate a fresh Django secret key and invalidate old signed sessions.

Git history was rewritten and checked for the exposed values and removed sensitive files.
