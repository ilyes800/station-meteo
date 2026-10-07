# Worldwide Weather Watcher

**Projet de systèmes embarqués · CESI · Deuxième année**

## Objectif

Concevoir un prototype de station météo embarquée capable d’acquérir des mesures, de les horodater et de les enregistrer sur carte SD. Le projet s’inscrit dans un scénario de surveillance météorologique en mer.

## Fonctionnement

La station décrite dans les livrables utilise un capteur BME280 pour mesurer la température, l’humidité et la pression. Elle associe également un capteur de luminosité, un GPS et une horloge RTC. Des boutons et une LED RGB permettent de choisir le mode de fonctionnement et de signaler l’état du système.

| Mode | Utilité |
| --- | --- |
| Standard | Acquérir et enregistrer les mesures. |
| Configuration | Régler les paramètres et les conserver en EEPROM. |
| Économique | Espacer les acquisitions et réduire l’activité de certains composants. |
| Maintenance | Diagnostiquer les erreurs et vérifier les composants. |

## Technologies

Arduino, modules Grove, BME280, GPS, RTC, carte SD, EEPROM. Bibliothèques documentées : `Adafruit_BME280`, `TinyGPSPlus`, `SoftwareSerial`, `RTClib`, `SD.h` et `ChainableLED`.

## Finalité du projet

Relier la conception d’un système embarqué à son fonctionnement concret : acquisition des données, gestion de plusieurs modes, stockage et diagnostic. La conception s’appuie sur des diagrammes de cas d’utilisation, d’activité et de séquence.

Cette présentation synthétise les livrables du projet. Le programme Arduino sera ajouté au dépôt lorsqu’il sera disponible. Le rapport identifie une limite de ressources sur Arduino Uno dans la fonction de mesure, avec une optimisation du programme ou un changement de carte comme pistes d’amélioration.

[Mon profil](https://github.com/ilyes800)
