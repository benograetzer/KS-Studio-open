# KS Studio AR Viewer

Dieses Repository ist eine reine oeffentliche Ablage fuer AR- und 3D-Modelle,
die direkt ueber GitHub Pages ausgeliefert werden. Es enthaelt nur statische
Dateien: eine Startseite, einen AR-Viewer, minimale Styles und den Ordner fuer
veroeffentlichte GLB/USDZ-Dateien.

Keine internen Daten, Preise, ERP-Informationen, Kundendaten oder privaten
Projektinformationen in dieses Repository hochladen.

## GitHub Pages aktivieren

1. Repository auf GitHub oeffnen.
2. `Settings` -> `Pages` oeffnen.
3. Bei `Build and deployment` die Option `Deploy from branch` waehlen.
4. Branch `main` und Ordner `/root` auswaehlen.
5. Speichern und warten, bis GitHub Pages die Seite veroeffentlicht hat.

## Dateistruktur

```text
KS-Studio_open/
├─ index.html
├─ ar-viewer.html
├─ css/
│  └─ ar-viewer.css
├─ exports/
│  └─ .gitkeep
└─ README.md
```

Der Ordner `exports/` ist fuer oeffentliche, bereinigte GLB- und USDZ-Dateien
vorgesehen. Die Datei `.gitkeep` sorgt dafuer, dass der leere Ordner im Repo
erhalten bleibt.

## Workflow

1. Im privaten KS-Studio den AR-Export erzeugen.
2. GLB- und optional USDZ-Datei nach `exports/` kopieren.
3. Commit + Push ausfuehren.
4. GitHub-Pages-URL oeffnen oder als QR-Code verwenden.

## Viewer-URLs

GLB-Datei laden:

```text
https://BENUTZERNAME.github.io/KS-Studio_open/ar-viewer.html?model=exports/test.glb
```

GLB-Datei mit USDZ fuer iPhone/iPad Quick Look laden:

```text
https://BENUTZERNAME.github.io/KS-Studio_open/ar-viewer.html?model=exports/test.glb&ios=exports/test.usdz
```

Optional kann ein Anzeigename gesetzt werden:

```text
https://BENUTZERNAME.github.io/KS-Studio_open/ar-viewer.html?model=exports/test.glb&ios=exports/test.usdz&title=H3000-Test
```

## Sicherheitsregel

Nur oeffentliche, bereinigte Modelle hochladen. Keine internen Daten, Preise,
ERP-Informationen, Kundendaten oder privaten Projektinformationen in GLB/USDZ,
Dateinamen, URLs, Commits oder die Dokumentation aufnehmen.
