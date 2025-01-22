Pierwszy projekt Spring Boot.

Projekt jest prostą aplikacją webową stworzoną w Spring Boot.

Technologie:
Java 17
Spring Boot
Thymeleaf (do renderowania szablonów HTML)
Maven (lub Gradle, w zależności od konfiguracji)


Uruchamianie i dostęp do aplikacji.
Aplikacja będzie dostępna pod adresem:
http://localhost:8080/greeting - Powitanie z możliwością podania własnej nazwy. (np. http://localhost:8080/greeting?name=Vistula)



Pliki zawarte w projekcie:

HelloController.java
Klasa kontrolera, która obsługuje ścieżki HTTP / i /greeting.

FirstProjectJavaSpringApplication.java
Główna klasa uruchamiająca aplikację Spring Boot.

greeting.html
Szablon Thymeleaf renderujący stronę z powitaniem. Wykorzystuje parametr name do wyświetlenia spersonalizowanego powitania.

vistula.png
Obrazek wykorzystywany na stronie powitalnej w szablonie greeting.html.




Przykład wyjścia
Strona główna (/)
Zawiera komunikat:
"Hello Vistula, in my first Spring controller."

Strona powitania (/greeting?name=Vistula)
Wyświetli powitaną w formacie:
"Hello, Vistula!"

Oraz zawiera przykładowy tekst "Lorem ipsum" oraz obrazek.
