# Générateur de briefs LinkedIn

Un outil simple et élégant pour générer des briefs de posts LinkedIn à partir de listes JSON personnalisables.

## 🎯 Objectif

Faciliter la création de briefs structurés pour des posts LinkedIn en combinant aléatoirement différents éléments : acteurs, situations, conséquences et déclics.

## ✨ Fonctionnalités

- **Gestion par JSON** : Configure tes listes d'acteurs, situations, conséquences et insights via des tableaux JSON
- **Génération aléatoire** : Génère des combinaisons aléatoires pour trouver des angles intéressants
- **Verrouillage** : Verrouille certains champs pour ne regénérer que les autres
- **Persistance** : Tes listes et verrous sont sauvegardés localement (localStorage)
- **Export/Import** : Exporte tes listes JSON pour les partager ou les sauvegarder
- **Interface moderne** : Design épuré avec accordéons pour une meilleure lisibilité

## 🚀 Utilisation

1. **Ouvre le fichier** : Lance simplement `index.html` dans ton navigateur
2. **Configure tes listes** : Colle tes tableaux JSON dans les champs correspondants
3. **Applique** : Clique sur "Appliquer les JSON"
4. **Génère** : Clique sur "Générer" pour obtenir un brief aléatoire
5. **Affine** : Verrouille les champs que tu veux garder et utilise "Reroll" pour régénérer les autres

## 📝 Format JSON

Chaque liste doit être un tableau JSON valide :

```json
[
  "Premier élément",
  "Deuxième élément",
  "Troisième élément"
]
```

### Exemples de listes

**Acteurs** :
```json
[
  "Artisane papetière",
  "Menuisier / ébéniste",
  "PME industrielle (B2B)",
  "Coach / thérapeute"
]
```

**Situations** :
```json
[
  "Dépend d'une plateforme (Etsy / Leboncoin) pour vendre",
  "A un site en ligne depuis 3 ans, mais zéro appel",
  "Site inutilisable sur mobile"
]
```

**Conséquences** :
```json
[
  "Des prospects vont chez un concurrent plus visible",
  "Perte de crédibilité avant même le premier contact",
  "Moins d'appels, moins de devis, moins de ventes"
]
```

**Déclics / Insights** :
```json
[
  "Le problème n'était pas le design. C'était la clarté + l'accès au contact.",
  "Tant que personne ne se plaint, on croit que tout va bien. En réalité, les gens partent en silence."
]
```

## 🎨 Fonctionnalités avancées

### Verrouillage
Coche la case "verrouiller" sur un champ pour le garder fixe lors des regénérations. Utile pour :
- Fixer un acteur et explorer différentes situations
- Garder une situation et tester différents insights
- Construire progressivement ton brief idéal

### Export
Le bouton "Exporter mes JSON" copie toutes tes listes dans le presse-papiers sous forme d'objet JSON complet, prêt à être sauvegardé ou partagé.

### Reset
Le bouton "Réinitialiser" restaure les exemples par défaut pour repartir de zéro.

## 💾 Stockage

- **Listes** : Sauvegardées automatiquement dans le localStorage après chaque "Appliquer"
- **Verrous** : Sauvegardés automatiquement à chaque changement de case à cocher
- **Persistance** : Tes données restent disponibles même après fermeture du navigateur

## 🛠️ Technologies

- HTML5
- CSS3 (design moderne avec gradients et animations)
- JavaScript vanilla (aucune dépendance)
- localStorage API

## 📦 Installation

Aucune installation nécessaire ! Il suffit d'ouvrir `index.html` dans un navigateur moderne.

## 🎯 Cas d'usage

1. **Brainstorming** : Génère des combinaisons aléatoires pour trouver de nouveaux angles
2. **Variation** : Verrouille un acteur et explore toutes les situations possibles
3. **Structuration** : Utilise le brief généré comme base pour rédiger ton post LinkedIn
4. **Partage** : Exporte tes listes pour les partager avec ton équipe

## 📄 Licence

Libre d'utilisation.
