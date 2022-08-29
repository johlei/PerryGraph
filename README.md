<img width="957" alt="Logo" src="https://user-images.githubusercontent.com/67282051/186034392-ea7143ed-0dda-42ec-bf8e-fa72f8f60fe1.png" style="margin-left:0; width:33%;">

*(look for english text below)*

## Einleitung

An dieser Stelle finden sich die Projektdateien für die Visualisierung des Figuren-Netzwerks aller Figuren in *Perry Rhodan*. Die interaktive Visualisierung findet sich unter: https://johlei.github.io/PerryGraph/network_visualization/. 

## Netzwerk

Das Netzwerk ist Teil der Analyse der seriellen Struktur von *Perry Rhodan*. Die Knoten im Netzwerk repräsentieren die Figuren der Serie. Kanten im Netzwerk werden angelegt, wenn die zugehörigen Artikel in der [Perrypedia](https://www.perrypedia.de) aufeinander verlinken. Alle Kanten sind ungerichtet, es wird von einer beidseitigen semantischen Affiliation ausgegangen. Knotengröße und -farbe ist in der Visualisierung des Netzwerks abhängig vom Grad der Knoten. [ForceAtlas 2](https://doi.org/10.1371/journal.pone.0098679) wurde für das grundlegende Layout verwendet; die fünf Knoten mit dem höchsten Grad wurden für Übersichtlichkeit manuell in die Mitte des Netzwerks versetzt (Basis dafür ist die topologische Nähe zu Core-Periphery-Netzwerken).

## Quellen

Die Visualisierung wurde generiert unter Verwendung von [Gephi](https://www.google.com/search?client=safari&rls=en&q=Gephi&ie=UTF-8&oe=UTF-8) und [SigmaExporter](https://github.com/oxfordinternetinstitute/gephi-plugins/tree/sigmaexporter-plugin/modules/sigmaExporter) von OII. Die Daten wurden mittels Datamining der Verlinkungsstruktur der [Perrypedia](https://www.perrypedia.de) akquiriert. 

 ## Inhalt

Dieses Repository enthält darüber hinaus: 

- **code**: Python-Notebooks für Webcrawling sowie für Netzwerkanalyse
- **network_data**: rohe Netzwerkdaten als .gexf-File für den Import in Gephi sowie für die Netzwerkanalyse aufbereitete Knoten- und Kantenlisten
- **network_visualization**: Quelldaten für die Visualisierung
- **results_network-analysis**: Ergebnisse der Netzwerkanalyse als .txt-File

*Johannes Leitgeb, August 2022*

<hr>




## Intro

You'll find here project data for visualizing the character network of all characters appearing in *Perry Rhodan*. The interactive visualization can be found here: https://johlei.github.io/PerryGraph/network_visualization/. 

## Network

The network is part of analysing the serial structure of *Perry Rhodan*. Nodes in the network represent the characters in the series. Edges are established when at least one of the corresponding articles on [Perrypedia](https://www.perrypedia.de) hyperlinks to the other. Edges are undirected, a mutual semantic affiliation is assumed. Node size and color in the network's visualization is determined by their degree. [ForceAtlas 2](https://doi.org/10.1371/journal.pone.0098679) has been used for basic layout; the five nodes with the highest degree have been manually placed in the center for clarity (on account of the network being topologically close to core periphery networks). 

## Sources

The Visualization has been generated using [Gephi](https://www.google.com/search?client=safari&rls=en&q=Gephi&ie=UTF-8&oe=UTF-8) and [SigmaExporter](https://github.com/oxfordinternetinstitute/gephi-plugins/tree/sigmaexporter-plugin/modules/sigmaExporter) made by OII. Data has been aquired by data mining the link structure of [Perrypedia](https://www.perrypedia.de).

## Contents

This repository contains:

- **code**: python notebooks for webcrawling as well as network analysis
- **network_data**: raw network data provided as .gexf file for import in Gephi as well as specially prepared node and edge lists for network analysis
- **network_visualization**: source files for visualization 
- **results_network-analysis**: results of network analysis as .txt file (in German)

*Johannes Leitgeb, August 2022*
