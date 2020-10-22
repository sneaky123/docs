---
id: arma3_mods
title: Mods Installieren
sidebar_label: Mods Installieren
---

## Mit FTP verbinden

Bevor Resourcen installiert werden können, muss der [FTP-Zugang](gameserver_ftpaccess.md) eingerichtet werden:

![](https://screensaver01.zap-hosting.com/index.php/s/H5nAfBHye2Ptp67/preview)

Nachdem dieser eingerichtet wurde, kann sich nun verbunden werden und der Server Ordner geöffnet werden:

![](https://screensaver01.zap-hosting.com/index.php/s/zMEbrBbf9Fz4Rj7/preview)


## Vorbereitung

Erstmal Richtig jemanden Deddosen

![](https://screensaver01.zap-hosting.com/index.php/s/fipYamHgWYPR2RD/preview)

Nun starten wir den ArmA 3 Launcher, damit die Mods im Spielordner angelegt werden, nachdem die Mods im Launcher verarbeitet wurden, können wir den Launcher wieder schließen.

Nun öffnen wir unseren ArmA 3 Ordner, hier ist nun ein "!Workshop" Ordner, diesen öffnen wir, dort sind unsere Mods drin:

![](https://screensaver01.zap-hosting.com/index.php/s/gkaemdrs2L5cASJ/preview)

## Mods hochladen


Um mit WinSCP Mods zu installieren, können diese über drag&drop in den arma3 Ordner hochgeladen werden

![](https://screensaver01.zap-hosting.com/index.php/s/XoXwwPawZo5xz9Q/preview)

Nachdem diese hochgeladen wurde, müssen wir anschließend den Modordner öffnen und alle Daten unter `keys` in den gleichnamigen Ordner auf deinem Server verschieben:

![](https://screensaver01.zap-hosting.com/index.php/s/ExrDkmwATT5o2pb/preview)

## Mods Aktivieren

Nun öffnen wir die Einstellungen unseres Gameservers, unter der "Mods" Einstellung tragen wir unsere Mods wie folgt ein:

```
@mod1;@mod2;@mod3
```

In unserem Fall sieht das Ganze dann so aus:

![](https://screensaver01.zap-hosting.com/index.php/s/feJXSeZry98qCjz/preview)

Gehe sicher, dass bei mehreren Mods ein ; zwischen den Einträgen gesetzt wird:

![](https://screensaver01.zap-hosting.com/index.php/s/WDzg2DAKmHE98bJ/preview)


Fertig! Nach einem Serverneustart sind die Mods nun aktiv.
