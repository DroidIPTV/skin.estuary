# Skin Estuary V2 for KOVI 19/20 Matrix/Nexus KN Edition #


## Installation Notes ##

It's strongly recommended to install the skin via the "Kodinerds Repo", as this is the only way to guarantee that additional 
required modules (e.g. the PVR Artwork Module) are also installed. Another advantage is that you get automatic updates when 
you install an addon from a repository and not from ZIP.

To install the Kodinerds repository visit the page "https://repo.kodinerds.net", download the repository zip (red button) 
and install it. After that you can install the skin directly from the repository under "Look & Feel", "Skins".

## Installation from Git ##

If you want to install the latest version from Git (before this has added to Kodinerds Repo) just download the Addon from here 
https://github.com/b-jesch/skin.estuary.modv2/tree/Nexus (green Code button), **rename the root folder inside the ZIP** 
from ```skin.estuary.modv2-Nexus``` to ```skin.estuary.modv2``` and choose 'install from zip' inside Kodi. **Renaming 
the root folder inside the ZIP needs unpacking/packing the zip in some cases.**

### File name flagging ###
If you want to use special flags like HDR or Dolby Vision or special 3D formats you have to name your files with proper tags, 
preferably before the file extension: 

| 3D with <br> stereoscopic detection |           MVC codec            |          Side by Side          |         Top and Bottom         |            HDR+ Files            |
|:-----------------------------------:|:------------------------------:|:------------------------------:|:------------------------------:|:--------------------------------:|
|     ![](resources/flags/3d.png)     | ![](resources/flags/3dmvc.png) | ![](resources/flags/3dsbs.png) | ![](resources/flags/3dtab.png) | ![](resources/flags/hdrplus.png) | 
|             no tagging              |             3d.mvc             |             3d.sbs             |             3d.tab             |         hdrplus., .12bit.        |


The HDR type recognition by filename for HDR/HLG/Dolby Vision has been removed.

### Animated Artwork ###

Da die Einrichtung der animierten Grafik durch das Skinhelper-Add-on übernommen wurde (das aus dem Skin entfernt wurde), wurde nun das Add-on „Animated Artwork Module“ übernommen
 die Verwaltung dieser Kunstwerke.  Animierte Kunstwerke unterliegen einigen Einschränkungen (siehe Kodi-Wiki: https://kodi.wiki/view/Artwork_types#Animated_Artwork).
Damit diese Funktion ordnungsgemäß funktioniert, müssen Sie in den Add-on-Einstellungen einen Ordner zuweisen, der alle Grafiken enthält.  Das
 Ordner **muss** ein Ordner Ihres lokalen Dateisystems sein.  Sie können eine Netzwerkfreigabe verwenden, diese **muss** jedoch an einem lokalen Mountpoint gemountet werden.
 Legen Sie alle Ihre Kunstwerke in diesen Ordner.  Unterordner sind erlaubt (ohne Verschachtelung).

Wenn Sie in Ihrer Filmbibliothek navigieren, steht Ihnen im Kontextmenü nun ein neuer Eintrag zur (Neu-)Zuweisung animierter Grafiken zur Verfügung.  Die Haut
 Unterstützt nur animierte Poster.

![](resources/setup_ap.png)

### Screenshots ###

![PVR Info](resources/screenshots/screenshot_1.png)![Embuary Info](resources/screenshots/screenshot_2.png)
![Music Visualization](resources/screenshots/screenshot_3.png)![PVR OSD](resources/screenshots/screenshot_4.png)
![TV Widget](resources/screenshots/screenshot_5.png)![Video OSD](resources/screenshots/screenshot_6.png)
![Embuary localized Infos](resources/screenshots/screenshot_7.png)
![New channel View](resources/screenshots/screenshot_8.png)
![Improved OSD](resources/screenshots/screenshot_9.png)
![simplified OSD](resources/screenshots/screenshot_10.png)
![colored flags](resources/screenshots/screenshot_11.png)
![improved nextup info](resources/screenshots/screenshot_12.png)
![improved PVR event icons](resources/screenshots/screenshot_13.png)
![various color...](resources/screenshots/screenshot_14.png)
![...and font schemes](resources/screenshots/screenshot_15.png)
![Audio DSP](resources/screenshots/screenshot_16.png)
![Flix Landscape](resources/screenshots/screenshot_17.png)
