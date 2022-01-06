# KincoExampleCO2
 Example program of CO2 Display for 4 - 20 mA Sensor in Kinco HMI
 
Dieses Beispielprogramm für ein Kinco GT070HE zeigt, wie man leicht einen 4 - 20 mA-Messwert auf dem HMI skalieren und darstellen kann. Ein simulierter Temperatursensor mit einem 4 - 20 mA-Messwert wird in einen Wert mit Einheit skaliert. Es beinhaltet folgende Funktionen und Anpassungen:

* Zahlenanzeige für CO2 mit Skalierung im Anzeigelement und Einheit als Label (ppm)
* Rechtsbündige Ausrichtung des Werts für bessere Darstellung
* Anpassung aller Schriftarten auf Arial Nova für attraktive Darstellung
* Beispiel Grafische Schrift (Bitmap-Schrift) zur Darstellung von Sonderzeichen (tiefergestellte 2 in CO2)
* Abgerundetes Rechteck, Überschrift für Messwert und Icon als statisches Bitmap (importiertes PNG)
* Simulation eines unskalierten Rohwertes als 4-20-mA-Messwert (wie im Analogmodul für KS-SPS)
* Eigene Button (selbst erstellte VG-Vektorgrafik) für Buttons für Wertänderung (Hoch / Runter) mit Jog-Funktion (Multizustandschalter) 
* Anpassung der Nummerntastatur mit passender Farbdarstellung und Arial Nova als Tastaturschriftart
* Anpassung der Systemmeldung für falsche Eingabe des Rohwertes - Sprache und Schriftart der Meldung
* Timer rechts unten, der beim Aufruf des Fensters (Start des HMI) den simulierten Messwert auf 5500 setzt

Das Projekt wurde für das Kinco HMI GT070HE mit einer Auflösung von 1.024 x 600 Pixeln erstellt. Die Kinco HMI der GL100E und GT100E-Serie sowie das GT070E2 haben eine gleiche Auflösung. Das Projekt kann für diese Modelle einfach per Rechtsklick auf das HMI in DTools konvertiert werden. 
Für HMI mit anderer Auflösung ist eine Konvertierung über diesen Weg ebenfalls möglich, es werden aber wahrscheinlich Nacharbeiten notwendig, um die Darstellung an das HMI anzupassen.

Das Programm wurde in der Entwicklungssoftware Kinco DTools 3.5.3 erstellt.
