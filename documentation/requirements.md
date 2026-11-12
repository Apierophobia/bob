# Anforderungen

## Teilfunktionen

- Hindernis Erkennung
    - Automatisches Anhalten vor Hindernissen
        - Visualisierung des Abstands
    - Autonomes Umfahren einfacher Hindernisse
        - Laser-Messgerät / 1D-LiDAR-Sensor für Messung des Abstands
            - 1x vorne, um vorausliegende Hindernisse frühzeitig zu erkennen
            - 1x seitlich, um den Abstand zum Hindernis während des Umfahrens zu halten

- Autonome Spurhaltung
    - Reflexionssensor-Array zur Erkennung von Kontrastunterschieden unter dem Auto
    - Korrekturen der Messdaten über einen PID-Regler
