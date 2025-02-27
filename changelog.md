
# Changelog

## Version 3.0.0beta-2.1

- *fix* Thiefs cant steal from city storehouse
- *fix* Tooltip Ritterbutton während respawn
- *fix* Sprachmeldung beim IO, wenn es auch Rewards gibt, die zu einem fahren.
- *fix* Unlock title for Player war noch fehlerhaft und wurde behoben.

  *Entschuldigung für fehlende Changelogs zwischen den Versionen*


## Version 3.0.0.beta-1.2

- *fix* Fehler bei dem manche Konsolenbefehle nie aufgerufen werden konnten wegen eines falschen Vergleichs
- *fix* Falscher Index in Behavior Konstruktor
- *fix* Violette Farbe wird nun dem Nutzerinput im Questjournal korrekt zugewiesen
- *fix* Falscher Index in allen :ProcessChatInput Methoden
- *fix* Falscher Zeichenbereich in den Regular-Expressions
- *added* Quests nutzen jetzt das gleiche Format für string tables
- *fix* Fehler beim Ersetzen-Parameter der Interaktiven Objekte
- *added* Hinweise zu Probleme bei der Nutzung mancher Funktionen wurden erweitert

## Version 3.0.0.beta-1.1.12

- *added* API.UnlockTitleForPlayer aus QSB2.
- *added* History Edition Editor Sprachenfix.
- *added* Konsolenbefehle won, failed, stopped, active, waiting und find

## Version 3.0.0.beta-1.1.11

- *fix* Typewriter gefixt.

## Version 3.0.0.beta-1.1.10

- *added* Es wurde der Goal_Decide wiedereingebaut

## Version 3.0.0.beta-1.1.9

- *fix* Befehle stop start win fail und restart sollten nun über die Konsole wieder gehen
- *fix* Reihenfolge alter Konsolenbefehle

## Version 3.0.0.beta-1.1.8

- *fix* Fehler in API.Message behoben
- *added* In der Konsole kann nun mit den Pfeiltasten durch bisherige Befehle gewechselt werden

## Version 3.0.0.beta-1.1.7
- *fix* Fehler beim Abspielen des Theaters
- *added* Questdialoge wurden aus der 2.x übernommen

## Version 3.0.0.beta-1.1.6
- *fix* Fixt einen Fehler bei der Marktplatzlieferung

## Version 3.0.0.beta-1.1.5
- *fix* Mehrere Rechtschreibfehler in den Behaviorn wurden korrigiert.

## Version 3.0.0.beta-1.1.4

- *fix* Fehler bei dem die Übersetzungen zu manchen Behaviors nicht richtig geladen wurden

## Version 3.0.0.beta-1.1.3

- *fix* Fehler bei der Variablenbennenung des Behaviors Reward_InitTradePost
- *fix* Fehler beim behandeln fehlerhafter Behaviors

## Version 3.0.0.beta-1.1.1

- *fix* Reward_InitTradePost geported.

## Version 3.0.0.beta-1.9

- *fix* Mehrere Fixes von 2.15.0.3 geported.

## Version 3.0.0.beta-1.8

- *fix* Multiselektionsfix von 2.14.9 hinzugefügt

## Version 3.0.0.beta-1.7

- *fix* Im Produktionsmenü werden nun die Kathedrale/Kirche, alle Arten von Burgen und alle Arten von Außenposten korrekt erfasst und sind durchschaltbar

- *added* toggle für DSE-Fehlerausgabe

## Version 3.0.0.beta-1.6

- *fix* error bei den Banditenfeuern (Ubisoft Fehler)

## Version 3.0.0.beta-1.5

- *fix* error in Aufgabencounter

## Version 3.0.0.beta-1.4

- *added* Addon HuntableLifestock hinzugefügt

## Version 3.0.0.beta-1.3

- *fix* error in TypeWriter, Briefing und Cutscenes
- *fix* error on RandomChest

- *added* Alias-Funktion SetCameraToEntity hinzugefügt
- *added* Alias-Funktion CreateObject hinzugefügt
- *added* Kompatibilität zu API.TravelingSalesmanCreate
- *added* Kompatibilität zu Cutscene System

## Version 3.0.0.beta-1.2

- *fix* Rechtschreibfehler
- *fix* fehlenden Rückgabeparameter in API.CanKnightBePromoted
- *fix* API.GetPosition gab y für z zurück
- *fix* Fehler in Baukosten, die einen DSE beim hovern von Baubuttons ohne veränderte Kosten verursacht hat
- *fix* Darstellungsfehler in der Markdown-Doku angepasst
- *fix* Reward_ToggleCommunityFeatures wurde nicht gefunden
- *fix* Reward_EditBuildingUpgradeCosts wurde nicht gefunden
- *fix* Reward_EditBuildingConstructionCosts wurde nicht gefunden
- *fix* Fehlende Data-Tabelle bei Gebäudebuttons hinzugefügt
- *fix* Fehlende Implementierung von API.SetSpeedLimit(_Limit) hinzugefügt


- *added* Addon für Questketten hinzugefügt
- *added* Kompatibilität zu Funktionen zum verstecken von Interfaceelementen
- *added* Kompatibilität zu Funktionen zur Nutztierzucht
- *added* Kompatibilität zu HE Quicksave Unterdrückung
- *added* Kompatibilität zu SetResourceAmount
- *added* Kompatibilität zu Funktionen des Interfaces
- *added* Kompatibilität zu API.GetControllingPlayer
- *added* API.UseSingleStop(_Flag) zu BuildingUI Modul hinzugefügt
- *added* API.UseSingleReserve(_Flag) zu BuildingUI Modul hinzugefügt
- *added* API.UseDowngrade(_Flag) zu BuildingUI Modul hinzugefügt

## Version 3.0.0.beta-1.1

- *fix* QSB wird nun korrekt gebaut, zuvor war die Reihenfolge der Dateien nicht vorgegeben, weswegen es zu Fehlern kommen konnte

## Version 3.0.0.beta-1

- *added* Erste Beta-Version der QSB3
