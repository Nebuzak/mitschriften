Hardware
========

Prozessorzyklus

0- Startbefehlsadresse in den Befehlszähler laden
1- Befehlszähler an RAM senden 
2- RAM holt befehl aus der Speicheradresse und sendet ihn an den Prozessor über eine
   Busleitung (Befehlsregister)
3- Befehl decodieren und Steuerbefehle für alle beteiligten Baugruppen bilden 
4- Ausführung
5- Befehlszähler erhöhen (+1)

(Steuerwerk)      
Befehlsdecoder
Befehlsregister
Befehlszähler

(Rechenwerk)
ALE - Arithmetisch Logische Einheit

Akkumulator
Speichert Ergebnisse 
