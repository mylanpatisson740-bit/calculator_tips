# Calculator Tips 💵

Application Android développée en **Kotlin** avec **Jetpack Compose**, qui calcule le montant du pourboire à ajouter à une addition.

## Fonctionnalités

- Saisie du montant de l'addition
- Saisie du pourcentage de pourboire souhaité
- Option pour arrondir le pourboire au dollar supérieur (`Switch`)
- Calcul automatique et affichage du pourboire formaté en devise locale (ex : `$10.00`)

## Technologies utilisées

- **Kotlin**
- **Jetpack Compose** (`TextField`, `Switch`, `Row`, `Column`)
- **Material 3**
- `NumberFormat.getCurrencyInstance()` pour le formatage monétaire

## Prérequis

- Android Studio
- SDK Android : min **24**, target/compile **35**

## Installation

1. Cloner le dépôt :
   ```bash
   git clone https://github.com/mylanpatisson740-bit/calculator_tips.git
   ```
2. Ouvrir le projet dans Android Studio
3. Lancer l'application sur un émulateur ou un appareil physique

## Contexte

Projet réalisé à partir du codelab **Android Basics with Compose** (Tip Time), complété et personnalisé pour pratiquer la gestion d'état et les champs de saisie en Compose.

## Auteur

Mylan Patisson — [GitHub](https://github.com/mylanpatisson740-bit)
