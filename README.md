# dbuas-modul_13-applied-ds-2-ml-and-reporting-studienarbeit-darius-mix

## Github-Link

Alle Dateien sind auch über den folgenden Github Link abrufbar: https://github.com/mixd304/dbuas-modul_13-applied-ds-2-ml-and-reporting-studienarbeit-darius-mix.

## Informationen zu den Ordnern und Dateien in der Arbeit
```requirements.txt``` - enthält die benötigten Packages zum Ausführen des Python Codes (wird im Setup der readme verwendet).  <br>
Ordner ```input``` -  enthält die Daten, welche im Rahmen der Studienarbeit analysiert werden. <br>
Ordner ```output``` - enthält jeglichen Output des Python Codes, u.a. den Profiling Report der EDA.  <br>
Ordner ```notebooks``` - enthält jegliche Notebooks der Arbeit.  <br>
```notebooks\eda.ipynb``` - Notebook für die EDA.  <br>
```notebooks\analyse.ipynb``` - Notebook für die Analyse und Darstellung der Ergebnisse.  <br>

## Setup

### Install packages

#### conda
```
$ conda init
$ conda create --name dbuas-ads-2-ml-and-reporting-studienarbeit-dariusmix --file requirements.txt
$ conda info --envs
$ conda activate dbuas-ads-2-ml-and-reporting-studienarbeit-dariusmix
```

zum entfernen der neuen Umgebung aus conda:
```
$ conda deactivate
$ conda env remove --name dbuas-ads-2-ml-and-reporting-studienarbeit-dariusmix
```

Hinweis:
Sollte es beim anlegen der neuen Umgebung in conda zu einem Fehler kommen, sollten die Befehle direkt über die Anaconda prompt ausgeführt werden.