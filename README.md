# SensorSystem
Development of a sensor system and data processing framework for an Arduino Mega using a line scan sensor, light sensor, and encoder. Implementing Arduino C++ and Python code to interface sensors, process data, and ensure reliable communication with a Raspberry Pi 5.
## Anleitung
Für eine detaillierte Anleitung zur Nutzung und Einrichtung dieses Projekts, siehe [Anleitung](Anleitung.pdf).
## Anforderungen
Dieses Projekt erfordert die Installation der `StandardCplusplus`-Bibliothek. Diese wurde für die Anwendung angepasst und ist hier runterladbar.

### Installation der `StandardCplusplus`-Bibliothek
Lade die Bibliothek herunter und füge sie deinem Projekt hinzu. Du kannst die Bibliothek von folgendem Link herunterladen: [StandardCplusplus herunterladen](https://drive.google.com/drive/folders/1O6TFKQ0zEkDa_eVXzmit57WRAGl3N2YQ?usp=sharing)  - Die Bibliothek muss anschließend in das Arduino IDE eingebunden werden. Dazu den Ordner nach .\Arduino\libraries verschieben.


Alternativ kann die Bibliothek durch eine andere Bibliothek ersetzt werden, die den Datentyp `<set>` und `<list>` unterstützt.

## Setup:
Achte darauf, dass hier im Arduino IDE das richtige board und port ausgewählt wird. Der entsprechende Port muss auch in PyConnection - Gesamtsystem angegeben werden.

![SetUp](SetUp.PNG)
