# Threat Model (STRIDE)
- Spoofing: fałszywe węzły, podszywanie, GNSS spoofing.
- Tampering: modyfikacja firmware, konfiguracji, danych.
- Repudiation: brak rozliczalności — audit trail, podpisy.
- Info Disclosure: wycieki danych, geolokalizacja sensorów.
- DoS: jamming RF, flood zdarzeń, ataki na łącza.
- EoP: eskalacja uprawnień, RCE w agentach.

## Hardening
- Secure boot, signed updates, TPM/SE.
- Segmentacja sieci, RBAC, rotacja kluczy.
- Redundancja, quorum, sanity‑checks.
