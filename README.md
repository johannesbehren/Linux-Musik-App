
Vorstellung
---

Eine lokale App, mit der man allerlei Musikdateien abspielen, gruppieren, speichern kann. Übersichtliche und einfache Bedienung von Musikdateien und Steuerung.

---
Design
---

**Bereiche**
1. Informationsleiste für Ansichten
2. Ordner Spalte für Auflistung der Ordner
3. Spieler Leiste für Steuerung
4. Hauptbereich für Songs und Songtext
5. Dateitext für Anzeige des Textes in einer Datei 

**Farben**
- Neon grün als Hauptfarbe und Schwarz als Hintergrund.

_Nachempfunden durch Fallout_

**Schrift**
- Eigene Blockart / Minecraft. 24px groß.

_Nachempfunden durch Minecraft_

**Bilder**
- Eigene oder aus der Distro Linux Mint (/usr/share/icons/Adwaita/symbolic/)

**Musikspeicherort**
- Kein extra Ordner für speichern der Musikdateien an sich, sondern verlinkung der Ordner mit Musik drinnen (./Musik/*)

---
Bilder (./Bilder/*.svg) und Eklärung
---

### Informationsleiste

#### -- Linke Seite --

Logo
  - ![Music.svg](./Bilder/Music.svg) Für Anwendungsfunktionsinformationen der Musik App
  - Anleitung der Knöpfe und Anwendungen aller Sachen, die eine Funktion haben

#### -- Mittlerer Bereich --

Titel
  - ![Multimedia](./Bilder/Multimedia.svg) Titelbild links neben dem Titel des offenen Ordners
  - Der Name des offenen Ordners wird angezeigt

#### -- Rechte Seite --

Suche
  - ![Search](./Bilder/Search.svg) Zum finden der Ordner & Dateien
  - Als Geistertext steht "Ordner-/Dateiname suchen"

Edetieren
  - ![Edit](./Bilder/Edit.svg) Zur Änderung der Anordung der Ordner und Dateien

Einstellungen
  - ![Settings](./Bilder/Settings.svg) Für das Einstellen der Website
      - ![SettingsOpen](./Bilder/SettingsOpen.svg) Wenn man es offen hat
  - Darin stellt man die Text bezogenen, Farben … ein

Formate
  - ![PlayerPhone](./Bilder/PlayerPhone.svg) Handyformat ausgewählt 
  - ![PlayerPC](./Bilder/PlayerPC.svg) PC Format ausgewählt

### Ordner Spalte

Linke Seitenspalte
  - ![SidebarLeft](./Bilder/SidebarLeft.svg) Zum Ein-/Ausklappen der Ordner

Mag Ich
  - ![Favorite](./Bilder/Favorite.svg) Beinhaltet die ausgewählten "Mag ich" Dateien
    - Dieser Ordner ist standartmäßig dabei

Ornder
  1. ![Folder](./Bilder/Folder.svg) Wird im Ordner Bereich benutzt, für visuelles darstellen eines Ordners
  2. ![FolderAdd](./Bilder/FolderAdd.svg) Visuelle Hilfe, Ordner einzufügen
      - Entweder einen Ordner aus dem System einfügen oder neuen Ordner erstellen 
  3. ![FolderOpen](./Bilder/FolderOpen.svg) Visuelle Anzeige eines ausgewählten Ordners

Pin
  1. ![PinNot](./Bilder/PinNot.svg) Zum anpinnen der Dateien im Ordner
  2. ![Pin](./Bilder/Pin.svg) Zeigt die Datei als angepinnt oben an

### Spieler Leiste

#### -- Linke Seite --

Vorher
  - ![Previous](./Bilder/Previous.svg) Zum zurückspringen vorheriger Datei

Start, Stop
  - ![Play](./Bilder/Play.svg) Zum starten einer Datei
  - ![Stop](./Bilder/Pause.svg) Zum stoppen einer Datei
  
Nächster
  - ![Next](./Bilder/Next.svg) Zur nächster Datei springen

Wiederholung
  - ![Repeat](./Bilder/Repeat.svg) Wiederholung ist aus
    - ![RepeatOne](./Bilder/RepeatOne.svg) Wiederholt die Datei von vorne
    - ![RepeatAll](./Bilder/RepeatAll.svg) Wiederholt die Liste der Dateien vom Anfang nach der letzten abgespielten Datei

Zufall
  - ![Shuffle](./Bilder/Shuffle.svg) Die Liste der Dateien wird weiter in Ordnung gespielt
  - ![ShuffleActive](./Bilder/ShuffleActive.svg) Spielt Dateien ohne Ordnung im selben Ordner

#### -- Mittlerer Bereich --

DVD
  - ![DVD](./Bilder/DVD.svg) Ersatzzeichen für ein nicht verfügbares Bild

#### -- Rechte Seite --

Lautstärke
  - ![VolumeMute](./Bilder/VolumeMute.svg) Ton ist aus (0%)
    - ![VolumeLow](./Bilder/VolumeLow.svg) Ton ist leise (1%-30%)
    - ![VolumeMedium](./Bilder/VolumeMedium.svg) Ton ist mittellaut (31%-70%)
    - ![VolumeMax](./Bilder/VolumeMax.svg) Ton ist laut (71%-100%)

### Hauptbereich

Datei
  1. ![File](./Bilder/File.svg) Wird im Hauptbereich benutzt, für visuells darstellen der Dateien
  2. ![FileAdd](./Bilder/FileAdd.svg) Visuelle Hilfe, Dateien in Ordner einzufügen

Bilder
  1. ![Image.](./Bilder/Image.svg) Ersatz für Bilder, die nicht gefunden wurden in der Musikdatei
  2. ![ImageInsert](./Bilder/ImageInsert.svg) Wird benutzt, um ein fehlendes Bild beizufügen
      - Ermöglicht ein anderes Bild einzufügen, kann auch das vorhandene Bild austauschen

Liste
  1. ![ListWide](./Bilder/ListWide.svg) Zeigt die Dateien ganz breitig untereinander anzuzeigen
  2. ![ListBlock](./Bilder/ListBlock.svg) Zeigt die Dateien als Kacheln nebeneinander und untereinander

Mag Ich
  - ![FavoriteNot](./Bilder/FavoriteNot.svg) Standartmäßig links an jeder Datei positioniert
  - ![Favorite](./Bilder/Favorite.svg) Zeigt an, das es im "Mag ich" Ordner verlinkt ist

### Dateitext

Rechte Seitenspalte
  - ![SidebarRight](./Bilder/SidebarRight.svg) Zum Ein-/Ausklappen des Textes der zurzeit spielenden Datei

Ersatzbild
  - ![FileText](./Bilder/FileText.svg) Ersatz Bild für nicht vorhandenen Text

---
Funktionen
---


![Search](./Bilder/Search.svg) Suche
  - Ermöglicht es Dateien aus jeden Ordner zu finden und anzuzeigen, mit Informationen: Ort des Befindens und die Dauer dieser Datei
  - Beim anklicken dieser Datei, wird die App den Ordner öffnen, zur Datei scrollen (sofern nicht sichtbar) und es markieren

![Settings](./Bilder/Settings.svg) Einstellung
  - Ermöglicht es die Farben des Hintergrund, Schrift und Bilder zu ändern
  - Einstellung abspeichern und abrufen.

![PlayerPhone](./Bilder/PlayerPhone.svg)
  - Zeigt die App klein an
  ![Vorschau Handy](./Vorschau%20Handy.svg)

![PlayerPC](./Bilder/PlayerPC.svg) PC
  - Zeigt die App groß an
  ![Vorschau PC](./Voschau%20PC.svg)

![FolderAdd](./Bilder/FolderAdd.svg) Ordner hinzufügen
  - Ermöglicht es Ordner mit dem Inhalt (oder keinem) einzufügen und automatisch als verlinkung abzuspiechern

![FileAdd](./Bilder/FileAdd.svg) Datei einfügen
  - Ermöglicht es Dateien in dem offenem Ordner einzufügen

![ImageInsert](./Bilder/ImageInsert.svg) Bilder einfügen
  - Ermöglicht es Bild neben der Datei einzufügen, auch wenn ein Bild schon exestiert, kann dieses ersetzt werden

![Favorite](./Bilder/Favorite.svg) Favorit
  - Ermöglicht es einzelne Dateien in zu favorisieren und in dem Ordner "Favorten" als duplikat anzuzeigen

---
