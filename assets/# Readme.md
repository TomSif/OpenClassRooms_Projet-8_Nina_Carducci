# Projet d'Optimisation SEO et Accessibilité - Nina Carducci

## Objectifs Pédagogiques

Ce projet vise à améliorer le référencement naturel (SEO) et l'accessibilité du site web de Nina Carducci, une photographe professionnelle basée à Bordeaux. Les objectifs pédagogiques incluent :

1. **Compréhension des Fondamentaux du SEO** : Identifier et appliquer les éléments essentiels du référencement naturel et de l'accessibilité web.
2. **Utilisation des Outils d'Audit** : Maîtriser des outils comme Lighthouse et Wave pour analyser la performance, l'accessibilité, et le SEO du site.
3. **Application des Techniques d'Optimisation** : Mettre en œuvre des recommandations pour améliorer la vitesse de chargement, la structure du code, et les métadonnées.
4. **Réalisation de Rapports** : Documenter les résultats avant et après les modifications, en mesurant leur impact sur le SEO et l'accessibilité.
5. **Connaissance en Référencement Local** : Optimiser le référencement local en utilisant des outils comme Schema.org.
6. **Développement d'une Communication Client** : Apprendre à communiquer efficacement avec un client pour comprendre ses besoins et le tenir informé des progrès.

---

## Structure du Projet

### 1. Audit Initial

- **Outils utilisés** : Lighthouse, Wave, Google PageSpeed Insights.
- **Métriques analysées** :
  - Performance (temps de chargement, optimisation des images).
  - Accessibilité (contraste des couleurs, balisage sémantique, attributs ARIA).
  - SEO (métadonnées, structure des titres, données structurées).
- **Résultats initiaux** : Documenter les scores et les problèmes identifiés.

### 2. Optimisations Appliquées

#### SEO

- **Métadonnées** :
  - Ajout de balises `<meta>` descriptives (title, description, keywords).
  - Balises Open Graph et Twitter Card pour les réseaux sociaux.
  - Balise canonique pour éviter le contenu dupliqué.
- **Données Structurées** :
  - Utilisation de JSON-LD pour marquer les informations de contact, les services, et les images.
- **Optimisation des Images** :
  - Utilisation du format WebP.
  - Ajout d'attributs `alt` descriptifs.
  - Implémentation de `srcset` pour le responsive.

#### Accessibilité

- **Balisage Sémantique** :
  - Utilisation de `<header>`, `<main>`, `<footer>`, `<section>`, et `<article>`.
  - Ajout de rôles ARIA (`role="banner"`, `aria-label` pour la navigation).
- **Contraste des Couleurs** :
  - Vérification des ratios de contraste avec Wave.
- **Navigation au Clavier** :
  - Ajout de `focus` styles pour les éléments interactifs.
- **Attributs d'Accessibilité** :
  - `loading="lazy"` pour les images hors écran.
  - `aria-hidden="true"` pour les éléments décoratifs.

#### Performance

- **Optimisation des Ressources** :
  - Minification des fichiers CSS et JS.
  - Chargement différé des scripts (`defer`).
- **Amélioration du Temps de Chargement** :
  - Réduction de la taille des images.
  - Utilisation de CDN pour Bootstrap et jQuery.

### 3. Résultats Post-Optimisation

- **Nouveaux Scores** : Comparaison des scores Lighthouse et Wave avant/après.
- **Impact Mesurable** :
  - Amélioration du temps de chargement.
  - Meilleure indexation par les moteurs de recherche.
  - Conformité accrue aux standards d'accessibilité (WCAG).

---

## Outils et Technologies Utilisés

- **SEO** : Google Search Console, Schema.org, Rich Results Test.
- **Accessibilité** : Wave, axe DevTools.
- **Performance** : Lighthouse, PageSpeed Insights.
- **Développement** : HTML5, CSS3, Bootstrap, JavaScript.

---

## Communication Client

### Étapes Clés

1. **Premier Contact** : Comprendre les besoins et attentes de Nina Carducci.
2. **Présentation des Résultats** : Fournir un rapport clair avec les problèmes identifiés et les solutions proposées.
3. **Feedback et Validation** : Intégrer les retours du client avant finalisation.
4. **Livraison** : Remise du site optimisé avec documentation des modifications.

### Modèle d'Email Client

```plaintext
Objet : Optimisation SEO et Accessibilité - Site Nina Carducci

Bonjour Nina,

Voici un résumé des améliorations apportées à votre site :
1. Optimisation des métadonnées pour un meilleur référencement.
2. Amélioration de l'accessibilité (navigation au clavier, contrastes).
3. Réduction du temps de chargement des pages.

Vous pouvez consulter les résultats détaillés ici [lien vers le rapport].

Cordialement,
[Votre Nom]
```
