# Maquette (faisabilité)

<!--
https://tim-montmorency.com/582523-gestion/#/contenus/3_planification/

# Maquette

## Importance de la maquette dans les projets multimédias
Une maquette permet de déterminer si un projet est réalisable sur les plans technique, économique et opérationnel. Elle aide à identifier les obstacles potentiels et à planifier les ressources nécessaires. Dans le contexte des technologies interactives, où les innovations sont rapides et les attentes des utilisateur·rice·s élevées, cette démarche devient encore plus critique.

## Étapes clés de la maquette

### 1. Ascpect technique
- **Analyse des exigences techniques** : Définir les spécifications techniques du projet, y compris les logiciels, le matériel, les interfaces utilisateur et les protocoles de communication.  
- **Compatibilité du système** : Vérifier si les nouvelles technologies interactives sont compatibles avec les systèmes existants.  
- **Tests** : Effectuer des tests pour valider les fonctionnalités et l'interactivité.  

### 2. Ascpect économique
- **Estimation des coûts** : Calculer les coûts associés à l'acquisition de matériel, de logiciels, au développement et à la maintenance.  
- **Analyse du retour sur investissement (ROI)** : Évaluer les bénéfices potentiels par rapport aux coûts engagés.  
- **Options de financement** : Explorer les subventions, les partenariats ou les modèles économiques alternatifs.  

### 3. LES RÈGLES ET LE SYSTÈME 

```mermaid
graph LR
    Règles Système
    Système Expérience
```

1. **Les règles sont les briques de base.**  
2. **Le système applique les règles.**  
3. **L’expérience est la perspective du joueur.**  

### 4. Asect temporelle
- **Planification du projet** : Établir un calendrier réaliste en tenant compte des délais de développement, de test et de déploiement.  
- **Gestion des risques** : Identifier les risques potentiels qui pourraient retarder le projet et prévoir des plans d'urgence.  

### 5. Aspect légal et éthique
- **Conformité réglementaire** : S'assurer que le projet respecte les lois en vigueur, notamment en matière de propriété intellectuelle et de protection des données.  
- **Accessibilité** : Garantir que l'installation interactive est accessible à tous les utilisateur·rice·s, y compris les personnes en situation de handicap.  

-->

## Scénarisation de l'interactivité
 
#### Scène 1
 
| Verbe action | Condition de déclenchement | Effet visuel | Effet sonore | Effet interactif |
|--------------|----------------------------|--------------|--------------|------------------|
| **Toucher** | Le visiteur touche la toile avec sa main | Une étoile apparaît au contact de la toile, créant un effet de scintillement | Une note discrète est émise | L’installation capte la position du toucher et projette l'interaction en une étoile lumineuse dans la projection |
 
#### Scène 2
 
| Verbe action | Condition de déclenchement | Effet visuel | Effet sonore | Effet interactif |
|--------------|----------------------------|--------------|--------------|------------------|
| **Toucher** | Un second visiteur touche la toile | Une nouvelle étoile apparaît et se connecte visuellement à l’étoile précédente par un filament de lumière | Un son harmonique s’élève, un peu plus riche et en harmonie avec le premier, symbolisant la connexion | Le système reconnaît la connexion entre les étoiles et renforce la présence de la constellation |
 
#### Scène 3
 
| Verbe action | Condition de déclenchement | Effet visuel | Effet sonore | Effet interactif |
|--------------|----------------------------|--------------|--------------|------------------|
| **Inactivité** | Absence d'interaction avec la toile pendant un certain moment | Dépendamment de la densité collective, les étoiles commencent à s’éteindre lentement | Le son de l’espace devient plus distant et se calme | Le système détecte l'absence d'interaction et prépare la disparition des étoiles |

## Équipements requis
#### Audio
- 2 haut-parleurs actifs de 4"
- 2 fils XLR 3 conducteurs de 15'
- Carte de son + adapteur powerCON
 
#### Vidéo
- 2 projecteurs Epson PowerLite 990U
- 2 kinects
- 3 cables HDMI
 
#### Lumière
- 2 lumières LED RGBAW DMX
- 2 fils XLR 3 conducteurs de 20'
- 1 Interface DMX Via XLR

#### Électricité
- 2 extensions
 
#### Réseau
- 3 cables ethernet
- 2 transmetteurs et 2 récepteurs (pour projection)
#### Ordinateurs
- 1 ordinateur portable (avec cable d'alimentation)

## Logiciels Requis
#### Environnement de programmation
- Touch Designer (Logique, ensemble du projet)
#### Design graphique/Effets visuels
- After Effects (Éléments pré-prod au besoin)
- Photoshop (Éléments pré-prod au besoin)
#### Gestion de l'éclairage
- QLC+ (Éclairage)
#### Audio
- FL Studio (Composition sonore)
- Synthétiseurs VST (WaveTable)

## Synoptique
![Plan de branchements](synoptique.svg)

## Plan d'implémentation
![Planification de l'espace - perspective 2D](2d_plan.webp)
![Planification de l'espace - perspective 3D](3d_plan1.webp)
![Planification de l'espace - perspective 3D](3d_plan2.webp)
![planification de l'espace - perspective 3D](3d_plan3.webp)

## Budget estimé

| Objet| Descritpion | Prix | URL/Provenance |
| ------ | ------ | ------ | ------ |
| Toile spandex | Toile en spandex qui sera l'élément principal de l'intéraction | 29$/0.9m | [Amazon](https://www.amazon.ca/Nylon-Spandex-Fabric-Yard-Activewear/dp/B0FKBBH6LN)|
| Bois traité | Pour construire le cadre de la toile | ~5$/p2 | [Rona](https://www.rona.ca/fr/produit/1-po-x-6-po-x-8-pi-bois-traite-brun-b4f-761-62892-84895013) |
| Peinture | Peinture pour peinturer la structure qui servira de cadre à la toile | 35$/950ml | [HomeDepot](https://www.homedepot.ca/produit/rust-oleum-painter-s-touch-peinture-multi-usages-en-noir-mat-946-ml/1000155179) |
| Pinceau | Pour peinturer la structure | ~4$/pinceau   | [HomeDepot](https://www.homedepot.ca/produit/hdg-pinceau-a-peinture-a-copeaux-plats-de-2-pouces-50-8-mm-de-largeur-paquet-de-1-/1000738776) |
|  |  |  | |
| Total | ~100$ |