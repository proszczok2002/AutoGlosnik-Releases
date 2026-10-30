# Historia zmian

## 1.03 — migracja do głównego repozytorium

- `versionCode 108`.
- Wersja 1.02 pobiera to wydanie jeszcze z kanału zgodności.
- Po instalacji 1.03 kolejne aktualizacje i polityka prywatności korzystają z
  głównego repozytorium `proszczok2002/AutoGlosnik`.
- Zachowano bezpieczną weryfikację i systemowy `PackageInstaller`.
- SHA-256 APK:
  `6F532F3B6BFFA4D88C2C43581075E7063D7A5305CF3FE261A62AFD9D46E7B0E5`.

## 1.02 — poprawka instalatora

- `versionCode 107`.
- Bezpośrednia sesja systemowego `PackageInstaller` zamiast ogólnego
  `ACTION_VIEW`, który mógł uruchomić Uptodown App Installer.
- Ponowna kontrola SHA-256, pakietu, wersji i podpisu tuż przed instalacją.
- Dodana pełna instrukcja instalacji, konfiguracji, działania i aktualizacji.
- SHA-256 APK:
  `FE84A901AED68C34A7330B2DF9C5645F8D44547BAD4D66EF0946B4268344D5F4`.

## 1.01 — aktualizacja testowa

- `versionCode 106`.
- Test pełnego przepływu aktualizatora z wersji 1.0.
- Ten sam certyfikat podpisu co w wersji 1.0.
- SHA-256 APK:
  `022D93EEA103EB9A93FEE297B056A6E460C2BAE6A28E847AF367BB1F2CACD134`.

## 1.0 — pierwsze publiczne wydanie

- Telefon Google/AOSP i Telefon Samsung.
- Automatyczne przełączanie słuchawka/głośnik.
- Cztery języki i zakładka Wsparcie.
- Bezpieczny updater GitHub.
- SHA-256 APK:
  `6E2A67DE9127667E98D1E3C48E1B63BF08F8F1291910A9C6B0F7BDF9DE9D5D8E`.
