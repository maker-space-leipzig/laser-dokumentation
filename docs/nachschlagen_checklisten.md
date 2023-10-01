# Checklisten

## Gerät einschalten

``` mermaid
flowchart TD
    1("Schubladenschlüssel aus dem Safe holen)
    -->2("Schublade am Laser öffnen, um an den Geräteschlüssel zu gelangen")
    -->3("Geräteschlüssel einstecken und drehen")
    -->4("Chiller einschalten")

```

## Lasern
``` mermaid
flowchart TD
    subgraph 1["Schnittmuster korrekt?"]
        1a("Maßstab korrekt?")
        -->1b("Richtige Grafiken ausgewählt?")
        -->1c("3. Werkstück groß genug?")
    end
    1-->2
    subgraph 2["Ebenen-Einstellungen korrekt?"]
        2a("Geschwindigkeit und Power korrekt?")
        -->2b("Weitere Einstellungen (Versatz etc.) korrekt?")
        -->2c("Output nur für die Ebene(n), die gelasert werden soll")
    end
    2-->3("Lüftung eingeschaltet?")
```

1. Schnittmuster korrekt?
   1. Maßstab überprüft? (Lineal-Werkzeug in Lightburn)
   2. Richtige Grafik zum Lasern ausgewählt?
   3. Werkstück groß genug?
2. Ebenen korrekt eingerichtet?
   1. Geschwindigkeit und Power passend eingestellt
   2. Weitere Einstellungen (Versatz etc.) korrekt?
   3. Output nur für die Ebene, die gelasert werden soll
3. Lüftung eingeschaltet?


## Arbeit am Laser beenden

``` mermaid
flowchart TD
    1("Stäbe entfernen und abwischen")
    1 --> 2("Materialliste mit dem Staubsauger entfernen")
    2 --> 3
    subgraph 3["Geräte ausschalten"]
        direction LR
        3a("Laser")
        -->3b("Chiller")
        -->3c("Lüftung")
    end
    subgraph 4["Schlüssel verstauen"]
        4a("Geräteschlüssel in Geräteschublade")
        -->4b("Schubladenschlüssel im Safe")
    end
    3 --> 4


```
<br>

1. Stäbe entfernen und abwischen
2. Gerät mit dem Staubsauger säubern
3. Gerät ausschalten
4. Geräteschlüssel in der Schublade ablegen
5. Schubladenschlüssel in der Schlüsselbox ablegen
6. Chiller ausschalten
7. Lüftung ausschalten
8. Sich in der "Laserliste" eintragen