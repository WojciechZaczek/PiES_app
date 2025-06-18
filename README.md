
# PiES_app – Przebieg i Ewidencja Służby

PiES_app to lokalna aplikacja desktopowa służąca do zarządzania grafikiem zmianowym pracowników.

## Główne funkcje:
- logowanie użytkowników (dwupoziomowe: user/admin)
- przeglądanie i edycja grafiku służb
- zarządzanie pracownikami i stanowiskami
- zmiana hasła przez użytkownika

## Technologie:
- Python + pywebview (frontend w HTML/CSS/JS)
- SQLite jako lokalna baza danych
- PyInstaller do tworzenia pliku `.exe`

## Wymagania:
- Gotowy `.exe` działa bez potrzeby instalowania Pythona
- Dla developerów: Python 3.10+, `pip install -r requirements.txt`

## Uruchomienie:
python main.py


Aplikacja działa lokalnie – dane nie wychodzą poza komputer.
