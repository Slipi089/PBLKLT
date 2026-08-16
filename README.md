# Slipi-AntiADBlock (DE)

Inoffizielle Filterliste, die Anti-Adblock-Erkennungsfilter aus uBlock Origin
für **AdGuard** und **uBlock Origin** bereitstellt. Verfügbar in zwei Syntax-Varianten.

## Umfang

Deckt diverse deutschsprachige Nachrichten-, Mail- und Streaming-Seiten ab.
Die genaue Liste der Domains steht in der jeweiligen Filterdatei.

## Installation

Im jeweiligen Blocker unter „Benutzerdefinierte Filter" die passende URL abonnieren –
**nicht** beide Dateien gleichzeitig, sondern die zu deinem Blocker.

**AdGuard Browser Extension** (Einstellungen → Filter → Benutzerdefinierte Filter → Filter hinzufügen):

```
https://raw.githubusercontent.com/Slipi089/PBLKLT/main/slipi-antiadblock-adguard.txt
```

**uBlock Origin** (Dashboard → Filterlisten → Importieren):

```
https://raw.githubusercontent.com/Slipi089/PBLKLT/main/slipi-antiadblock-ubo.txt
```

## Hinweise

- Getestet mit AdGuard Browser Extension ≥ 4.x und uBlock Origin (Chrome/Firefox).
- Nicht kompatibel mit AdGuard Home (DNS-Ebene) – DNS kann keine Scriptlets ausführen.
- Unter Chromium/Manifest V3 kann die Scriptlet-Injektion später greifen als unter
  Firefox; einzelne Erkennungen (z. B. rain-alarm.com) sind dort ggf. weniger zuverlässig.
- Die Filter werden bei Änderungen der Upstream-Quelle manuell aktualisiert.

## Verwandte Projekte

- Regel-Quelle: https://github.com/uBlockOrigin/uAssets
- AdGuard-Filter: https://github.com/AdguardTeam/AdguardFilters

## Quelle & Lizenz

Die Filterregeln wurden aus **uBlockOrigin/uAssets** portiert und für die jeweilige
Syntax angepasst.

- Upstream: https://github.com/uBlockOrigin/uAssets
- Upstream-Lizenz: GPL-3.0 (Copyright gorhill et al.)
- Diese Liste steht ebenfalls unter **GPL-3.0**

