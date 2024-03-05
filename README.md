# dbuas-modul_13-applied-ds-2-ml-and-reporting-studienarbeit-darius-mix

## Github-Link

Alle Dateien sind auch über den folgenden Github Link abrufbar: https://github.com/mixd304/dbuas-modul_13-applied-ds-2-ml-and-reporting-studienarbeit-darius-mix.

## Informationen zu den Ordnern und Dateien in der Arbeit
```requirements.txt``` - enthält die benötigten Packages zum Ausführen des Python Codes (wird im Setup der readme verwendet).  <br>
Ordner ```input``` -  enthält die Daten, welche im Rahmen der Studienarbeit analysiert werden. <br>
Ordner ```output``` - enthält jeglichen Output des Python Codes, u.a. den Profiling Report der EDA.  <br>
Ordner ```notebooks``` - enthält jegliche Notebooks der Arbeit.  <br>
```notebooks\eda.ipynb``` - Notebook für die EDA.  <br>
```notebooks\eda_profiling_report.ipynb``` - Notebook für die Erstellung des Profiling Reports.  <br>
```notebooks\hyperparameter_gradient_boosting.ipynb``` - Notebook für die Optimierung der Hyperparameter des Gradient Boosting Modells.  <br>
```notebooks\main.ipynb``` - Notebook für die Analyse und Darstellung der Ergebnisse.  <br>

## Setup

### Install packages

#### conda
```
$ conda init
$ conda create -n dbuas-ads-2-ml-and-reporting-full-studienarbeit-dariusmix python=3.11 -y
$ conda activate dbuas-ads-2-ml-and-reporting-full-studienarbeit-dariusmix
$ pip install -r requirements.txt
```

#### zusätzliches Environment zur Erstellung des ydata profiling reports
```
$ conda create -n profiling_report python=3.11 -y
$ conda activate profiling_report
$ pip install -r requirements_profiling.txt
```

#### Anzeige der vorhandenen Environments
```
$ conda info --envs
```

#### entfernen der Umgebung aus conda
```
$ conda info --envs
$ conda deactivate
$ conda env remove -n dbuas-ads-2-ml-and-reporting-full-studienarbeit-dariusmix
$ conda env remove -n profiling_report
```

Hinweis:
Sollte es beim anlegen der neuen Umgebung in conda zu einem Fehler kommen, sollten die Befehle direkt über die Anaconda prompt ausgeführt werden.