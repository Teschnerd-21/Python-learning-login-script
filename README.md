# Python-learning-login-script
Login Script tweaks for a existing Linux interface 

Dieses Projekt beschäftigt sich mit dem Entwurf eines einfachen Login-Prozesses in einer bestehenden Linux-Oberfläche als Lernprozess. Ziel ist es Konzepte wie Logging, Cleanup und vor allem eine saubere Struktur zu verstehen und anzuwenden.

Das Projekt entstand aus dem eigenen Interesse heraus Python besser zu verstehen und erste Erfahrungen in der Nutzung von Python in einem reellen Anwendungs-Szenario zu bekommen.

Das Skript verbessert einen bestehenden (Main und Spare) Login und ergänzt die Basisstruktur durch verschiedene, folgende Features:

## Atomare Locking Funktion um parallele Starts des Logins zu verhindern. Bei versuchtem Start einer weiteren Instanz wird diese Beendet. 
## Einfaches Logging um Fehler besser nachvollziehen zu können 
## Cleanup um das Lock nach Beenden der Instanz zu entfernen und Login (wieder) zulässt 
## Exit Code Analyse um über verschiedene Aktionen entscheiden zu können wie *beenden, wiederholen, abbrechen* 


## Technologien: 
Python: Grundlagen; Linux Umfeld: Umgang mit Terminal 

## Was ich gelernt habe
- Strukturierung von Programmabläufen in Python
- Grundlagen der Benutzereingabe und Validierung
- Umgang mit Fehlern und unerwarteten Eingaben
- Integration einfacher Logik in ein größeres System
- Dokumentation und Nachvollziehbarkeit von Projekten
