### Vorbereitung techI3 für Anwendungen mit Matlab Simulink

#### Hochfahren des Systems
- Kippschalter im Kofferraum aktivieren
- "Nebukadnezar" (Rechenmaschine) über den scharzen Power Button einschalten
- Fahrzeug aktivieren (CAN-Bus muss )
- Netzwerkleitung mit Matlab-Rechner verbinden
#### ROS Umgebung aktivieren
- Doppelklick auf das Icon "start_matlab_sandbox"

<img src="1.png" alt="Alt-Text" title="" />

#### Position Paket initialisieren
- Fahrzeug in Bewegung setzen

#### Initialisierung überprüfen

- Graphische Übersicht der `tf-frames` öffnen. Hierfür Terminal über die Testenkombination Strg+Alt+T öffnen und folgendes Kommando eingeben
```console
rosrun rqt_tf_tree rqt_tf_tree
```
<img src="2.png" alt="Alt-Text" title="" />

- Folgende Übersicht öffnet sich. Solange Initialisierung noch nicht abgeschlossen ist -> `odom` nicht aufgelistet

<img src="3.png" alt="Alt-Text" title="" />

- Übersicht wenn Initialisierung abgeschlossen ist -> `odom` aufgelistet

<img src="5.png" alt="Alt-Text" title="" />

