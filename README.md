# AutoGłośnik — oficjalne wydania

To repozytorium zawiera wyłącznie podpisane pliki APK, publiczny manifest
aktualizacji i dokumentację. Kod źródłowy nie jest publikowany.

AutoGłośnik automatycznie przełącza dźwięk rozmowy telefonicznej między
słuchawką a głośnikiem na podstawie czujnika zbliżeniowego. Obsługuje Telefon
Google/AOSP i Telefon Samsung oraz współpracuje z TalkBackiem.

## Najnowsze wydanie

- stabilna wersja: [1.0](https://github.com/proszczok2002/AutoGlosnik-Releases/releases/tag/v1.0)
- pakiet: `pl.bumbox.autospeaker`
- wymagany Android 12 lub nowszy
- języki: polski, angielski, niemiecki i rosyjski

## Instalacja

1. Pobierz APK wyłącznie z sekcji **Releases** tego repozytorium.
2. Otwórz pobrany plik i potwierdź instalację w systemie Android.
3. Przy pierwszej migracji ze starej, debugowo podpisanej wersji 1.3.1 trzeba
   ją odinstalować. Wydania od 1.0 mają wspólny bezpieczny podpis.
4. W aplikacji przyznaj uprawnienie Telefon i świadomie włącz ograniczoną
   usługę dostępności AutoGłośnika.

## Usługa dostępności i prywatność

Usługa dostępności jest używana wyłącznie podczas rozmowy, aby znaleźć i
aktywować istniejący przycisk głośnika w obsługiwanej aplikacji Telefon.
AutoGłośnik nie nagrywa rozmów, nie zapisuje treści ekranu, nie używa reklam
ani analityki. Pełne informacje: [PRIVACY.md](PRIVACY.md).

## Aktualizacje

Aplikacja pobiera publiczny `update.json` z tego repozytorium. Aktualizacja jest
pobierana tylko po potwierdzeniu użytkownika. Przed otwarciem instalatora
sprawdzane są: HTTPS, SHA-256, nazwa pakietu, rosnący numer wersji i podpis APK.
Android zawsze wyświetla osobne potwierdzenie instalacji.

Wbudowany updater jest przeznaczony dla dystrybucji bezpośredniej przez GitHub,
nie dla wydania w Google Play.

## Wsparcie

- Revolut: <https://revolut.me/r_rosiejka>
- PayPal: <https://paypal.me/proszczok>

Wsparcie jest dobrowolne i nie odblokowuje żadnych funkcji.

## Weryfikacja podpisu

SHA-256 certyfikatu podpisu wydań od 1.0:

`60A685333B8B79BD70998D692FD44F73D236B043429505C7555DDF7BECBF3326`

Sumy SHA-256 poszczególnych APK są podawane w opisie każdego wydania.
