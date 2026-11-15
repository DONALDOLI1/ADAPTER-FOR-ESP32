<div align="center">

# Terminal Adapter for ESP32

**OLITECH · Conception d'une carte d'adaptation pour ESP32**

![Project](https://img.shields.io/badge/Project-Design%20stage-orange)
![MCU](https://img.shields.io/badge/MCU-ESP32-blue)
![CAD](https://img.shields.io/badge/CAD-KiCad-blue)
![Languages](https://img.shields.io/badge/README-FR%20%7C%20EN-informational)

Design of an ESP32 adapter board using KiCad.

</div>

---

**Brand / Marque:** OLITECH  
**Designer / Concepteur:** OLI OLI DONALD  
**Country / Pays:** Cameroon / Cameroun  
**Design software / Logiciel de conception:** KiCad  
**Contact:** [oliolidonald186@gmail.com](mailto:oliolidonald186@gmail.com)

## Table of contents

- [🇫🇷 Français](#-français)
  - [Présentation](#présentation)
  - [Objectifs du projet](#objectifs-du-projet)
  - [Architecture et principe de conception](#architecture-et-principe-de-conception)
  - [Caractéristiques techniques](#caractéristiques-techniques)
  - [Documents techniques](#documents-techniques)
  - [État et limites du projet](#état-et-limites-du-projet)
- [🇬🇧 English](#-english)
  - [Overview](#overview)
  - [Project objectives](#project-objectives)
  - [Architecture and design principle](#architecture-and-design-principle)
  - [Technical specifications](#technical-specifications)
  - [Technical documents](#technical-documents)
  - [Project status and limitations](#project-status-and-limitations)
- [Contact](#contact)

---

## 🇫🇷 Français

### Présentation

Terminal Adapter for ESP32 est un projet de conception d'une carte électronique d'adaptation destinée à faciliter le raccordement des broches d'une carte de développement ESP32 DevKitC-32D.

L'objectif est de concevoir une interface permettant de reporter les connexions de l'ESP32 vers des points de raccordement organisés sur deux rangées. Cette disposition vise à simplifier le câblage des capteurs, des modules électroniques et des autres périphériques utilisés dans les projets à base d'ESP32.

Le schéma électronique et le circuit imprimé ont été conçus avec le logiciel KiCad.

Il s'agit actuellement d'un projet de conception numérique. La carte n'a pas encore été fabriquée physiquement.

### Objectifs du projet

- Faciliter l'accès aux broches de la carte ESP32.
- Simplifier le raccordement des capteurs et périphériques externes.
- Améliorer l'organisation du câblage des montages électroniques.
- Concevoir une interface pratique pour les projets de prototypage.
- Réduire la complexité des connexions dans les projets à base d'ESP32.

### Architecture et principe de conception

La conception repose sur une carte d'adaptation assurant le report des connexions de l'ESP32 vers des points de raccordement accessibles.

L'organisation prévue comprend :

- **Interface ESP32 :** emplacement destiné à recevoir la carte de développement ESP32 DevKitC-32D.
- **Connexions d'entrées/sorties :** report des broches GPIO.
- **Connexions d'alimentation :** accès aux lignes d'alimentation et de masse.
- **Organisation des raccordements :** deux rangées de connexions destinées à faciliter le câblage.
- **Fixation mécanique :** quatre trous de montage prévus dans la conception du PCB.

### Caractéristiques techniques

| Paramètre | Description |
|---|---|
| Type de projet | Conception d'une carte d'adaptation |
| Carte compatible | ESP32 DevKitC-32D |
| Microcontrôleur de la carte principale | ESP32 |
| Logiciel de conception | KiCad |
| Schéma électronique | Conçu |
| Circuit imprimé (PCB) | Conçu et routé |
| Organisation des connexions | Deux rangées |
| Fixation | Quatre trous prévus |
| Application | Facilitation du câblage et du prototypage |

### Documents techniques

Les documents techniques sont prévus dans le répertoire `documents/` :

| Document | Description |
|---|---|
| [Schéma électronique (PDF)](documents/SCHEMATIC%20TERMINAL%20ADAPTER%20FOER%20ESP32.pdf) | Schéma électronique de la carte d'adaptation |
| [Typon du PCB (PDF)](documents/TYPON%20%20TERMINAL%20ADAPTER%20FOER%20ESP32.pdf) | Dessin du circuit imprimé |

### État et limites du projet

| Élément | État |
|---|---|
| Conception du schéma électronique | Réalisée sous KiCad |
| Conception du PCB | Réalisée sous KiCad |
| Routage du circuit imprimé | Réalisé |
| Documentation technique | Préparée |
| Fabrication physique | Non réalisée |
| Assemblage des composants | Non réalisé |
| Essais sur prototype physique | Non réalisés |
| Validation expérimentale | Non réalisée |

> **Important :** ce projet est actuellement au stade de conception numérique. Les documents présentés illustrent le schéma électronique et le typon du circuit imprimé. Ils ne constituent pas la preuve d'une fabrication ou d'un fonctionnement physique de la carte.

---

## 🇬🇧 English

### Overview

Terminal Adapter for ESP32 is a PCB design project intended to simplify access to the connections of an ESP32 DevKitC-32D development board.

The objective is to design an interface that brings the ESP32 connections out to organized connection points arranged in two rows. This layout is intended to simplify the wiring of sensors, electronic modules and other peripherals used in ESP32-based projects.

The electronic schematic and PCB layout were designed using KiCad.

This project is currently at the digital design stage. The board has not yet been physically manufactured.

### Project objectives

- Provide easier access to ESP32 pins.
- Simplify connections to external sensors and peripherals.
- Improve wiring organization in electronic assemblies.
- Design a practical interface for prototyping projects.
- Reduce wiring complexity in ESP32-based applications.

### Architecture and design principle

The design is based on an adapter board that brings the ESP32 connections out to accessible connection points.

The planned organization includes:

- **ESP32 interface:** footprint intended for the ESP32 DevKitC-32D development board.
- **Input/output connections:** breakout of GPIO pins.
- **Power connections:** access to power supply and ground lines.
- **Connection arrangement:** two rows of connection points for easier wiring.
- **Mechanical mounting:** four mounting holes included in the PCB design.

### Technical specifications

| Parameter | Description |
|---|---|
| Project type | Adapter board design |
| Compatible board | ESP32 DevKitC-32D |
| Main board microcontroller | ESP32 |
| Design software | KiCad |
| Electronic schematic | Designed |
| Printed circuit board (PCB) | Designed and routed |
| Connection arrangement | Two rows |
| Mounting | Four planned mounting holes |
| Application | Simplified wiring and prototyping |

### Technical documents

The technical documents are intended to be stored in the `documents/` directory:

| Document | Description |
|---|---|
| [Electronic schematic (PDF)](documents/SCHEMATIC%20TERMINAL%20ADAPTER%20FOER%20ESP32.pdf) | Adapter board electronic schematic |
| [PCB artwork (PDF)](documents/TYPON%20%20TERMINAL%20ADAPTER%20FOER%20ESP32.pdf) | Printed circuit board artwork |

### Project status and limitations

| Item | Status |
|---|---|
| Electronic schematic design | Completed in KiCad |
| PCB design | Completed in KiCad |
| PCB routing | Completed |
| Technical documentation | Prepared |
| Physical manufacturing | Not performed |
| Component assembly | Not performed |
| Physical prototype testing | Not performed |
| Experimental validation | Not performed |

> **Important:** this project is currently at the digital design stage. The documents show the electronic schematic and PCB artwork. They do not demonstrate physical manufacturing or operation of the board.

---

## Contact

**OLI OLI DONALD · OLITECH**  
Cameroon  
Email: [oliolidonald186@gmail.com](mailto:oliolidonald186@gmail.com)

*OLITECH — Electronic design and practical engineering.*
