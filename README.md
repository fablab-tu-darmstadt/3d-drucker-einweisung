# 3D-Drucker-Einweisung
Diese Einweisung ist für die im TUD FabLab vorhandenen 3D-Drucker:
+ Prusa MK3S
+ Prusa MK3S MMU2
+ Prusa MK2.5S
+ Ultimaker 2
+ Makerbot Replicator 2X
+ 3Dator

**Personen ohne Einweisung ist es untersagt die im FabLab vorhandenen Drucker selbstständig zu benutzen, um Beschädigungen zu vermeiden.** Einweisungen für die 3D-Drucker sind von den Betreuern zu erhalten. Inhalt der Einweisung ist die Erklärung des 3D-Drucker Workflows und der Sachgerechten Bedienung der 3D-Drucker. Hat der Benutzer die Inhalte verstanden kann die Einweisung unterschrieben werden.

## Inhaltsverzeichnis
1. Regeln und Hinweise
2. 3D-Modell erstellen
3. 3D-Modell slicen
4. 3D-Modell ausdrucken
5. Bezahlen

## 1. Regeln und Hinweise
1.1 3D-Druck fällt unter den Begriff **Rapid Prototyping** jedoch kann ein Druck je nach Größe und Einstellungen in der Druckersoftware (Slic3r) mehrere Stunden dauern. Die Betreuer helfen die Dauer abzuschätzen.  
1.2 Der Benutzer soll sich innerhalb des FabLabs aufhalten bis der Druck der ersten Schicht abgeschlossen ist, um zwischenzeitlich den Druck zu kontrollieren. Erfahrungsgemäß ist die Wahrscheinlichkeit eines Fehlers während des Drucks an dieser Stelle am häufigsten  
1.3 Anleitung sind exakt zu beachten. Falls Unsicherheiten auftreten kann jederzeit ein Betreuer gefragt werden.  
1.4 Verbrennungsgefahr an heißen Teilen:  
1.4.1 Extruder wird sehr heiß (Druckerdüse) ! Nicht direkt berühren.  
1.4.2 Bodenglasplatte des Ultimakers 2 und die Federstahlplatten werden sehr heiß. Erst abkühlen lassen und vorsichtig testen.  
1.5 Drucker ausschalten:  
1.5.1 Falls der Drucker nicht richtig funktioniert ( Geräuschpegel, falsche Bewegungen)  
1.5.2 Falls der Drucker nicht mehr benötigt wird:  
1.6 Bei Beschädigungen in jeder Form sind die Betreuer sofortig zu informieren.  
1.7 Keinen Schaber, Messer oder Ähnliches verwenden, um Objekte von der Plattform zu lösen, denn dies beschädigt die Folie.  
1.8 Nach erfolgreichem Drucken Wiegen und entsprechend Bezahlen!  

## 2. 3D-Modell
Das zu druckende Modell kann mittels CAD-Software erstellt oder Online auf Websiten ( Thingiverse, YouMagine, MyMiniFactory oder GrabCAD ) herruntergeladen werden.  

### 2.1 CAD-Sodtware
Mit CAD (computer-aided-design) wird die Idee in ein 3D-Modell eingegossen. Dazu gibt es eine Fülle von Programmen. Im Open Source Bereich sind 2 Programme hervorzuheben, die unter Linux und Windows funktionieren:
+ FreeCAD (Angelehnt an professionelle CAD-Software, aber relativ einfach zu bedienen)
+ OpenSCAD (Skriptsprache für Konstruktion aus geometrischen Grundkörpern)  

Darüber hinaus gibt es kostenpflichtige (proprietär) Software, die kostenlos für Studenten ist:
+ Autodesk Fusion360
+ PTC Creo
+ Solid Edge, Siemens NX

### 2.2 Kontruktionsregeln
Generell gilt bei der Konstrution von Werkstücken, die Regeln des gewählten Fertigungsprozesses mit einfließen zu lassen. Im 3D-Druck FDM sind folgende Regelen zu beachten:
+ Größe des Modells 
    + Abhängig von der Größe des Arbeitsraumes eines Druckers:
        + Prusa         250 x 210 x 210 mm
        + Ultimaker     223 x 223 x 205 mm
        + Makerbot      285 x 153 x 155 mm
        + 3Dator        180 x 170 x 270 mm
+ Brigheing über 80mm ist nicht erlaubt
+ Überhänge mit einem Winkel über 65° sind nicht erlaubt
+ Das Aspektverhältnis (Höhe / laterale Ausdehnung) des Drucks darf den Wert 10 nicht überschreiten
+ Drucken ohne Stützstrucktur
    + TODO
+ Drucken mit Stützstrucktur
    + TODO
    
### 2.3 Dateiformat
Ist die Konstruktion des gewünschten Modells abgeschlossen, wird das CAD-Modelle wahlweise in die Dateiformate STL, AMF oder OBJ exportiert.

## 3. 3D-Modell slicen
Im FabLab Darmstadt wird der PrusaSlic3r genutzt. An dieser Stelle sei erwähnt das es 
Software zum slicen der Modelle:
+ PrusaSlic3r (OpenSource)
+ Cura (Opensource)
+ Slic3r (Opensouce)
+ Simplyfy3d
## 4. 3D-Modell ausdrucken

## 5. Bezahlen
