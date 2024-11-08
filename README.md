# heating-blueprints
Home Assistant Blueprints for Heating

Einfache Heizungsteuerung nach einem Heizplan (Zeitplan). Die Einschaltzeiten repräsentieren das Heizprofil Kompfort\n
Berücksichtigt werden zwei Heizprofile Komfort & ECO\n
Ein geöffnetes Fesnter, schaltet das Thermostat in den Off Modus\n
Das Schließen des Fesnters, schaltet das Thermostat in den Heat Modus und der laut Zeitplan voreingestellten Soll-Temperatur\n
Bei Abwesenheit (Letze Person verlässt die Heim Zone) aller Personen wird die ECO Temperatur eingestelt\n
Bei Anwesenheit wird die gemäß dem Zeitplan vorgesehene Soll-Temperatur eingestellt\n
Ein Helfer Heizsaison sorgt dafür, das Die Automatisierung nur während der Heizsaison ausgeführt wird\n

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2FSmartHomeForDummies%2Fheating-blueprints%2Fblob%2Fmain%2Fheizplan.yaml)

