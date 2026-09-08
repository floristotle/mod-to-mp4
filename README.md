# Everio naar MP4 — uitgaven

Mac-app die opnames van de JVC Everio-camcorder (`.MOD` + `.MOI`) omzet naar MP4:
één chronologische video met hoofdstukken en datumstempel, plus losse clips.

**Download:** de nieuwste versie staat onder [Releases](../../releases/latest).
Pak de zip uit en sleep de app naar Programma's. De eerste keer: Systeeminstellingen →
Privacy en beveiliging → "Toch openen". Daarna meldt de app zelf als er een nieuwe versie is.

Vereist: Mac met Apple Silicon, macOS 14 of nieuwer.

Deze repository bevat alleen de uitgaven en de updatefeed (`appcast.xml`).
De app bevat een statisch gebouwde [ffmpeg](https://ffmpeg.org) (GPL v3, build van
[martin-riedl.de](https://ffmpeg.martin-riedl.de/)); die wordt als los programma aangeroepen.
