#  Przypadek testowy 

* ID: 001 
* Tytuł: Rejestracja nowego użytkownika używając niepoprawnego adresu e-mail 
* Środowisko: Chrome wersja 62.0.3202.94, Ubuntu 16.04 LTS 
* Warunek wstępny: Uruchomiona przeglądarka. Użytkownik nie jest zalogowany. 


Kroki: 
* 1. Wejdź na stronę "https://wizzair.com/pl-pl#/" 
* 2. Kliknij "ZALOGUJ SIĘ" 
* 3. Kliknij "REJESTRACJA" 
* 4. Wpisz imię 
* 5. Wpisz nazwisko 
* 6. Wybierz płeć 
* 7. Wprowadź nr telefonu 
* 8. Wprowadź niepoprawny e-mail 
* 9. Wprowadź hasło 
* 10. Wybierz kraj 
* 11. Zaakceptuj politykę prywatności 

Oczekiwany rezultat: 
Rejestracja nie powodzi się Użytkownik dostaje informację, 
że wprowadzony e-mail jest niepoprawny 

# Uwagi Końcowe

Automatyzacja przypadku testowego (test funkcjonalny) powiodła się.
Test może być wrażliwy na zmianę struktury strony z powodu konieczności stosowania długich ścieżek w lokalizatorach XPATH i CSS Selector. 
 
