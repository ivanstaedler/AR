Augmented Reality mit AR.js

Für das RDZ Wattwil | FutureCity:Digital | 2022


Grundsätzliche Funktionsweise:
Auf dem Handy oder Tablet wird bspw. via Link oder QR-Code eine Webseite aufgerufen. Diese Webseite aktiviert die Gerätekamera (das muss bestätigt werden).
https://rdz-wattwil.github.io/kBwR/AR.html
Die «durchsichtige» Webseite sucht dann nach bestimmten Markern (die sich bspw. in der Future City befinden), die jeweils einen Wert aufweisen. 
Je nach Wert wird dann ein Objekt auf dem Display dargestellt, wo der Marker sich befindet.
Das erscheinende Objekt kann dann gedreht und vergrössert / verkleinert werden, bis es in die City passt. 
Dann kann das Objekt mit dem Handy von allen Seiten betrachtet werden, solange der Marker sichtbar ist.

Wichtig:
Die Webseite ist so programmiert, dass sie immer nach einem Objekt sucht, dass als Dateiname den dreistelligen Wert des Markers hat. Der Marker 13 sucht also nach dem Objekt, das mit «013.obj» benannt ist. Wenn dieses nicht auffindbar ist, weil es bspw. «13.obj» heisst, passiert nichts.
Die Objekte müssen auch alle im vorgesehenen Ordner abgelegt werden, weil die Webseite nur dort sucht: https://github.com/rdz-wattwil/kBwR/tree/main/modelle 
Die Marker sollten möglichst flach sein und nicht spiegeln – also nicht zerknittern und nicht glänzend laminieren.
Es kann sein, dass gewisse Marker schlechter erkannt werden als andere. Dann den «schlechten Marker» einfach überspringen und das Objekt mit der nächsten Nummer hochladen. (Die Objekte sind ziemlich klein in der Dateigrösse.)

Marker
Die folgenden Marker wurden auf der Webseite eingerichtet. Die Nummern 0 – 29 sind farblos (nur .obj), die Nummern 030 bis 035 sind vorbereitet für farbige Modelle. Hier muss zusätzlich zum .obj noch die entsprechende .mtl-Datei hochgeladen werden mit der gleichen Nummer (z.B. «032.obj» und «032.mtl») 
Falls mehr benötigt werden, kann man sich gerne bei mir melden.

Es ist möglich, den Quellcode zu übernehmen, um eine eigene Zusammenstellung zu machen. Entsprechende Kommentare sind eingefügt. Die Marker sind nicht von mir.
Viel Spass damit, jerome.zgraggen@phsg.ch
