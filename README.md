# 🎯 Le Juste Prix

Un jeu de devinettes interactif où vous devez deviner un nombre aléatoire entre 0 et 1000. Testez votre intuition et votre logique !

## 🎮 Aperçu du jeu

Le Juste Prix est un jeu classique de devinettes où l'ordinateur génère un nombre aléatoire et vous devez le deviner en un minimum de coups. Le jeu vous guide avec des indices "c'est plus" ou "c'est moins" pour vous aider à trouver le bon nombre.

## ✨ Fonctionnalités

- **Interface intuitive** : Design moderne avec thème sombre
- **Validation en temps réel** : Vérification automatique des entrées
- **Historique des tentatives** : Affichage de tous vos essais précédents
- **Compteur de coups** : Suivi du nombre de tentatives
- **Messages d'aide** : Indications "c'est plus" ou "c'est moins"
- **Fin de partie** : Félicitations et blocage du formulaire à la victoire

## 🎯 Règles du jeu

1. L'ordinateur génère un nombre aléatoire entre 0 et 1000
2. Entrez votre proposition dans le champ de saisie
3. Cliquez sur "Deviner" ou appuyez sur Entrée
4. Suivez les indices :
   - **"C'est plus !"** : Le nombre à trouver est plus grand
   - **"C'est moins !"** : Le nombre à trouver est plus petit
5. Continuez jusqu'à trouver le juste prix !

## 🚀 Installation et utilisation

### Prérequis
- Un navigateur web moderne
- Aucune installation requise

### Lancement
1. Clonez ce dépôt :
   ```bash
   git clone https://github.com/votre-username/le-juste-prix.git
   ```

2. Naviguez dans le dossier :
   ```bash
   cd le-juste-prix
   ```

3. Ouvrez `index.html` dans votre navigateur

## 📁 Structure du projet

```
le-juste-prix/
├── index.html      # Page principale du jeu
├── js.js           # Logique JavaScript du jeu
├── style.css       # Styles CSS
└── README.md       # Documentation
```

## 🛠️ Technologies utilisées

- **HTML5** - Structure de la page
- **CSS3** - Styling et animations
- **JavaScript (ES6)** - Logique du jeu
- **DOM Manipulation** - Interactivité en temps réel

## 🎨 Caractéristiques techniques

### Fonctionnalités JavaScript
- Génération de nombres aléatoires avec `Math.random()`
- Validation des entrées avec `isNaN()`
- Manipulation du DOM en temps réel
- Gestion des événements (`keyup`, `submit`)
- Création dynamique d'éléments HTML

### Design CSS
- **Thème sombre** : Arrière-plan `#232020`
- **Couleurs d'accentuation** : Orange `#ff7315` et `#f39c12`
- **Effets hover** : Transformations et transitions fluides
- **Responsive design** : Adapté à tous les écrans

## 🎯 Améliorations possibles

- [ ] Ajouter des niveaux de difficulté
- [ ] Système de score basé sur le nombre de coups
- [ ] Sauvegarde des meilleurs scores
- [ ] Mode multijoueur
- [ ] Animations plus avancées
- [ ] Son et effets audio
- [ ] Historique des parties

### Interface principale
- Champ de saisie avec validation
- Bouton de soumission stylisé
- Zone d'instructions dynamique

### Pendant le jeu
- Historique des tentatives
- Compteur de coups
- Messages d'aide colorés

## 🤝 Contribution

Les contributions sont les bienvenues ! Pour contribuer :

1. Fork le projet
2. Créez une branche pour votre fonctionnalité (`git checkout -b feature/AmazingFeature`)
3. Committez vos changements (`git commit -m 'Add some AmazingFeature'`)
4. Push vers la branche (`git push origin feature/AmazingFeature`)
5. Ouvrez une Pull Request

## 🎯 Stratégies de jeu

### Méthode dichotomique (optimale)
1. Commencez par 500 (milieu de 0-1000)
2. Divisez toujours l'intervalle restant par 2
3. Trouvez le nombre en maximum 10 coups !

### Méthode intuitive
- Utilisez votre instinct
- Adaptez selon les indices
- Apprenez des tentatives précédentes

## 📧 Contact

- **Auteur** : FOFANA ISSOUF
- **Email** : fofanaissouf179@gmail.com
- **GitHub** :https://github.com/issouf14-DEV

---

🎮 **Amusez-vous bien et que le meilleur gagne !** ⭐

> **Conseil** : La stratégie optimale est la recherche dichotomique - commencez par 500 puis divisez toujours l'intervalle par 2 !
