# FehrFactory -  E-Commerce Shop-Fabrik auf Azure

[![Status](https://img.shields.io/badge/Status-In%20Entwicklung-yellow)](https://opensource.org/licenses/MIT)
[![Letzter Commit](https://img.shields.io/github/last-commit/DeinUsername/fehrfactory)](https://github.com/DeinUsername/fehrfactory/commits/main)
[![GitHub Issues](https://img.shields.io/github/issues/DeinUsername/fehrfactory)](https://github.com/DeinUsername/fehrfactory/issues)
[![License](https://img.shields.io/github/license/DeinUsername/fehrfactory)](LICENSE) # Füge später ggf. eine Lizenzdatei hinzu

## Projektübersicht

`fehrfactory` ist ein ambitioniertes Projekt zur Schaffung eines wiederverwendbaren und weitgehend automatisierten Systems für die schnelle Bereitstellung mehrerer unabhängiger Online-Shops. Basierend auf der robusten Infrastruktur von Azure App Service, der Flexibilität von WordPress und der E-Commerce-Power von WooCommerce, zielt dieses Projekt darauf ab, den Prozess der Shop-Erstellung zu vereinfachen und zu beschleunigen.

Anstatt jeden Shop von Grund auf neu aufzubauen, definiert `fehrfactory` eine "Goldene Vorlage" mit grundlegenden E-Commerce-Funktionen und nutzt Infrastructure as Code (IaC) mittels ARM Templates sowie Deployment-Skripte, um die Basis für jeden neuen Shop effizient zu erstellen.

## Kernidee

Die Kernidee ist die Schaffung einer "Fabrik" für Online-Shops, in der durch Automatisierung der Infrastruktur und der Basis-Installation von WordPress und WooCommerce, neue, isolierte E-Commerce-Plattformen schnell und konsistent "produziert" werden können. Jeder Shop läuft in seiner eigenen Azure App Service Instanz mit eigener Datenbank, was Isolation, Stabilität und individuelle Budgetkontrolle ermöglicht.

## Technologien

* Azure App Service: Die gewählte Hosting-Plattform für die WordPress-Shops.
* Azure Resource Manager (ARM) Templates: Zur Definition und Bereitstellung der Azure-Infrastruktur (App Service Plan, App Service, Azure Database for MySQL).
* Azure CLI: Für die Erstellung von Deployment-Skripten zur Automatisierung des Bereitstellungsprozesses.
* WordPress: Das Content-Management-System (CMS) als Basis für die Online-Shops.
* WooCommerce: Das führende E-Commerce-Plugin für WordPress.
* PHP: Die serverseitige Skriptsprache, auf der WordPress und WooCommerce basieren.
* Git: Für die Versionskontrolle des Projekts (ARM Templates, Skripte, Dokumentation).

## Architektur (Geplant)

