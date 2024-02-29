# Opis aplikacji
## 1. Wymagania
- python 3.10+
- django min 5.0
- paczka pillow
- silnik bazy sqllite3

## 2. Uruchomienie projektu
Wykonanie polecenia

Dla Windows
```sh
python -m venv venv
```

Dla Unix
```sh
python3 -m venv venv
```

Uruchomienie wirtualnej zmiennej środowiskowej (venv)

Dla Windows
w PowerShell
```sh
.\venv\Scripts\activate
```

lub w (GIT bash)
```sh
source venv/Scripts/activate
```

Instalacja Django
```sh
pip install django
```

Instalacja Pillow
```sh
pip install pillow
```

(opcjonalnie jeżeli jest pusta baza to)
```sh
python manage.py migrate
```

oraz utworzenie sa
```sh
python manage.py createsuperuser
```

W przypadku używania silnika sqllite3 z repo dane do logowania
```sh
login: admin
password: password
```

Uruchomienie serwera
```sh
python manage.py runserver
```