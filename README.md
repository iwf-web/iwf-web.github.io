## Willkommen

Hier findest du alle unsere bisher veröffentlichten und gepflegten Projekte, die wir unter einer MIT-Lizenz für die Community bereitstellen.

Wenn du Interesse hast, daran mitzuarbeiten, dann mach das doch auf [Github](https://www.github.com/iwf-web), oder bewirb dich bei uns als Entwickler. 
Unsere aktuell ausgeschriebenen Stellen findest du auf [hier](https://www.iwf.ch/web-solutions/jobs).

- Unsere Webseite: [https://web-solutions.io](https://web-solutions.io)
- Unser GitHub Account: [https://github.com/iwf-web](https://github.com/iwf-web)
- Unser Dockerhub Account: [https://hub.docker.com/u/iwfwebsolutions](https://hub.docker.com/u/iwfwebsolutions)


## Unsere Arbeitsmittel

Die Basis für unsere Arbeit bildet ein selbst entwickelter Stack basierend auf Docker und Vagrant.

Jeder bei uns im Team kann damit neue Projekte innerhalb von 15 Minuten bei sich lokal aufsetzen und stellt zudem sicher, dass sie bei ihm lokal genau 
so funktionieren wie auf dem produktiven Server.

Die zugehörigen Scripts, Dokumentationen und Docker-Images stellen wir euch für eure eigenen Projekte zur Verfügung.


### Das allumfassende Beispiel

Dokumentation ist wichtig, ein funktionierendes Beispiel noch wichtiger. 

Wir haben ein Beispielprojekt erstellt, das all unsere veröffentlichten Projekte integriert: Eine Vagrant-Box mit Docker-Inside, in der ein
Symfony 4-Projekt mit Nginx und MySQL läuft. Dazu eine umfassende Dokumentation (ausbaufähig! Hilf uns!) und Integration in PhpStorm.

[https://github.com/iwf-web/symfony-vagrant-docker-example](https://github.com/iwf-web/symfony-vagrant-docker-example)


### Die Docker Base Images

Es gibt tausende Images auf Dockerhub. Wer sein eigenes PHP-Image auf Basis des sehr schlanken Official Images bauen will, muss ein bisschen
Zeit investieren. Auch muss man sich Gedanken machen, und wie man Startscripts, Daemonen, Logfiles, Berechtigungen usw. umgeht. Wir haben das bereits
alles in langwieriger Arbeit entwickelt und optimiert. Hier findet ihr unsere optimierten und wöchentlich neu gebauten Basis-Images:


- [**PHP-FPM**](https://hub.docker.com/repository/docker/iwfwebsolutions/phpfpm): aktuell PHP 7.3 und PHP 7.1, mit vielen Modulen und hilfreichen Scripts
- [**Nginx**](https://hub.docker.com/repository/docker/iwfwebsolutions/nginx): aktuell v1.14, mit Konfiguration für Symfony3, Symfony4 und CraftCMS 
- [**MySQL**](https://hub.docker.com/repository/docker/iwfwebsolutions/mysql): aktuell v5.7, mit einer guten Default-Config


### Vagrant

Zusammengebaut und zusammengehalten wird all das mit unseren standardisierten Vagrant Scripts, die in jedem Projekt enthalten sind.
Sie helfen bei der Provisionierung der Vagrant Box bei jedem Entwickler und lösen einige Probleme, die entstehen, wenn man das selbst probiert, z.B.
wie man PhpUnit innerhalb der doppelten Virtualisierung mit PhpStorm nutzen kann.

[https://github.com/iwf-web/vagrant-scripts](https://github.com/iwf-web/vagrant-scripts)

Schau dir das *allumfassende Beispiel* an, wie du die Scripts in dein eigenes Projekt integrieren kannst.


## Unsere Packages

Wiederverwendbarer Code ist ein wichtiger Baustein der Open Source Community. Wir werden versuchen, unseren Teil dazu beizutragen.


### Symfony bundles

Unser Lieblings-Framework für die Backend-Entwicklung ist [Symfony](https://symfony.com), aktuell noch in Version 3, bald stellen wir um auf Version 4.

Wir haben natürlich bereits viele eigene Symfony Bundles entwickelt, die in unseren komplexen Applikationen eingesetzt werden. 
Einige davon werden wir nach und nach der Community bereitstellen.

Dazu ist aber noch etwas Arbeit nötig: Wir müssen Abhängigkeiten auflösen, Dokus erweitern, unsere Projekt anpassen, und das alles auf Github bringen.

Schau doch ab und zu mal hier vorbei!


### React packages

Unser Framework-of-choice für die Frontend-Entwicklung ist seit 2018 React. Alle unsere neuen Applikationen basieren darauf.

Auch hier haben wir ein paar Packages, die wir gerne veröffentlichen. 

Schau doch ab und zu mal hier vorbei!



## Bleib up-to-date

Auf unserem Twitter-Feed erfährst du am schnellsten, wenn wir etwas neues veröffentlichen oder aktualisieren. Nebenbei erfährst du noch, für welche
Projekte all dieses Zeug eingesetzt wird, und manchmal auch, wie wir in unseren Projekten arbeiten und was für ein tolles Team wir sind:


[https://twitter.com/IwfWeb](https://twitter.com/IwfWeb)


## Kontakt

Unsere Open Source Spezialisten erreichst du via E-Mail an: opensource@iwf.io

Wir versuchen, möglicht schnell zu antworten, aber das kann durchaus mal ein paar Tage dauern.

