---
{"dg-publish":true,"permalink":"/hausbau/loxone/loxone-air/"}
---

# Loxone Air

**Loxone Air** ist die von uns eigens für die Gebäudeautomatisierung entwickelte Funktechnologie.

Diese Funkschnittstelle wird von folgenden Loxone Geräten bereitgestellt:  
[Air Base Extension](https://www.loxone.com/dede/kb/air-base-extension/)  
[Miniserver Go](https://www.loxone.com/dede/kb/miniserver-go/)  
[Tree to Air Bridge](https://www.loxone.com/dede/kb/tree-to-air-bridge/)

Mittlerweile kann eine Vielzahl von kompatiblen Geräten über die Air Schnittstelle angesteuert, und damit in die Gebäudeautomatisierung eingebunden werden.  
Dabei sind batteriebetriebene Geräte zur einfachen Nachrüstung verfügbar, als auch Geräte mit fester Spannungsversorgung.

## Meshing und Vermittler
Loxone Air beinhaltet eine Meshing Technologie, um die Air Geräte untereinander zu vernetzen.

Dabei werden die Signale von weiter entfernten Geräten durch Air Geräte mit fester Spannungsversorgung (sogenannte Vermittler) bis zur Air Base Extension weitergeleitet.  
Dies erhöht insgesamt die Reichweite, wenn keine direkte Funkverbindung von der Air Base Extension zu weiter entfernten Geräten möglich ist.

Beachten Sie, dass die Kommunikation über Vermittler zu Zeitverzögerungen führt.  
Benötigt ein Air Gerät mehr als zwei Vermittler hintereinander, empfehlen wir eine zusätzliche Air Base Extension oder Tree to Air Bridge in der Nähe des signalarmen Gerätes.  
Die Anzahl der Hops (Anzahl der Vermittler zur Air Base Extension) wird im Gerätestatus angezeigt.

Die Loxone Air Kommunikation ist mittels IPSec verschlüsselt. Jede Loxone Installation hat ihren eigenen Verschlüsselungscode.

## Frequenzwechsel
Wenn mehrere Geräte auf der gleichen Frequenz arbeiten, kann die Verbindungsqualität darunter leiden.  
Ob der verwendete Kanal frei oder belegt ist, kann im Gerätestatus von Loxone Config geprüft werden.

## Onlinestatus von Air Geräten
Bei allen Air Geräten können in den Eigenschaften die Diagnose Eingänge aktiviert werden. Bei diesen finden Sie den Onlinestatus, der, wie der Name verrät, Sie über den aktuellen Status den Air Produktes informiert.