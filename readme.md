# Zadanie rekrutacyjne na programistę Full Stack

Cześć, zapraszam do rozwiązania poniższego zadania rekrutacyjnego.
Podczas oceny, brane pod uwagę będą takie elementy jak:

* czysty kod, korzystanie z Javy >= 8
* optymalność rozwiązania
* organizacja branchy/commitów
* testy jednostkowe/integracyjne
* łatwość uruchomienia kodu i sprawdzenia działania przez inną osobę (sprawdzającego)
* responsywność i estetyka interfejsu użytkownika

Całość powinna być zrealizowana z użyciem następujących technologii:
* maven lub gradle
* Spring Boot/Spring Data/Postgresql (Docker) 
* Angular lub Ract.js

# Wymagania dotyczące aplikacji
* aplikacja sprawdza co godzinę wskazany katalog i jeśli znajdzie w nim pliki json (przykład questions.json) importuje zawarte tam dane do bazy
* aplikacja udostępnia api restowe umożliwiające:
    - rozpoczęcie nowego testu
    - przechodzenie po pytaniach (przód/tył)
    - zakończenie testu (na życzenie zdającego lub po upływie określonego czasu)
    - podsumowanie wyników testu oraz przegląd udzielonych odpowiedzi wraz z ich wyjaśnieniem
* aplikacja powinna posiadać interfejs webowy (Angular lub React.js) 
   
    