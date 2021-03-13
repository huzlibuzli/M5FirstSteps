# M5FirstSteps	

Hallo Jonas, 
nachfolgend habe ich dir eine kurze Zusammenfassung aufbereitete, damit du einen einfacheren Start in die Programmierung des M5Fire hast. Ich gehe davon aus, dass du mit google und youtube ausreichend gut umgehen kannst, um kleinere Probleme selbst zu lösen. Solltest du an der einen oder anderen Stelle nicht weiterkommen, dann melde dich einfach bei mir.

## Allgemeine Informationen
- Dokumentation der M5Fire Hardware https://docs.m5stack.com/#/en/core/fire
- Übersicht zu allen Produkten (Module und Sensoren) https://docs.m5stack.com/#/en/
- Programmierportal UIFlow https://flow.m5stack.com/
- UIFlow Quick Start Guide https://docs.m5stack.com/#/en/quick_start/m5core/m5stack_core_get_started_MicroPython

## So gehts los
* Du benötigts einen Rechner und ein WLAN mit Internetzugang
* Der M5Fire ist nach dem UIFlow Quick Start Guide so weit voreingestellt, dass du ihn nur noch bei euch zu Hause fertig eirichten musst. 
  - (hab ich schon gemacht) Einrichten des WLAN-Zugangs nach der Anleitung https://docs.m5stack.com/#/en/quick_start/m5core/m5stack_core_get_started_MicroPython?id=ap-hotspot-configuration-wifi
  - (sollte auch schon gehen) Umstellen des Programmiermodus auf "Internet Mode" https://docs.m5stack.com/#/en/quick_start/m5core/m5stack_core_get_started_MicroPython?id=ap-hotspot-configuration-wifi
  - Öffne das UIFlow Programmierportal https://flow.m5stack.com/ und trage den API-Key ein
  - Dann kannst du starten :)

## Programmieren lernen

* Die grafische Programmieroberfläche ist ein wenig wie ein Programmierpuzzle. Die einzelnen Anknüpfpunkte der Programmbausteine sorgen für eine gewisse logische Abfolge innerhalb eines Programms. Du solltest dich dennoch mit einigen grundlegenden Ideen des Programmierens auseinandersetzen. 
- Variablen https://docs.m5stack.com/#/en/uiflow/data_structure?id=variables
- Operatoren https://docs.m5stack.com/#/en/uiflow/data_structure?id=operation
- Bedingungen, logische Operatoren und Schleifen https://docs.m5stack.com/#/en/uiflow/logic?id=if
* Mit diesem Rüstzeug kannst du dich dann an die Möglichkeiten der Hardware herantrauen und die Einzelne Aktoren und Sensoren in deinem Code verwenden
  - Leds einschalten https://docs.m5stack.com/#/en/uiflow/hardware?id=rgb
  - Taster mit einbeziehen https://docs.m5stack.com/#/en/uiflow/Units?id=button
  - Gyro Sensor auslesen https://docs.m5stack.com/#/en/uiflow/hardware?id=imu
  - die Bildschirmanzeige verändern usw. https://docs.m5stack.com/#/en/uiflow/ui_simulator?id=ui-elements
* Du wirst für die Programmierung recht schnell weitere Elemente des Programmierens benötigen, wenn du also die oben genannten verstanden hast geht es hiermit weiter
  - Maps und Arrays https://docs.m5stack.com/#/en/uiflow/data_structure?id=array
  - Laden und Speichern von Datenstrukturen (JSON) https://docs.m5stack.com/#/en/uiflow/data_structure?id=json
  - Funktionen https://docs.m5stack.com/#/en/uiflow/logic?id=functions

> So dann viel Spaß bei deinen ersten Gehversuchen.
