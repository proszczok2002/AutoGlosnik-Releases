# AutoGłośnik — instalacja i obsługa

AutoGłośnik przełącza dźwięk zwykłej rozmowy telefonicznej między słuchawką a
głośnikiem na podstawie czujnika zbliżeniowego. Wspiera Androida 12 lub nowszego
oraz Telefon Google/AOSP i Telefon Samsung. Nie nagrywa rozmów.

## Instalacja

1. Pobierz najnowszy `AutoGlosnik-v*.apk` z oficjalnej strony
   [Releases](https://github.com/proszczok2002/AutoGlosnik-Releases/releases).
2. Otwórz plik i potwierdź instalację w systemie Android.
3. Jeżeli masz starą wersję 1.3.1, odinstaluj ją jednorazowo — miała inny,
   testowy podpis. Wydania od 1.0 aktualizują się bez odinstalowania.
4. Uruchom AutoGłośnik, włącz główny przełącznik i przyznaj uprawnienie Telefon.
5. Otwórz ustawienia dostępności i świadomie włącz usługę AutoGłośnika. Gdy
   Android wymaga „ustawień z ograniczeniami”, zezwól na nie na ekranie
   informacji o aplikacji, a następnie wróć do ustawień dostępności.

## Test

Wykonaj zwykłe połączenie przez SIM. Odsuń telefon od ucha na około pół sekundy
— powinien włączyć się głośnik. Zbliż telefon do ucha, aby wrócić do słuchawki.
Bluetooth, słuchawki przewodowe/USB i aparaty słuchowe mają pierwszeństwo.

## Aktualizacje

Na zakładce **Wsparcie** wybierz **Sprawdź aktualizacje**. Po potwierdzeniu APK
jest pobierany z tego repozytorium i sprawdzany według HTTPS, SHA-256, pakietu,
wersji i certyfikatu. Od wersji 1.02 plik trafia bezpośrednio do systemowego
`PackageInstaller`, więc Uptodown App Installer nie powinien się uruchamiać.
Android nadal pokazuje własne potwierdzenie — aplikacja nie instaluje po cichu.

Przy pierwszej aktualizacji zezwól AutoGłośnikowi na **Instaluj nieznane
aplikacje**. Nie wyłączaj Play Protect na stałe. Jeżeli pokazuje ostrzeżenie,
sprawdź źródło, sumę wydania i certyfikat:

`60A685333B8B79BD70998D692FD44F73D236B043429505C7555DDF7BECBF3326`

## Problemy

- Brak przełączania: sprawdź główny przełącznik, uprawnienie Telefon, usługę
  dostępności oraz czy nie jest aktywny Bluetooth lub zestaw słuchawkowy.
- Konflikt pakietu/podpisu: odinstaluj wyłącznie starą 1.3.1 i zainstaluj
  aktualne wydanie.
- Usługa jest zatrzymywana: zdejmij ograniczenia baterii dla AutoGłośnika.
- Instalacja aktualizacji nie startuje: sprawdź zgodę „Instaluj nieznane
  aplikacje”, wróć do aplikacji i ponownie wybierz **Zainstaluj**.

Prywatność: [PRIVACY.md](PRIVACY.md). Wsparcie:
[SUPPORT.md](SUPPORT.md).
