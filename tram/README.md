Ajout des fichiers et dossiers

templates/
static/css

Ajout de lignes dans les fichiers de configurations

settings.py =>
    STATICFILES_DIRS = [
        os.path.join(BASE_DIR, "static"),
        '/var/www/static/',
    ]