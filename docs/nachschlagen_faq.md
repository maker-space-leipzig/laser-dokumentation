# Häufige Fragen & Probleme

## Lightburn zeigt nicht die aktuelle Position des Laserkopfs an

Wenn der Laserkopf am Gerät bewegt wurde, dann meldet das Gerät die aktuelle Position nicht an Lightburn zurück und daher ist Lightburn nicht auf dem aktuellen Stand. Du kannst das Problem lösen, indem du in Lightburn eine kleine Bewegung ausführst.

Nutze in Lightburn das Bedienfeld *Bewegung*, um den Laserkopf zu bewegen, zum Beispiel erst einen Schritt nach Links und anschließend wieder nach Rechts.

!!! warning "Sicherheit"
    Achte darauf, dass die Option *kontinuierliches Joggen* ausgeschaltet ist.


## Mein fertig gelasertes Werkstück ist zu groß/ klein

Hier gibt es 2 Möglichkeiten:

1. Die Größe deines Schnittmusters ist nicht korrekt. Überprüfe die Größe mit dem Lineal-Werkzeug.
2. In den Ebenen Einstellungen ist ein Versatz eingestellt. Öffne die Ebenen-Einstellungen und betätigte den Knopf "*Auf Standard zurücksetzen*", um die Einstellungen zurückzusetzen. Dies muss für jede Ebene einzeln vorgenommen werden.

!!! tip "Hintergrundinformation zu Punkt 2"
    Wenn man in Lightburn eine neue Datei anlegt, dann werden nicht automatisch die Standardeinstellungen geladen. Wenn z.B. eine Person vor dir einen Versatz eingestellt hat, dann ist dieser auch in deiner neuen Datei eingestellt.
