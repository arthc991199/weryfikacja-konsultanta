Weryfikacja konsultanta z banku przez klienta podczas rozmowy telefonicznej przychodzącej do klienta.
 
 
Problem: klient nie ma pewności, że rozmawia z bankiem, nie ma jak zweryfikować rozmówcy.

Rozwiązanie: konsultant udowadnia, że jest pracownikiem banku, bo może podać klientowi jednorazowy kod, który wcześniej klient dostał do weryfikacji jakiejś operacji i go skutecznie użył.
 
Istniejące rozwiązania weryfikacji konsultanta dzwoniącego do klienta, przez klienta:
1.	Wysłanie SMSa przez konsultanta
2.	Wysłanie powiadomienia push przez aplikację mobilną
3.	kontakt klienta z infolinią banku lub placówką
4.	Hasło ustalane z bankiem, które konsultant może podać klientowi

ad 1 i 2 i 4 nie są stosowane przez wszystkie banki.
ad 3 nie spełniają wymogu weryfikacji gdyż złośliwy aktor może się podszyć pod pracownika banku. Znając imie i nazwisko oraz numer telefonu można uzyć tej tożsamości oraz oszukać odbiorcę poprzez Caller ID spoofing.

ad 2 jest grupa klientów, którzy nie używają aplikacji bankowych, mają swoje powody z pogranicza bezpieczeństwa i prywatności, jednocześnie z tych samych powodów są bardziej zainteresowani weryfikacją kto do nich dzwoni.

Warunki możliwości zastosowania skutecznej procedury: 
1.	System generowania kodów potwierdzających operacje, przekazuje kody (np. po 3 dniach) do repozytorium kodów autoryzacji dla konsultantów telefonicznych
a.	opóźnienie w przekazaniu daje brak ryzyka nadużycia kodu
2.	klient nie może kasować SMSów
3.	System podaje konsultantowi kod łatwy do znalezienia przez klienta w skrzynce odbiorczej SMSów 
Np. Pierwszy konkretnego dnia, Nie dalszy niż 14 dni do tyłu, Nie nowszy niż poprzedni dzień
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
5.	Działaniem socjotechnicznym można podesłac klientowi wcześniej SMSy i liczyć na to, że klient się nie zorientuje, które są od przestępcy, a które realnie zadziałały na potrzey skutecznej autoryzacji transakcji bankowej

Alternatywne mozliwości:
1. klient może żadać od konsultanta kwoty przelewu z dnia x.y
2. Konsultant może podać kwotę, którą autoryzował posiadany przez klienta SMS
3. konsultant banku podaje token, ktory to klient może odczytac na swojej aplikacji typu Microsoft Authenticator lub alternatywie stosowanej przez klienta
4. klient pyta o 4 ostatnie cyfry numeru konta, dla którego była operacja na kwotę xx,yy zł, prosty formularz <numer operacji> <data> + blokada enumeracji na operatora
 



Microsoft Authenticator Alternatives
FusionAuth. FusionAuth. ...
1Password Business. 1Password. ...
Duo Security. Cisco. ...
Google Authenticator. Google. ...
RSA SecurID Suite. RSA Security. ...
Authy. Twilio. ...
Ping Identity. Ping Identity. ...
Symantec VIP. Broadcom


