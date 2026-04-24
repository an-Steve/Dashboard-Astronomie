#  Explorateur d'Habitabilité Exoplanétaire

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?logo=chart.js&logoColor=white)](https://www.chartjs.org/)

<img width="1911" height="566" alt="image" src="https://github.com/user-attachments/assets/ad06513d-bf9d-4d36-ac48-acb718b745c7" />


> Un tableau de bord interactif comparant les exoplanètes potentiellement habitables avec les paramètres de référence de la Terre.

![Aperçu du tableau de bord](https://an-steve.github.io/Dashboard-Astronomie/)

##  Fonctionnalités

- **Comparaison Terre / Exoplanètes** : Visualisation des paramètres clés (oxygène, eau, gravité, température, indice ESI)
- **Analyse graphique complète** : 6 graphiques interactifs (corrélation, radar, histogramme, scatter plots)
- **Système Solaire** : Données réelles des planètes de notre système avec valeurs scientifiques
- **Surlignage intelligent** : La planète la plus similaire à la Terre est mise en évidence en violet
- **Interface sombre** : Design moderne adapté à la visualisation de données astrophysiques

##  Paramètres de référence (Terre)

| Paramètre | Valeur |
|-----------|--------|
| Température moyenne | 15°C |
| Eau de surface | 71% |
| Oxygène atmosphérique | 21% |
| Gravité | 1,00 g |
| Indice ESI | 1,00 (maximum) |

##  Exoplanètes incluses

| Nom | Distance (al) | ESI |
|-----|---------------|-----|
| Teegarden's Star b | 12,5 | 0,95 |
| TOI-700 d | 101 | 0,93 |
| TRAPPIST-1 e | 39 | 0,85 |
| Luyten b | 12,2 | 0,84 |
| Kepler-442 b | 1206 | 0,83 |
| Proxima Centauri b | 4,2 | 0,80 |
| Ross 128 b | 11 | 0,74 |

##  Système Solaire inclus

- Mercure, Vénus, Terre, Mars, Jupiter, Saturne, Uranus, Neptune
- Données scientifiques NASA/JPL (gravité, température, composition atmosphérique)

##  Graphiques disponibles

1. **Corrélation Oxygène / Eau** (diagramme à bulles)
2. **Comparaison ESI** (graphique à barres avec ligne de référence Terre)
3. **Diagramme radar** (critères d'habitabilité normalisés)
4. **Distribution de l'eau** (histogramme interactif)
5. **Gravité vs Température** (scatter plot)
6. **Distance vs ESI** (échelle logarithmique)

##  Technologies utilisées

- **HTML5** : Structure sémantique
- **CSS3** : Design sombre, grilles responsives, animations
- **JavaScript (ES6)** : Manipulation du DOM, logique métier
- **Chart.js** : Visualisation de données interactive
- **Font Awesome 6** : Icônes vectorielles

##  Installation et utilisation

### Méthode 1 : Directe (recommandée)

1. Téléchargez le fichier `index.html`
2. Ouvrez-le dans votre navigateur web (Chrome, Firefox, Edge, Safari)

### Méthode 2 : Avec un serveur local

```bash
# Clonez le dépôt
git clone https://github.com/votre-username/exoplanet-habitability.git

# Accédez au dossier
cd exoplanet-habitability

# Lancez un serveur local (Python 3)
python -m http.server 8080

# Ouvrez http://localhost:8080 dans votre navigateur

```
##  Sources des données

| Source | Description |
|--------|-------------|
| NASA Exoplanet Archive | Base de données d'exoplanètes confirmées |
| PHL - Planetary Habitability Laboratory | Indices ESI et classifications d'habitabilité |
| NASA Planetary Fact Sheets | Données du Système Solaire |
| GISS - NASA Goddard Institute | Paramètres terrestres de référence |

### Références scientifiques par exoplanète

- **Teegarden's Star b** : Zechmeister et al. (2019)
- **TOI-700 d** : Gilbert et al. (2020)
- **TRAPPIST-1 e** : Gillon et al. (2017)
- **Luyten b** : Astudillo-Defru et al. (2017)
- **Kepler-442 b** : Torres et al. (2015)
- **Proxima Centauri b** : Anglada-Escudé et al. (2016)
- **Ross 128 b** : Bonfils et al. (2018)

##  Auteur

**ANTON NELCON Steve**

##  Licence

Ce projet est sous licence MIT. Voir le fichier `LICENSE` pour plus d'informations.
