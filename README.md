# MABAR DIAGNOSTICS

Prywatne repozytorium źródłowe projektu.

## Pliki
- `index.html` — aktualny program MABAR DIAGNOSTICS 1.0.2.
- `manifest.json` — metadane kanału aktualizacji.
- `CHANGELOG.md` — historia zmian.

## Publikowanie wydania
1. Wgraj `index.html` do repozytorium.
2. Utwórz GitHub Release z tagiem `v1.0.2`.
3. Dodaj plik jako asset o nazwie `MABAR_DIAGNOSTICS.html`.
4. Przy kolejnej wersji zwiększ `version` w `manifest.json`, zmień `downloadUrl` jeśli zmieni się nazwa assetu i zaktualizuj changelog.

## Uwaga o prywatności
Nie umieszczaj tutaj eksportów bazy klientów, VIN-ów ani danych pojazdów. Dane warsztatowe pozostają lokalnie na komputerze. Prywatny Release wymaga autoryzacji pobierania na urządzeniu klienckim; nie umieszczaj tokenu GitHub w pliku HTML.
