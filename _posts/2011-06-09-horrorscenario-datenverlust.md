---
id: 481
title: 'Horrorscenario: Datenverlust'
date: 2011-06-09T00:18:39+00:00
author: Julian
layout: post
guid: http://www.focusaperture.com/?p=481
permalink: /horrorscenario-datenverlust/
dsq_thread_id:
  - "2237797342"
image: /wp-content/uploads/2011/06/Daten-gelöscht-Lightroom-Fragezeichen.jpg
categories:
  - Technik
tags:
  - backup
  - d90
  - datenverlust
  - formatieren
  - raid
  - windows
---
Wer noch nie wichtige Daten verloren hat, darf sich zu den wenigen Glücklichen zählen. Mir ist es heute passiert!

Ich habe eine Sicherung meiner Systempartition (C:/) eingespielt, um mich den vielen abgelaufenen Demo-Versionen zu entledigen und damit mein Windowssystem aufzuräumen. Beim Wiederherstellen der Systempartition durch ein Partitionsabbild wird die Systempartition unwiederherstellbar überschrieben. Also wird alles entfernt, das nach der Sicherung hinzu gekommen ist. Deshalb habe ich bisher Programme und Daten auf andere Partitionen ausgelagert. So musste ich nach einer Systemwiederherstellung neu hinzugekommene Programme nicht erneut installieren und die, meist noch zeitintensiveren, Programmeinstellungen erneut vornehmen. 

Leider schreiben auch die ausgelagerten Programme, die nicht für den portablen Einsatz optimiert sind, Dateien in die Systempartition, beispielsweise in die Registry. Sind diese Dateien nicht mehr vorhanden, funktionieren Programme meist nur noch fehlerhaft oder gar nicht mehr. Diese Tatsache macht das Auslagern der Programme praktisch sinnlos, sodass ich damit im letzten Jahr aufgehört habe, und nun Programme wieder standardmäßig auf C:/ installiere.

Klar hat das Auslagern der Programme auch andere Vorteile, wie die effizientere Recourcennutzung (Programme und System auf verschiedenen Speichermedien), die zu einer höheren Leistung führen soll. In der Praxis ist der Leistungsschub aber nicht zu spüren, da System und Programme ohnehin nur sehr selten gleichzeitig auf die volle Bandbreite eines Speichermediums zugreifen &#8222;wollen&#8220;. Der größte Vorteil am Auslagern der eigens installierten Programme ist für mich die Übersichtlichkeit. Man kann eigene Programmordner anlegen und es entsteht nicht dieser Windows-Ordner-Salat, wo Hersteller, Windowsdienste, vorinstallierte Tools und Programme im Programmordner gemischt werden. Das macht Apple besser!

Wie auch immer, ich habe alle installierten Programme wieder auf der Systempartition. So exportiere ich möglichst alle Programmeinstellungen und Lesezeichen bevor ich die Systempartition mit der Sicherung überschreibe. An sich kein Problem, man darf nur nichts vergessen! Genau das ist mir passiert.

Normalerweise speichert Lightroom meine Bilder beim Import auf eine eigene Bilderpartition. Warum auch immer, ist das seit Mai nicht mehr geschehen und, ohne dass es mir aufgefallen ist, wurden die Bilder in den Windows-Bilderordner auf C:/ importiert. Somit sind nun ca. 350 Bilder von Schloss Nymphenburg, der Münchener Innenstadt und dem Deutschen Museum gelöscht.

Dabei ist mir die Idee gekommen die Daten von meiner Fotospeicherkarte erneut einzulesen. Dummerweise formatiere ich die Karte nachdem alles in Lightroom importiert wurde. So sind schnell alle Bilder von der Speicherkarte entfernt &#8211; schneller als übers Menü.

Zum Glück waren die Bilder auf der Speicherkarte wiederherstellbar, obwohl ich diese mit meiner D90 formatiert hatte. Also ist das Formatieren der Speicherkarte über die Formatierungsfunktion der Kamera kein &#8222;echtes Formatieren&#8220; &#8211; ein sehr willkommener Zufall. Die wiederhergestellten Bilder haben zwar ihren ursprünglichen Namen verloren, sodass Lightroom diese nicht als schon bearbeitete erkannt hat. So konnte ich alle Fotos aus dem Deutschen Museum retten, musste aber alle erneut bearbeiten. Egal, hauptsache die Bilder sind wieder da.

Für die Wiederherstellung habe ich <a href="http://www.piriform.com/recuva/builds" target="_blank">Recuva</a> von Piriform genutzt. Allgemein mancht <a href="http://www.piriform.com/" target="_blank">Piriform</a> gute, nützliche Windows-Tools: Der allseits bekannte <a href="http://www.piriform.com/ccleaner/builds" target="_blank">CCleaner</a>, das Defragmenierungstool <a href="http://www.piriform.com/defraggler/builds" target="_blank">Defraggler</a> und <a href="http://www.piriform.com/speccy/builds" target="_blank">Speccy</a> zum Auslesen der Systemmesswerte. Alle in 32 oder 64 Bit als normale oder portable Version.

Fazit der Aktion: Fast alle Bilder des Monats Mai verloren.
  
Was lerne ich daraus: Ein aufgeräumtes System und strukturierter Workflow sind nicht zu unterschätzen; aber vor allem: BACKUP! Auch wenn in diesem Fall die Schuld bei mir lag, kann in einem anderen Fall auch die Festplatte abrauchen. Dann ist das Geschrei groß, man wünscht sich in ein solides Backupsystem investiert zu haben, als immer gehofft zu haben, man würde verschont bleiben. Man wird nicht verschont.

Ich werde mir nach meiner kommenden Amerikareise ein RAID-System einrichten. Wenn die nächste Version von Lightroom alle Daten noch effizient verschlüsseln würde, wäre das Thema Datensicherheit zumindest für meine Fotos durch!