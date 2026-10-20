<p align="center">
  <img src="assets/autoglosnik-icon.svg" width="128" height="128" alt="Logo AutoGłośnika — biały głośnik na niebieskim tle">
</p>

<h1 align="center">AutoGłośnik</h1>

<p align="center">
  Automatyczne przełączanie rozmowy między słuchawką i głośnikiem<br>
  na podstawie czujnika zbliżeniowego.
</p>

<p align="center">
  <a href="https://github.com/proszczok2002/AutoGlosnik-Releases/releases/latest"><img alt="Najnowsze wydanie" src="https://img.shields.io/github/v/release/proszczok2002/AutoGlosnik-Releases?display_name=tag&label=wersja&color=315CFF"></a>
  <img alt="Android 12 lub nowszy" src="https://img.shields.io/badge/Android-12%2B-3DDC84?logo=android&logoColor=white">
  <img alt="Cztery języki" src="https://img.shields.io/badge/języki-PL%20%7C%20EN%20%7C%20DE%20%7C%20RU-315CFF">
  <img alt="Kod źródłowy prywatny" src="https://img.shields.io/badge/źródła-prywatne-555555">
</p>

<p align="center">
  <a href="https://github.com/proszczok2002/AutoGlosnik-Releases/releases/latest"><strong>⬇ Pobierz najnowszy APK</strong></a>
  ·
  <a href="INSTRUKCJA.md"><strong>Instrukcja</strong></a>
  ·
  <a href="https://github.com/proszczok2002/AutoGlosnik-Releases/issues/new?template=bug_report.md"><strong>Zgłoś problem</strong></a>
</p>

---

## Co robi AutoGłośnik?

Podczas zwykłej rozmowy telefonicznej aplikacja reaguje na położenie telefonu:

| Położenie telefonu | Trasa dźwięku |
| --- | --- |
| Telefon przy uchu | słuchawka rozmów |
| Telefon odsunięty | głośnik |
| Aktywny Bluetooth, USB, przewód lub aparat słuchowy | urządzenie zewnętrzne ma pierwszeństwo |

AutoGłośnik współpracuje z Telefonem Google/AOSP i Telefonem Samsung. Nie
zastępuje aplikacji Telefon, nie wykonuje połączeń i nie nagrywa rozmów.

## Najnowsza wersja

> [!TIP]
> **AutoGłośnik 1.02** jest aktualnym stabilnym wydaniem. Poprawia instalację
> aktualizacji: zweryfikowany APK trafia bezpośrednio do systemowego instalatora
> Androida, bez przekazywania go do Uptodown App Installer.

| Informacja | Wartość |
| --- | --- |
| Wersja | [`1.02`](https://github.com/proszczok2002/AutoGlosnik-Releases/releases/tag/v1.02) (`versionCode 107`) |
| Pakiet | `pl.bumbox.autospeaker` |
| System | Android 12 lub nowszy |
| Dialer | Telefon Google/AOSP lub Telefon Samsung |
| Języki | polski, angielski, niemiecki, rosyjski |

## Instalacja w skrócie

1. Pobierz `AutoGlosnik-v1.02.apk` z
   [najnowszego wydania](https://github.com/proszczok2002/AutoGlosnik-Releases/releases/latest).
2. Otwórz plik i potwierdź instalację w systemie Android.
3. Uruchom AutoGłośnik, przyznaj uprawnienie Telefon i świadomie włącz usługę
   dostępności AutoGłośnika.
4. Wykonaj testowe połączenie SIM: odsuń telefon, a następnie zbliż go do ucha.

> [!IMPORTANT]
> Jeżeli masz starą wersję 1.3.1, odinstaluj ją przed pierwszą instalacją
> aktualnego wydania. Wersja 1.3.1 miała inny, testowy podpis. Wydania od 1.0
> korzystają już z jednego certyfikatu i aktualizują się bez odinstalowania.

Dokładne kroki, ustawienia baterii, test, aktualizacje, Play Protect i
rozwiązywanie problemów opisuje **[pełna instrukcja](INSTRUKCJA.md)**.

## Aktualizacje z GitHuba

Updater korzysta wyłącznie z publicznego `update.json` i plików APK z GitHub
Releases. Przed instalacją sprawdza:

- połączenie HTTPS i dozwolony adres oficjalnego wydania;
- sumę SHA-256 pobranego pliku;
- pakiet `pl.bumbox.autospeaker` i rosnący `versionCode`;
- zgodność certyfikatu z zainstalowaną aplikacją.

Od wersji 1.02 APK jest przekazywany bezpośrednio do systemowego
`PackageInstaller`. Użytkownik nadal zatwierdza pobranie i osobno instalację —
aplikacja nie wykonuje cichych aktualizacji.

## Dostępność i prywatność

AutoGłośnik używa ograniczonej usługi dostępności wyłącznie podczas rozmowy,
aby znaleźć i aktywować istniejący przycisk głośnika w obsługiwanej aplikacji
Telefon. Użytkownik sam włącza tę usługę i może ją w każdej chwili wyłączyć.

Aplikacja:

- nie nagrywa rozmów i nie odczytuje numerów telefonu;
- nie zapisuje ani nie przesyła treści ekranu;
- nie zawiera reklam ani analityki;
- łączy się z internetem tylko w sprawie aktualizacji i po otwarciu przez
  użytkownika zewnętrznego łącza.

Pełne ujawnienie: **[polityka prywatności](PRIVACY.md)**.

## Bezpieczeństwo wydania

Pobieraj APK wyłącznie z zakładki
[`Releases`](https://github.com/proszczok2002/AutoGlosnik-Releases/releases).
SHA-256 certyfikatu wydań od wersji 1.0:

```text
60A685333B8B79BD70998D692FD44F73D236B043429505C7555DDF7BECBF3326
```

SHA-256 APK 1.02:

```text
FE84A901AED68C34A7330B2DF9C5645F8D44547BAD4D66EF0946B4268344D5F4
```

Więcej: **[zasady bezpieczeństwa](SECURITY.md)**.

## Dokumentacja

| Dokument | Zawartość |
| --- | --- |
| [INSTRUKCJA.md](INSTRUKCJA.md) | instalacja, konfiguracja, test, updater i problemy |
| [PRIVACY.md](PRIVACY.md) | dane, sieć, dostępność i uprawnienia |
| [CHANGELOG.md](CHANGELOG.md) | historia wydań i sumy APK |
| [SECURITY.md](SECURITY.md) | weryfikacja podpisu i zgłaszanie podatności |
| [SUPPORT.md](SUPPORT.md) | wsparcie rozwoju i pomoc techniczna |
| [LICENSE.md](LICENSE.md) | warunki udostępnienia binarnych wydań |

## Wsparcie rozwoju

Jeżeli AutoGłośnik jest dla Ciebie przydatny, możesz dobrowolnie wesprzeć jego
dalszy rozwój:

- **Revolut:** <https://revolut.me/r_rosiejka>
- **PayPal:** <https://paypal.me/proszczok>

Wsparcie nie jest zakupem i nie odblokowuje żadnych funkcji.

---

<p align="center">
  Repozytorium zawiera wyłącznie oficjalne wydania, manifest aktualizacji i
  dokumentację. Kod źródłowy pozostaje prywatny.
</p>
