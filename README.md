# Worldwide Weather Watcher

**Systèmes embarqués · CESI · Deuxième année**

## Objectif

Concevoir une station météo embarquée capable de relever des données, de les horodater et de les enregistrer, dans un scénario de surveillance météorologique en mer.

## Réalisation

Conception d’un système Arduino associant des capteurs de température, d’humidité, de pression et de luminosité, un GPS, une horloge et une carte SD. Des boutons et une LED signalent l’état du système et permettent d’interagir avec ses modes.

| Mode | Fonction |
| --- | --- |
| Standard | Acquérir et enregistrer les mesures. |
| Configuration | Régler et mémoriser les paramètres. |
| Économique | Espacer les acquisitions pour limiter l’activité des composants. |
| Maintenance | Vérifier les composants et diagnostiquer les erreurs. |

## Résultat présenté

Une conception documentée de la station : choix des composants, organisation des quatre modes et diagrammes de fonctionnement. Le projet relie les mesures des capteurs, leur datation et leur stockage.

Le bilan technique identifie une limite de ressources de l’Arduino Uno sur la fonction de mesure. Il propose d’optimiser le programme ou d’adapter la carte : une occasion de prendre en compte les contraintes réelles du matériel.

## Compétences acquises

- Analyser un besoin et choisir des composants adaptés.
- Comprendre les échanges entre capteurs, programme et stockage.
- Organiser le comportement d’un système en plusieurs modes.
- Modéliser les interactions avec des diagrammes UML.
- Identifier les contraintes de mémoire et les pistes d’amélioration d’un prototype.

**Outils :** Arduino, modules Grove, BME280, GPS, RTC, carte SD, EEPROM et UML.

*Présentation fondée sur les livrables du projet.*

[Retour au profil et au CV](https://github.com/ilyes800)
