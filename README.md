# Slipi-AntiADBlock (DE)

Inoffizielle Filterliste für **AdGuard Browser Extension**, die Anti-Adblock-Erkennungsfilter aus uBlock Origin für AdGuard-Syntax portiert.

AdGuard übernimmt bestimmte Filter nicht in ihre offiziellen Listen, weil betroffene Websites eine kostenpflichtige Alternative anbieten und AdGuard das intern als „Paywall mit Option" wertet. Diese Liste füllt diese Lücke.

## Unterstützte Websites

| Website | Beschreibung |
|---|---|
| bild.de | Anti-Adblock-Wall (adBlockWallEnabled), SmartAdServer-Erkennung |
| sport.bild.de | Kosmetische Ausnahme |
| spiele.bild.de | Verzögerte Adblock-Erkennung via setTimeout |
| gmx.net / gmx.de / gmx.at / gmx.ch | FairPlay Anti-Adblock-Wall |
| web.de | Anti-Adblock-Wall, Werbe-iFrame-Erkennung |
| golem.de | showAds-Check, adBlockerDetected-Timeout |
| focus.de | JSON-basierte Adblock-Erkennung |
| kino.de | JSON-basierte Adblock-Erkennung |
| spieletipps.de | JSON-basierte Adblock-Erkennung |
| gamesaktuell.de | JSON-basierte Adblock-Erkennung |
| videogameszone.de | JSON-basierte Adblock-Erkennung |

## Installation

**AdGuard Browser Extension:**

1. AdGuard öffnen → Einstellungen → Filter
2. Benutzerdefinierte Filter → Filter hinzufügen
3. Diese URL einfügen:

```
[[https://raw.githubusercontent.com/Slipi089/PBLKLT/refs/heads/main/Slipi-AntiADBlock](https://raw.githubusercontent.com/Slipi089/PBLKLT/main/Slipi-AntiADBlock)]
```

## Was diese Filter tun

Diese Filter neutralisieren ausschließlich die **Erkennung** des Adblockers. Sie umgehen keine Paywalls und schalten keine kostenpflichtigen Inhalte frei. Die eigentliche Werbeblockierung übernehmen weiterhin die Standardlisten von AdGuard (EasyList, AdGuard Base, AdGuard German Filter).

## Hinweise

- Getestet mit AdGuard Browser Extension ≥ 4.x (Chrome/Firefox)
- Nicht kompatibel mit AdGuard Home (DNS-Ebene) – DNS kann keine Scriptlets ausführen
- Die Filter werden bei Änderungen der Upstream-Quelle manuell aktualisiert

## Quelle & Lizenz

Die Filterregeln wurden aus **uBlockOrigin/uAssets** portiert und für AdGuard-Syntax angepasst.

- Upstream: https://github.com/uBlockOrigin/uAssets
- Upstream-Lizenz: GPL-3.0 (Copyright gorhill et al.)
- Diese Liste steht ebenfalls unter **GPL-3.0**

Relevante uAssets-Issues: #161 #6541 #6834 #7753 #8047 #8257 #8360 #8866 #9083 #9615 #15000 #15422 #22834

Relevante AdGuard-Issues (Won't fix): #57891 #199190 #210163
