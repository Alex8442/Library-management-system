# Buecherei Verwaltungs System

Empfohlene Spezifikation:
-Windows 10 
-Internetzugang (ohne vpn/proxy)

Getestet auf einer frischen Virtuellen Maschine mit Windows 10
 

Einrichtung falls xampp nicht vorhanden:
0. Download unter: www.apachefriends.org/de 
1. Eine Aktuelle version von XAMPP (Die empfohlenen einstellungen benutzen)
	1.1 - Es müssen mysql,apache und phpMyAdmin installiert werden.
2.  Mittwald.sql & htdocs aus der  github repo herunterladen.
3.  Die Dateien innerhalb des Xampp/htdocs ordners löschen.  (In meinem fall unter: C:\xampp\htdoc) 
4.  Innerhalb xampp (xampp control panel) "mysql" und "apache" starten.
5.  In einem Webbrowser z.b Edge/Chrome localhost/phpmyadmin/aufrufen 
6.  Eine Neue Datenbank mit dem namen "mittwald" erstellen imgur.com/a/8KIRVW9
7.  Oben auf den reiter Importieren gehen und die datei "mittwald.sql" auswählen und unten auf ok drücken. 
8.  Die heruntergeladenen dateien des htdocs ordners in den XAMPP htdocs ordner verschieben. 
9.  localhost aufrufen 
10. fertig 

Einrichtung falls xampp vollständig eingerichtet ist: 
1. Innerhalb phpmyadmin eine neue datenbank mit dem namen "mittwald" erstellen.
2. mittwald.sql importieren
3. In htdocs einen neuen Ordner erstellen (falls dort noch andere Projekte sind)
4. Localhost öffnen / "Localhost/ordner" 


