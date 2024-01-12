# Altersbestimmung von Kunden
Ein Netzwerk-Supermarkt führt ein computergestütztes Bildverarbeitungssystem ein, um Fotos von Kunden zu verarbeiten. Die Erfassung von Fotos an der Kasse soll dazu dienen, das Alter der Kunden zu bestimmen, um:

* Einkäufe zu analysieren und Produkte vorzuschlagen, die das Interesse der Kunden dieser Altersgruppe wecken könnten;
* Die Integrität der Kassierer beim Verkauf von Alkohol zu überwachen.

***Ziel:*** Ein Modell entwickeln, das anhand eines Fotos das ungefähre Alter einer Person bestimmt.

Wir haben einen Datensatz von Fotos von Menschen zur Verfügung, die mit ihrem Alter beschriftet sind.

***Aufgabe:*** Erreichen Sie einen MAE-Wert auf dem Testset von höchstens 8.

# Datenbeschreibung

Wir werden Daten von der Website [ChaLearn Looking at People](http://chalearnlap.cvc.uab.es/dataset/26/description/) verwenden. Sie befinden sich im Ordner /datasets/faces/.

In [dem Artikel zu dem Datensatz](http://people.ee.ethz.ch/~timofter/publications/Agustsson-FG-2017.pdf), den wir verwenden, beträgt der MAE-Wert 5,4 - ein MAE-Wert von unter 7 wäre also ein ausgezeichnetes Ergebnis!

Wir haben einen Ordner mit allen Bildern (/final_files) und eine CSV-Datei labels.csv mit zwei Spalten: file_name - der Dateiname des Bildes und real_age - das tatsächliche Alter der Person auf dem Foto.

# Projektschritte

1. Führen Sie eine explorative Datenanalyse des Bildsatzes durch.
2. Bereiten Sie die Daten für das Training vor.
3. Trainieren Sie das neuronale Netzwerk und bewerten Sie seine Qualität.

## Fähigkeiten und Werkzeuge
Tags: Computer Vision, Bildverarbeitung, neuronale Netzwerke

<img src="https://img.shields.io/badge/Keras-black?style=flat-square&logo=keras&logoColor=red"/><img src="https://img.shields.io/badge/Python-Blue?style=flat-square&logo=pythony&logoColor=yellow"/>
## Tätigkeitsbereiche:
Geschäft, Offline

## Hauptpunkte der Forschung:
* Erforschende Datenanalyse
* Modelltraining
* Analyse des trainierten Modells
