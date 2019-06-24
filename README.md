# Der Projekttester
Um den Projekttester zu verwenden müsst ihr einfach die Datei "src/Projekttester.java" in das default Packages eures Projektes kopieren.

# Konfiguration
Ihr müsst den Projekttester konfigurieren und die Klasse angeben, in welcher eure Main-Methode ist.

```
public class ProjektTester {
    // Konfiguration eurer Hauptklasse. Bitte vollqualifizierten Klassennamen plus Paket angeben.
    // Z.b. die Klasse MeinProjekt im Paket dhbw.java, muss lauten: 'dhbw.java.MeinProjekt'
    private static final String MAIN_CLASS = "Main";
```

# Problemlösung:
## 1. Der Test liefert, dass Ergebnisse um eins abweichen
Die Testdaten gehen davon aus, dass bei einem Filmnetz der Film auf dem die Netzwerksuche basiert nicht im Ergebnis enthalten ist. Bei dem Schauspielernetzwerk ebenso. D.h. ihr müsstet die originalen Filme/Schauspieler aus der Ergebnismenge raus filtern.
