# Arènes Mystiques

Bienvenue dans **Arènes Mystiques**, un jeu de programmation où vous incarnez des héros issus d'un univers fantasy pour affronter d'autres joueurs dans des combats stratégiques. Le projet est à la fois ludique et éducatif, conçu pour permettre aux débutants en Ruby de s'améliorer tout en s'amusant.

---

## 🎮 Concept
Dans **Arènes Mystiques**, vous choisissez un héros (mage, guerrier, rôdeur, etc.), écrivez des scripts Ruby pour définir ses actions, et le faites combattre dans des arènes magiques.

- **Créez votre héros** : Choisissez une classe, personnalisez ses compétences et équipez-le.
- **Codez ses stratégies** : Décidez comment il attaque, se défend ou utilise ses pouvoirs.
- **Regardez le combat** : Les affrontements se déroulent automatiquement, basés sur vos scripts et les règles de l'arène.

---

## 🔧 Installation

### Prérequis
- Ruby 3.0 ou supérieur
- Bundler pour gérer les dépendances

### Guide d'installation
1. Clonez ce dépôt :
   ```bash
   git clone https://github.com/bu7ch/Mystic_Arena.git
   cd Mystic_Arena
   ```

2. Installez les dépendances :
   ```bash
   bundle install
   ```

3. Lancez le serveur localement :
   ```bash
   ruby app.rb
   ```

4. Ouvrez votre navigateur à l'adresse [http://localhost:4567](http://localhost:4567) pour commencer.

---

## 🔬 Fonctionnalités

### Héros et Classes
- **Mage** : Spécialiste des sorts destructeurs, mais fragile.
- **Guerrier** : Robuste, avec des attaques physiques puissantes.
- **Rôdeur** : Agile et précis, excellent en esquive.

Chaque classe a des statistiques uniques :
- Points de vie
- Attaque
- Défense
- Mana
- Vitesse

### Arènes
- **Forêt enchantée** : Bonus de régénération de mana.
- **Volcan** : Dégâts passifs à chaque tour.
- **Château hanté** : Chances accrues de rater une attaque.

### Combats
- Programme les actions de ton héros :
  ```ruby
  if mana > 20
    "Lancer boule de feu"
  else
    "Attaque basique"
  end
  ```
- Regarde les résultats et améliore ta stratégie !

### Progression
- Gagne de l'expérience et des récompenses pour améliorer ton héros.
- Débloque de nouvelles compétences et équipements.

---

## 🔄 Comment contribuer ?

### 1. Forkez ce dépôt
Cliquez sur le bouton **Fork** en haut de cette page.

### 2. Clonez votre fork
```bash
git clone https://github.com/bu7ch/Mystic_Arena.git
cd Mystic_Arena
```

### 3. Créez une branche pour votre contribution
```bash
git checkout -b ma-nouvelle-fonctionnalite
```

### 4. Soumettez votre modification
- Faites vos changements et ajoutez un commit :
  ```bash
  git add .
  git commit -m "Ajout d'une nouvelle fonctionnalité"
  ```
- Poussez votre branche :
  ```bash
  git push origin ma-nouvelle-fonctionnalite
  ```
- Ouvrez une Pull Request sur GitHub.

---

## 🌐 Ressources supplémentaires

### Pour débutants en Ruby
- [Documentation officielle de Ruby](https://www.ruby-lang.org/fr/documentation/)
- [Tutoriel Ruby pour débutants](https://www.rubyguides.com/ruby-tutorial/)

### Communauté
- Rejoignez les discussions et posez vos questions dans l'onglet **Discussions** du projet.

---

## 🏆 Licences
Ce projet est sous licence [MIT](LICENSE). Vous êtes libre de l'utiliser, le modifier, et le partager.

---

Prêts à plonger dans l'aventure ? Installez **Arènes Mystiques** et commencez votre ascension vers la gloire !

