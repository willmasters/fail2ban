## Fail2Ban ##
Analyse der Logfiles und Sperrung bösartiger IP-Adressen


### Conf
Die lokale Systemdatei ```jail.local``` beinhaltet verfügbare Filter, sogenannte Jails.


### Filter
Reguläre Ausdrücke in ```filter.d``` sind auf Logfiles eines Nginx-Webservers optimiert.
Der Nginx-typische Aufbau der Log-Dateien wird also berücksichtigt.


### Referenz
Der Artikel im Cup Magazin beschäftigt sich mit der Installation und Einrichtung von [Fail2Ban](http://cup.wpcoder.de/fail2ban-ip-firewall/).


### Autor
[Sergej Müller](http://wpcoder.de)