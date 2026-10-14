# Home Assistant

Home Assistant zur Steuerung des Fire TV Sticks per Alexa und ADB.

## Hintergrund

Wer kennt es nicht? Die Fernbedienung ist mal wieder verschwunden. Deshalb habe ich Home Assistant verwendet, um meinen Fire TV Stick per Sprachbefehl zu steuern.

## Einrichtung

Ich habe Home Assistant auf meinem Proxmox-Server in einer virtuellen Maschine installiert. Anschließend habe ich den Fire TV Stick über ADB mit Home Assistant verbunden und Alexa in Home Assistant integriert.

Danach habe ich verschiedene Routinen eingerichtet, um den Fire TV Stick per Sprache zu steuern.

## Sprachsteuerung

Grundlegende Funktionen wie „Alexa, Fernseher an“ haben bereits vorher funktioniert. Über Home Assistant habe ich weitere Steuerungsmöglichkeiten hinzugefügt.

Wenn ich jetzt beispielsweise „Alexa, hoch“ sage, wird über ADB ein Befehl von Home Assistant an den Fire TV Stick gesendet, der die Pfeil-nach-oben-Taste auslöst.
