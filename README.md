# Mistrz-ortografii

Projekt powstał na konkurs programistyczny (Daj Się Poznać 2017).
To jedna z pierwszych aplikacji z GUI, które napisałem po powrocie do programowania.
Użyłem tkinter, list słów w pliku txt i prostych mechanizmów losowania + liczenia punktów.
Został w formie, w jakiej był rozwijany.

Aplikacja edukacyjna do nauki polskiej ortografii – trudnych par liter (ch/h, rz/ż, u/ó).

Losuje słowo ze słownika, pokazuje je z brakującą częścią i czeka na wybór poprawnej opcji przez przyciski.  
Liczy skuteczność w procentach i liczbę wylosowanych słów.

## Co robi

- Wczytuje słowa z pliku proste.txt
- Losuje jedno słowo i ukrywa fragment (np. t_órz zamiast tchórz)
- Wyświetla 6 przycisków: ch, hh, rz, uo, uu, zz
- Po kliknięciu sprawdza poprawność, aktualizuje licznik i procent skuteczności
- Prosty interfejs w tkinter

## Wymagania

Python 3 + tkinter (standardowa biblioteka)

### Uruchomienie

```bash
python start1.15.py
```

----------------------------------------------------------
Mistrz Ortografii wersja 1.0
- Wybierz słowo -- losuje jedno słowo ze słownika
- O programie   -- przycisk przenoszący na stronę konkursu

v1.01
- poprawiono README
- dodano nowe słowa do słownika
- poprawiono czcionkę

v1.1
- dodano licznik wylosowanych słów
- dodano skuteczność wyrażoną w procentach
- słownik zawiera teraz 1169 słów, ale trzeba będzie utworzyć z niego drugi słownik na potrzeby rozwoju aplikacji

v1.15
- wstępna refakturyzacja zmniejszyła ilość linijek kodu z 259 do 195
----------------------------------------------------------
TODO:
- dodanie nowej funkcjonalności
- zrobić wersję exe
- ubranie kodu w klasy oop
