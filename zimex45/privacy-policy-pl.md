# Polityka Prywatnosci - Zimex 45

**Data wejscia w zycie: 28 czerwca 2025**
**Ostatnia aktualizacja: 30 marca 2026**

## 1. Wprowadzenie

Niniejsza Polityka Prywatnosci opisuje, w jaki sposob aplikacja **Zimex 45** ("Aplikacja", "my", "nas", "nasz") przetwarza dane podczas korzystania z Aplikacji.

Zimex 45 jest nieoficjalnym, fanowskim symulatorem retro telefonu, inspirowanym klasycznymi doswiadczeniami mobilnymi, w tym era Siemens SL45i.

## 2. Administrator Danych

Administrator danych osobowych:
- Nazwa: PATRYKITI Patryk Ciechanski
- Email kontaktowy: zimex45@patrykiti.pl
- Adres: 05-532 Szymanow, Polska

## 3. Jakie Dane Przetwarzamy

### 3.1 Dane Przetwarzane przez Zintegrowane Uslugi Zewnetrzne

W zaleznosci od urzadzenia, regionu, wyborow dotyczacych zgody i zachowania Aplikacji, Aplikacja moze przetwarzac nastepujace kategorie danych za pomoca zintegrowanych SDK i uslug:

- **Dane o awariach i diagnostyczne** za pomoca Firebase Crashlytics, takie jak:
  - raporty o awariach
  - komunikaty o bledach i stack trace
  - techniczny kontekst dolaczany do logow, np. nazwy modulow, nazwy operacji, znaczniki czasu, nazwy ekranow i niewrazliwy stan runtime
  - metadane urzadzenia i aplikacji zbierane przez dostawce w ramach diagnostyki awarii

- **Dane reklamowe i dotyczace zgody** za pomoca Google Mobile Ads / AdMob oraz Google's User Messaging Platform (UMP), takie jak:
  - identyfikatory i dane zwiazane z zapytaniami reklamowymi obslugiwane przez Google
  - status zgody i sygnaly zgody wymagane do ustalenia, czy reklamy moga byc wyswietlane
  - techniczne metadane urzadzenia/sieci przetwarzane przez Google na potrzeby dostarczania reklam, zapobiegania naduzyciom i zgodnosci

### 3.2 Dane Przechowywane Lokalnie na Urzadzeniu

Aplikacja przechowuje czesc danych lokalnie na urzadzeniu, glownie w pamieci aplikacji i SharedPreferences, w tym:

- **Dane gry**:
  - najlepsze wyniki
  - postep w grze
  - stan gry potrzebny do dzialania funkcji gameplay

- **Preferencje i ustawienia aplikacji**:
  - ustawienia zwiazane z audio
  - preferencje UI i symulatora
  - wybrane stany wewnatrz aplikacji potrzebne do przywracania ekranow i zachowania

- **Dane organizera**:
  - przykladowe lub symulowane kontakty SIM utworzone w Aplikacji
  - stan kalendarza
  - appointments oraz inne wpisy organizera utworzone w Aplikacji

- **Dane dotyczace zgody**:
  - lokalnie zapisany status zgody reklamowej, np. `user_ad_consent`
  - consent strings lub powiazane wartosci zapisywane przez SDK Google, jezeli ma to zastosowanie

### 3.3 Danych, o Ktore Aplikacja Nie Prosi Bezposrednio

Aplikacja nie wymaga zakladania konta ani bezposredniego podawania danych profilowych, aby korzystac z jej podstawowych funkcji.

Aplikacja nie prosi bezposrednio o dostep do:
- prawdziwych kontaktow telefonicznych
- prawdziwej historii polaczen lub SMS
- precyzyjnej lokalizacji GPS
- danych z kamery lub mikrofonu
- zdjec, filmow lub bibliotek multimedialnych

## 4. Cele Przetwarzania Danych

Przetwarzamy dane w nastepujacych celach:

- **Funkcjonalnosc aplikacji**: uruchamianie symulatora, organizera i gier
- **Zapisywanie postepu i preferencji**: zachowanie lokalnego stanu gry i ustawien
- **Niezawodnosc i debugowanie**: diagnozowanie awarii, bledow i problemow technicznych
- **Reklamy i zarzadzanie zgoda**: wyswietlanie, ograniczanie lub blokowanie reklam zgodnie ze statusem zgody
- **Bezpieczenstwo i zgodnosc**: przeciwdzialanie naduzyciom i wykonywanie obowiazkow prawnych

## 5. Uslugi Zewnetrzne

### 5.1 Firebase Crashlytics

Korzystamy z **Firebase Crashlytics** do zbierania raportow o awariach i diagnostyki technicznej, aby identyfikowac oraz naprawiac bledy.

Informacje od dostawcy:
- [Firebase Privacy and Security](https://firebase.google.com/support/privacy)

### 5.2 Google Mobile Ads / AdMob

Korzystamy z **Google Mobile Ads / AdMob** do wyswietlania reklam w Aplikacji.

Informacje od dostawcy:
- [Google Privacy Policy](https://policies.google.com/privacy)

### 5.3 Google UMP (User Messaging Platform)

Korzystamy z narzedzi Google do zarzadzania zgoda, dostarczanych wraz z SDK reklamowym, aby zbierac i zapisywac wybory dotyczace zgody reklamowej tam, gdzie jest to wymagane.

Informacje od dostawcy:
- [Google Privacy Policy](https://policies.google.com/privacy)

### 5.4 Zasady Udostepniania

Nie sprzedajemy Twoich danych.

Jednak dane moga byc przetwarzane przez dostawcow uslug wykorzystywanych przez Aplikacje, w szczegolnosci uslugi Google wymienione powyzej, oraz moga zostac ujawnione, gdy wymaga tego prawo albo gdy jest to rozsadnie konieczne dla ochrony bezpieczenstwa, praw lub dzialania Aplikacji.

## 6. Bezpieczenstwo Danych

Podejmujemy rozsadne kroki w celu ograniczenia ryzyka prywatnosci, w tym:

- przechowywanie danych lokalnych w przestrzeni aplikacji
- sanitizowanie kontekstu logowania, aby ograniczyc przypadkowe dolaczenie danych wrazliwych
- ograniczenie Aplikacji do niewrazliwych uprawnien w glownym manifeście Androida
- korzystanie ze sprawdzonych dostawcow zewnetrznych dla crash reportingu, reklam i przeplywow zgody

Zadna metoda transmisji ani przechowywania nie jest w pelni wolna od ryzyka, dlatego nie mozemy zagwarantowac absolutnego bezpieczenstwa.

## 7. Okres Przechowywania Danych

- **Dane lokalne aplikacji** sa co do zasady przechowywane do czasu wyczyszczenia danych aplikacji, nadpisania ich w normalnym toku uzywania albo odinstalowania Aplikacji.
- **Dane o awariach, reklamach i zgodzie** przetwarzane przez dostawcow zewnetrznych moga byc przechowywane zgodnie z ich wlasnymi politykami i harmonogramami retencji.
- Nie gwarantujemy ani nie kontrolujemy dokladnych okresow retencji danych przechowywanych przez uslugi Google.

## 8. Twoje Prawa i Wybory

W zaleznosci od obowiazujacego prawa mozesz miec prawa takie jak dostep, sprostowanie, usuniecie, ograniczenie przetwarzania, sprzeciw lub zlozenie skargi do organu nadzorczego.

W praktyce:
- mozesz usunac lokalnie zapisane dane poprzez wyczyszczenie danych aplikacji lub odinstalowanie Aplikacji
- wybory dotyczace zgody reklamowej sa obslugiwane przez przeplyw zgody Google, gdy jest prezentowany w Aplikacji albo wymagany dla Twojego regionu
- mozesz skontaktowac sie z nami w sprawie pytan lub zadan dotyczacych ochrony danych

## 9. Dzieci

Ta Aplikacja nie jest przeznaczona dla dzieci ponizej 13 roku zycia.

- Aplikacja jest przeznaczona dla uzytkownikow 13+
- Nie prosimy swiadomie dzieci o podawanie danych profilowych, aby korzystac z Aplikacji
- Jezeli uwazasz, ze dziecko przekazalo nam bezposrednio dane osobowe, skontaktuj sie z nami pod adresem zimex45@patrykiti.pl

## 10. Zmiany w Polityce Prywatnosci

Mozemy od czasu do czasu aktualizowac niniejsza Polityke Prywatnosci.

W przypadku istotnych zmian mozemy zaktualizowac date na gorze dokumentu i, gdy bedzie to odpowiednie, odzwierciedlic zmiane w aktualizacji aplikacji lub powiazanej dokumentacji.

## 11. Kontakt

W sprawach dotyczacych niniejszej Polityki Prywatnosci lub przetwarzania danych skontaktuj sie z nami:

- Email: zimex45@patrykiti.pl

## 12. Podstawa Prawna

Gdy ma zastosowanie RODO, podstawy prawne przetwarzania moga obejmowac:

- **Art. 6 ust. 1 lit. f RODO** - prawnie uzasadniony interes w zakresie bezpieczenstwa aplikacji, diagnostyki i niezawodnego dzialania
- **Art. 6 ust. 1 lit. a RODO** - zgoda, gdy jest wymagana dla przetwarzania zwiazanego z reklamami lub zarzadzaniem zgoda

## 13. Informacje Dodatkowe

### 13.1 Uprawnienia Aplikacji

Glowny manifest Androida obecnie deklaruje:
- **INTERNET** - wymagane do komunikacji ze zintegrowanymi uslugami online, takimi jak crash reporting i reklamy

Aplikacja nie deklaruje wrazliwych runtime permissions dla kontaktow, lokalizacji, mikrofonu, kamery, SMS ani historii polaczen w glownym manifeście Androida.

### 13.2 Linki Zewnetrzne

Niniejszy dokument zawiera linki do polityk prywatnosci podmiotow trzecich. Podmioty te stosuja wlasne zasady i praktyki.

---

**Wersja**: 1.1
