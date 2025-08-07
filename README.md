# FULL PORTABLE LIST
Software list for portable storage devices.

## FULL PORTABLE Criteria

- **Free Software:** Must comply with the FSF (Free Software Foundation) definition of free software.
- **Self-contained Data:** All configuration, data, and cache files must be stored in a user-specified local directory only. The software must not write to system directories or the registry on the host machine (exception: necessary OS-level caches, e.g., GPU driver caches, are not restricted).
- **Active Community:** The project should have a healthy community environment, with a minimum threshold of popularity (e.g., ≥1000 GitHub stars or equivalent recognition).
- **Security & Stability:** The software must be secure, stable, and have no known history of malicious behavior or "developer sabotage".

---

## Definitions

- **Native Portable:** The software natively supports storing all data in a specific directory by default, with no special configuration required.
- **Setting Portable:** By default, the software writes to the host system, but it can be configured (via built-in settings) to store all data in a designated directory (e.g., VSCode detects a "data" folder, Windows Terminal detects a ".portable" file, etc.).
- **Isolated Portable:** The software only supports writing data to the host system by default, but with technical workarounds (such as setting environment variables or adding parameters), all data can be redirected to a specific directory, avoiding writes to the host environment.
- **Fake Portable:** (*Does **not** meet FULL PORTABLE criteria*) Data is initially written to the host system and then migrated to a designated directory to simulate "portability".
- **No Portable:** Not portable as described above.

---

