# Tip Time

Application Android de calcul de pourboire, faite avec Kotlin et Jetpack Compose.

## Fonctionnement

L'utilisateur saisit le montant de la facture, et l'application affiche automatiquement un pourboire de 15 %.

## Concepts utilisés

- **État** avec `mutableStateOf` et `remember`
- **Recomposition** automatique de l'interface
- **Hissage d'état** : 
`EditNumberField` est sans état, 
`TipTimeLayout` possède l'état

## Lancer le projet

1. Ouvrir le projet dans Android Studio
2. Attendre la synchronisation Gradle
3. Lancer sur un émulateur ou un appareil (Run ▶)
