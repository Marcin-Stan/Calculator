# Calculator
Ćwiczenie 1: Kalkulator
Celem ćwiczenia jest zapoznanie się z podstawowymi elementami interfejsu
użytkownika (layouty, przyciski, pola tekstowe) oraz sposobem tworzenia aktywności
i przełączania między nimi.
Założenia:
1) Aplikacja powinna zapewniać funkcjonalność kalkulatora, który w zależności od wyboru
użytkownika pozwoli na wykonanie podstawowych lub zaawansowanych obliczeń.
2) Ekran startowy aplikacji powinien umożliwiać:
• Wybór typu kalkulatora – prosty lub zaawansowany.
• Wyświetlenie informacji o aplikacji (np. nazwa aplikacji, nazwisko autora, krótki opis).
• Zamknięcie aplikacji.
3) Kalkulator w wersji prostej powinien umożliwiać wykonanie jedynie podstawowych
operacji matematycznych (zmiennoprzecinkowych) w tym obowiązkowo:
• Cztery podstawowe działania: dodawanie (+), odejmowanie(-), mnożenie(*), dzielenie(/).
• Zmiana znaku liczby (+/-) - znak zmienia się po, a nie przed wprowadzeniem liczby.
• Clear enter/clear (C/CE) - pierwsze naciśnięcie tego klawisza kasuje liczbę na
wskaźniku i umożliwia wprowadzenie innej, bez zakłócania toku obliczeń. Dwukrotne
naciśnięcie zeruje wszystkie rejestry kalkulatora (chyba, że istnieje zaimplementowana
funkcja pamięci).
• All clear (AC) - klawisz całkowitego kasowania rejestrów (i opcjonalnie pamięci)
kalkulatora.
• Wyświetlanie wyniku działania (=).
4) Kalkulator w wersji zaawansowanej, oprócz podstawowych, powinien dodatkowo
implementować bardziej zaawansowane operacje w tym obowiązkowo:
• Funkcje trygonometryczne: sinus (sin), cosinus (cos), tangens (tan).
• Funkcje logarytmiczne: logarytm naturalny (ln), logarytm (log).
• Obliczanie procentów (%).
• Pierwiastkowanie (sqrt).
• Potęgowanie (x^2), (x^y).
2
5) Dane wprowadzane przez użytkownika powinny być weryfikowane. W przypadku
błędnych danych użytkownik powinien zostać o tym poinformowany (można w tym celu
wykorzystać np. powiadomienie Toast).
6) Kalkulator musi pracować poprawnie w orientacji pionowej i poziomej. Operacja
wprowadzona w trybie pionowym, może zostać kontynuowana z trybie poziomym.
Screeny z aplikacji:

![image](https://user-images.githubusercontent.com/65038043/104471492-3583af80-55bb-11eb-8da4-75b4dc1f22f8.png)
![image](https://user-images.githubusercontent.com/65038043/104471640-64018a80-55bb-11eb-9fe5-982a15545898.png)
![image](https://user-images.githubusercontent.com/65038043/104471780-8abfc100-55bb-11eb-8a00-4b95fd9323ad.png)


