# 🎵 TheLabo-A · Reconnaissance des intervalles    ©Daniel Mancero Baquerizo CRD d'Évry - 2026

Didacticiel interactif d’entraînement à la reconnaissance auditive des intervalles musicaux.

Ce module fait partie du projet **TheLabo-A**, une plateforme pédagogique consacrée à l’entraînement musical.

---

## 🎯 Objectif pédagogique

Le didacticiel a pour objectif de développer progressivement la capacité à reconnaître un intervalle à l’oreille, indépendamment de la hauteur absolue des notes.

À chaque question, l’élève écoute deux sons et doit identifier l’intervalle entendu.

Le programme fait varier les notes de départ afin de privilégier la reconnaissance de la **distance intervallique** plutôt que la mémorisation d’une succession particulière de notes.

---

## 🎧 Principe du jeu

Une manche comporte **10 questions**.

Pour chaque question :

1. le programme choisit un intervalle ;
2. une hauteur de départ est choisie aléatoirement ;
3. l’intervalle est joué ;
4. l’élève sélectionne la réponse correspondante ;
5. le programme indique immédiatement si la réponse est correcte.

L’intervalle peut être réécouté grâce au bouton :

**🔊 ÉCOUTER / RÉÉCOUTER**

---

## ✅ Bonne réponse

Lorsqu’une réponse est correcte :

- la bonne réponse apparaît en vert ;
- le nom de l’intervalle est affiché ;
- le nombre de demi-tons est indiqué ;
- les deux notes sont indiquées ;
- la question suivante apparaît automatiquement.

---

## ❌ Mauvaise réponse

En cas d’erreur :

- la réponse choisie apparaît en rouge ;
- la bonne réponse apparaît en vert ;
- le nom correct de l’intervalle est indiqué ;
- l’élève peut réécouter l’intervalle ;
- la progression est volontairement interrompue.

L’élève utilise ensuite le bouton **QUESTION SUIVANTE** lorsqu’il souhaite continuer.

Ce fonctionnement permet de prendre le temps d’écouter et d’observer la correction avant de passer à un nouvel intervalle.

---

# 📚 Niveaux

## Niveau 1 · Repères

Introduction à quelques intervalles auditivement bien différenciés :

- seconde majeure ;
- tierce majeure ;
- quarte juste ;
- quinte juste ;
- octave juste.

Ce niveau permet de construire les premiers repères auditifs.

---

## Niveau 2 · Majeur / mineur

Introduction des distinctions entre intervalles majeurs et mineurs :

- seconde mineure ;
- seconde majeure ;
- tierce mineure ;
- tierce majeure ;
- quarte juste ;
- quinte juste ;
- sixte mineure ;
- sixte majeure ;
- octave juste.

---

## Niveau 3 · Chromatique complet

Travail de l’ensemble des intervalles contenus dans l’octave :

- seconde mineure ;
- seconde majeure ;
- tierce mineure ;
- tierce majeure ;
- quarte juste ;
- triton ;
- quinte juste ;
- sixte mineure ;
- sixte majeure ;
- septième mineure ;
- septième majeure ;
- octave juste.

---

## Niveau 4 · Expert

Le niveau expert utilise également l’ensemble des intervalles chromatiques et pourra servir de base à des variantes plus exigeantes du didacticiel.

---

# 🎶 Modes d’écoute

Le jeu propose quatre modes.

### ↑ Ascendant

La note grave est entendue en premier, puis la note aiguë.

### ↓ Descendant

La note aiguë est entendue en premier, puis la note grave.

### ♫ Harmonique

Les deux notes sont jouées simultanément.

### ⇅ Mixte

Le programme alterne aléatoirement entre les modes ascendant, descendant et harmonique.

---

# 🔊 Son

Le son est généré directement dans le navigateur avec la **Web Audio API**.

Aucun fichier sonore externe n’est nécessaire.

Les hauteurs sont calculées à partir de notes MIDI puis converties en fréquences.

Par exemple :

- La4 = MIDI 69 ;
- La4 = 440 Hz.

La tessiture du jeu est volontairement placée dans un registre central afin que les intervalles restent facilement perceptibles.

Un réglage de **volume général** permet à l’utilisateur d’adapter le niveau sonore à son appareil et à ses conditions d’écoute.

> Pour un travail auditif précis, l’utilisation d’un casque ou d’écouteurs de bonne qualité peut être préférable aux haut-parleurs intégrés d’un téléphone ou d’un ordinateur portable.

---

# 🎼 Feedback pédagogique

Après une réponse, le jeu indique :

- le nom de l’intervalle ;
- le nombre de demi-tons ;
- les noms des deux notes ;
- une représentation visuelle simplifiée ;
- un bouton permettant de réécouter l’intervalle.

L’information visuelle apparaît **après la réponse**, afin que l’exercice reste d’abord un exercice de reconnaissance auditive.

---
