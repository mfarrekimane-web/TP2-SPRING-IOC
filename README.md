# TP2 : Spring IoC

## Description
Ce projet illustre le principe d'inversion de contrôle (IoC) et l'injection de dépendances avec Spring Framework.

## Technologies utilisées
- Java 17
- Spring Framework 6.1.2
- Maven
- IntelliJ IDEA

## Fonctionnement
Le projet utilise les annotations @Component, @ComponentScan, @Autowired et @Qualifier pour gérer les beans Spring et injecter les dépendances.

## Exécution
Ouvrir le projet dans IntelliJ IDEA, puis exécuter la classe presentation.Presentation2.

## Résultat attendu
Résultat = 300.0 si l'implémentation DaoImpl2 est sélectionnée avec @Qualifier("dao2").
