# Utilisez une image de base contenant Python 2.7
FROM python:2.7

# Définissez le répertoire de travail dans le conteneur
WORKDIR /app

# Copiez le fichier apy.py dans le conteneur
COPY api.py /app/api.py

# Installez les dépendances python-requests et python-flask
RUN  pip install requests flask

# Exécutez le fichier apy.py
CMD ["python", "api.py"]
