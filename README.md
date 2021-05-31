---
title: Studienleistung 2
author: Alexander Bazo und Jakob Fehle
documentclass: scrartcl
classoption:
  - a4paper
header-includes: |
    \usepackage{german}
	\usepackage{xcolor} 
    \usepackage[a4paper,left=2.5cm, right=2.5cm,top=2.5cm, bottom=3cm]{geometry}
    \usepackage{fancyhdr}
    \pagestyle{fancy}
    \fancyhf{}
    \rhead{Webtechnologien}
    \lhead{SL2}
    \fancypagestyle{plain}{
      \fancyhf{}
      \rhead{Webtechnologien}
      \lhead{SL2}}


---

## Eine kleine To-Do Liste

Implementieren Sie in dieser Aufgabe mit Hilfe von JavaScript eine einfache To-Do Liste, mit der Sie über ein _Input_ - Feld Items hinzufügen können. Sobald Sie die "Enter"-Taste betätigen oder auf ein "Bestätigungs" -Icon klicken, soll ein neues Listenelement mit dem Inhalt des Inputfeldes erstellt und an eine Liste angehängt werden. Achten Sie darauf, dass keine leeren Items generiert werden können. Mit Hilfe eines Doppelklicks auf ein Listenitem, können Sie dieses auch wieder aus der Liste entfernen. [\textcolor{blue}{Hier}](https://homepages.uni-regensburg.de/~kom13409/WTSS2020/SL2/ToDoList.html) finden Sie eine kleine Demo-Anwendung, die die grundlegende Funktionalität der Liste zeigt. 

Die folgenden Tutorials sollen Sie dabei unterstützen, die Liste zu designen und die Funktionalität zu implementieren:

- [\textcolor{blue}{Hier}](https://developer.mozilla.org/de/docs/Web/API/EventTarget/addEventListener) finden Sie Informationen zum Registrieren von Events und Listenern
- [\textcolor{blue}{Hier}](https://www.w3schools.com/jsref/met_node_appendchild.asp) lernen Sie, wie Sie neue DOM-Elemente programmatisch erstellen

- [\textcolor{blue}{Hier}](https://developer.mozilla.org/en-US/docs/Web/API/KeyboardEvent/key) können Sie mehr über Keyboard Events erfahren, um Tastatureingaben abzufangen.
- [\textcolor{blue}{Hier}](https://www.w3schools.com/jsref/obj_mouseevent.asp) erfahren Sie mehr über Maus-Events, um auf Klicks der Maus zu lauschen.

- [\textcolor{blue}{Hier}](https://keycode.info/) finden Sie die Keycodes heraus, um auf Eingaben bestimmter Tasten reagieren zu können.
- Wie Sie dynamisch CSS-Klassen Elementen hinzufügen und entfernen, können Sie [\textcolor{blue}{hier}](https://developer.mozilla.org/de/docs/Web/API/Element/classList,) nachlesen.
- Mehr zu Farben in CSS erfahren Sie [\textcolor{blue}{hier}](https://www.w3schools.com/cssref/css_colors.asp).
- Mehr Informationen zu Rahmen ("Border") in CSS erhalten Sie [\textcolor{blue}{hier}](https://www.w3schools.com/css/css_border.asp).
- Mehr zum Design des Mauszeigers ("Cursor") in CSS können Sie  [\textcolor{blue}{hier}](https://www.w3schools.com/cssref/pr_class_cursor.asp) erfahren.

------

*Abgabekriterien:*

Laden Sie Ihre Antworten bis spätestens 18.6.2021 (23:59 Uhr) als zip-komprimierten Ordner auf GRIPS hoch.  Benennen Sie die einzelnen Dateien pro Aufgabe sinnvoll und verwenden Sie geeignete Formate:

- Aufgabe 1: Das gesamte Projekt (HTML, JS, CSS)

Der Name der Datei ergibt sich aus dem Präfix „SL_WT_SS21“, der Nr. der Studienleistung, ihrem Vor- und Nachnamen jeweils getrennt durch _ .

 

Beispiel: **SL_WT_SS21_2_Max_Mustermann.zip**

