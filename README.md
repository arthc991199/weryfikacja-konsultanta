Weryfikacja konsultanta z banku przez klienta podczas rozmowy telefonicznej przychodzącej do klienta.
 
 
Problem: klient nie ma pewności, że rozmawia z bankiem, nie ma jak zweryfikować rozmówcy.

Rozwiązanie: konsultant udowadnia, że jest pracownikiem banku, bo może podać klientowi jednorazowy kod, który wcześniej klient dostał do weryfikacji jakiejś operacji i go skutecznie użył.
 
Istniejące rozwiązania weryfikacji konsultanta dzwoniącego do klienta, przez klienta:
1.	Wysłanie SMSa przez konsultanta
2.	Wysłanie powiadomienia push przez aplikację mobilną
3.	kontakt klienta z infolinią banku lub placówką
4.	Hasło ustalane z bankiem, które konsultant może podać klientowi

1 i 2 i 4 nie są stosowane przez wszystkie banki.
3 nie spełniają wymogu weryfikacji gdyż złośliwy aktor może się podszyć pod pracownika banku. Znając imie i nazwisko oraz numer telefonu można uzyć tej tożsamości oraz oszukać odbiorcę poprzez Caller ID spoofing.

Warunki mozliwości zastosowania skutecznej procedury: 
1.	System generowania kodów potwierdzających operacje, przekazuje kody (np. po 3 dniach) do repozytorium kodów autoryzacji dla konsultantów telefonicznych
a.	opóźnienie w przekazaniu daje brak ryzyka nadużycia kodu
2.	klient nie może kasować SMSów
3.	System podaje konsultantowi kod łatwy do znalezienia przez klienta w skrzynce odbiorczej SMSów Np. Pierwszy konkretnego dnia, Nie dalszy niż 14 dni do tyłu, Nie nowszy niż poprzedni dzień
4.	Kod był skuteczny do potwierdzenia operacji bankowej - klient dokładnie ten kod musiał użyć wcześniej do potwierdzenia operacji bankowej
5.	Interesariusz tworzy kampanie informującą klientów o nowej procedurze
 
Procedura: 
1.	Konsultant aby się zweryfikować podaje klientowi kod 
2.	Kod na ekran roboczy podczas rozmowy z klientem, wskazał mu system klasy "CRM" (wspomagający zrealizowanie połączenia", otrzymując go ze zbioru skutecznie zastosowanych kodów przez klienta we wcześniejszych operacjach).
3. Podczas rozowy telefoniecznej konsultant może się zweryfikować mówiąc np. "ostatni kod z 19.03.2021, który zastosował Pan/Pani do operacji bankowej to 090-231"
4. Klient znajduje podczas rozmowy kod i weryfikuje jego poprawność
5. Klient wymagający, troskliwy o swoje dane ma możliwość upewnienia się co do tego kto dzwoni
6. Klient ignorujący tą informację jest tak samo narażony na wyciek informacji, jak gdyby podał złośliwemu aktorowi swoje dane weryfikacyjne bez tej procedury
7.	Dalsza część rozmowy zgodnie z aktualną procedurą
 
 
Słabe punkty:
1.	Lenistwo klienta i na ślepo akceptowanie podanego legitnego kodu
2.	Klient nie potrafi w trakcie rozmowy znaleźć KODu w zbiorze SMSów
3.	Oszust wmówi klientowi brak potrzeby takiej weryfikacji
4.	Klient nie będzie znał takiej możliwości weryfikacji i podczas fraudu nie ma szans to zadziałać

