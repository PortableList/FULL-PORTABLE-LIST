# FULL PORTABLE LIST
A curated list of free and truly portable software for use on portable storage devices.

<!-- Shields/Badges -->
<p align="center">
  <img src="Shields/FPL-Native_Portable-blue.svg" alt="Native Portable"/>
  <img src="Shields/FPL-Setting_Portable-brightgreen.svg" alt="Setting Portable"/>
  <img src="Shields/FPL-Isolated_Portable-orange.svg" alt="Isolated Portable"/>
  <img src="Shields/FPL-Fake_Portable-lightgrey.svg" alt="Fake Portable"/>
  <img src="Shields/FPL-No_Portable-red.svg" alt="No Portable"/>
  <img src="Shields/FPL-Runtime-purple.svg" alt="Runtime"/>
</p>

## FULL PORTABLE Criteria

- **Free Software:** Must comply with the FSF (Free Software Foundation) definition of free software.
- **Self-contained Data:** All configuration, data, and cache files must be stored in a designated local directory only. The software must not write to system directories or the registry on the host machine (exception: necessary OS-level caches, e.g., GPU driver caches, are not restricted).
- **Active Community:** The project should have a healthy community environment, with a minimum threshold of popularity (e.g., ≥1000 GitHub stars or equivalent recognition).
- **Security & Stability:** The software must be secure, stable, and have no known history of malicious behavior or developer misconduct.

---

## Definitions

- **Native Portable:** The software natively supports storing all data in a specific directory by default, with no special configuration required.
- **Setting Portable:** By default, the software writes to the host system, but it can be configured (via built-in settings) to store all data in a designated directory (e.g., VSCode detects a "data" folder, Windows Terminal detects a ".portable" file, etc.).
- **Isolated Portable:** The software only supports writing data to the host system by default, but with technical workarounds (such as setting environment variables or adding parameters), all data can be redirected to a specific directory, avoiding writes to the host environment.
- **Fake Portable:** (*Does **not** meet FULL PORTABLE criteria*) Data is initially written to the host system and then migrated to a designated directory to simulate "portability".
- **No Portable:** Does not meet any portable criteria described above.

---
