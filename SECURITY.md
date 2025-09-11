# Security Policy

## Zgłaszanie podatności
Nie publikuj wrażliwych danych. Zgłoszenia potencjalnych podatności opisuj wg STRIDE/CWE w sekcji Issues jako **Security report** z minimalnymi danymi reprodukcji.

## Zakres
Repo zawiera wyłącznie publiczne, jawne materiały. Nie przyjmujemy danych operacyjnych ani konfiguracji produkcyjnych.

## Dobre praktyki
- Szyfruj komunikację (TLS), podpisuj firmware, rotuj klucze.
- Segmentuj sieć sensorów, **zero‑trust** i least‑privilege.
- Redundancja i monitoring integralności (attestation, checksums).
