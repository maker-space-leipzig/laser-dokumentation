# Diese Dokumentation bearbeiten

Die Dokumentation wurde mit [MkDocs](https://www.mkdocs.org/){:target="_blank"} erstellt. Die Bearbeitung erfolgt über ein direktes Editieren der Markdown-Dateien.

Zur Erstellung fertigen HTML-Version muss über MkDocs ein Build-Prozess ausgeführt werden.

## Arbeiten mit MkDocs

### Am Laser-PC des Maker Space
text text text text text text text text text text text text text text text text text text text text text text

<br>
### Zuhause bearbeiten

**Zugang zum GitHub-Repository**
Für die Bearbeitung zuhause sollte das GitHub-Repository genutzt werden. Bitte wende dich an die zuständigen Personen für das FabLab, um einen Zugang zu erhalten.

**MkDocs und Erweiterungen installieren**

1. Python installieren: [https://www.python.org/downloads/](https://www.python.org/downloads/){:target="_blank"}
2. Python Package Manger installieren
   1. Installationsskript runterladen: [https://bootstrap.pypa.io/get-pip.py](https://bootstrap.pypa.io/get-pip.py){:target="_blank"}
   2. Installationsskript ausführen
3. Im Terminal bzw. in der Powershell folgenden Befehl ausführen:
<br>`pip install mkdocs mkdocs-material mdx_truly_sane_lists`

<br>
**Vorschau beim Bearbeiten**

1. Beileigende Batch-Datei *mkdocs_serve.bat* ausführen
3. Die Vorschau ist im Browser erreichbar unter [http://127.0.0.1:8000](http://127.0.0.1:8000){:target="_blank"}

<br>
**Build-Prozess**

1. Beileigende Batch-Datei *mkdocs_build.bat* ausführen
2. Die fertige HTML-Version befindet sich im Unterordner *site*

## Markdown-Syntax
Du kannst dich beim Bearbeiten an den bestehenden Inhalten orientieren. Ein leichter Einstieg ist immer vorhandene Inhalte zu kopieren und abzuändern. Wenn du das tust, dann solltest du darauf achten, dass die Formatierung (z.B. Texteinrückung) gleich bleibt.

- [Markdown-Cheatsheet](https://www.markdownguide.org/cheat-sheet/){:target="_blank"}
- [Emojis](https://squidfunk.github.io/mkdocs-material/reference/icons-emojis/){:target="_blank"} (Empfehlung: Suchfeld benutzen)
- [Bausteine des Themes](https://squidfunk.github.io/mkdocs-material/reference/admonitions/){:target="_blank"} (Hinweiskästen, Tabs etc.)
- [Mermaid-Dokumentation](https://mermaid.js.org/intro/){:target="_blank"} (Ablaufdiagramme)
- [Mermaid-Cheatsheet](https://jojozhuang.github.io/tutorial/mermaid-cheat-sheet/){:target="_blank"}

### Breite von Bildern definieren
Bilder können in der Breite auf 40%/ 50%/ 60%/ 70%/ 80% der verfügbaren Fläche skaliert werden. Hierfür muss einfach die Bezeichnung *img40*/ *img50*/ *img60*/ *img70*/ *img80* im Feld für die Bildbeschreibung eingetragen werden.

`![img60](Grafik - Lasercutter.png)` entspricht 60% Breite der verfügbaren Fläche

## Empfohlene Software zur Bearbeitung

- [VSCode](https://code.visualstudio.com/){:target="_blank"}
- VSCode-Erweiterungen
  - Markdown All in One
  - Markdown Table
  - Mermaid Markdown Syntax Highlighting
  - Mermaid Preview