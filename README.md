#### Installation des Projekts:
##### Klonen des Repositories:
###### Um ein Repository zu klonen muss man den Befehl (git clone https://github.com/benutzername/repository.git) im Git Bash ausführen. Weil dieser Befehl das REpository in ein lokales Verzeichnis kopiert.
##### Installation der notwendigen Pakete:
###### Nachdem man das Repository geklont hat. Muss man das Repository ins Projektverzeichnis navigieren mit dem Befehl (cd repository). Man muss die notwendige Pakete installieren. Das Paket muss die geeignete Programmiersprache des Projektes haben, sowie sollte es auf die gleichen Paketmanager basiert sein. Man installiert die Pakete, indem man die Abkürzung als erstes schreibt gefolgt von install BSP: Node.js = npm also das heisst das der Befehl "npm install" ist. ES gibt natürlich auch ausnahmen.
##### Docker-Konfiguration und -Installation
###### Als erstes muss man Docker Installiert haben (https://www.docker.com/products/docker-desktop). Nachdem Docker installiert ist sollte man die installation verizifieren mit dem Befehl "docker --version".
##### Starten der Applikation in einem Docker-Container
###### Falls das Projekt einen docker-compose.yml enthält, kann man es mir Docker Compose starten mit dem Befehl " docker-compose up". Sonst falls man nur eine Dockerfile haben, dann benutzt man die Befehle " docker bulit -t mein-app . " und " docker run -p 8080:8080 mein-app". Diese Befehle starten die Applikation in einem Docker-Container, der lokal auf deinem System läuft.

