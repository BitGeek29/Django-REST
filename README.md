# Django-REST

#Staic Location set krna

//# <project>/setting.py
STATIC_ROOT = os.path.join(BASE_DIR, "static")
MEDIA_ROOT = os.path.join(BASE_DIR, "media")

#run cmd static loc update
python3 manage.py collectstatic

##Test
pip install flake8
python3 -m flake8 . --max-line-length=127
