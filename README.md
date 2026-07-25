# analyse-bivariée-pratique-sportive-licenciée-et-niveau-de-vie-par-departement
Étude d'une relation entre le taux de pratique sportive licenciée (tous sports confondus) et le niveau de vie médian, au niveau départemental, en France

## Objectif
Étudier la relation entre le taux de pratique sportive et le niveau de vie médian, à l'echelle  départementale en France. Le projet met en œuvre une analyse bivariée quantitatif × quantitatif : nuage de points, covariance, corrélation de Pearson, et régression linéaire simple (MCO).
 
## Sources des données
- **INJEP / MEDES** — Recensement des licences et clubs sportifs 2024, ventilé par département (résidence).
- **INSEE-Filosofi** — Niveau de vie annuel médian par département, 2023.
Les deux sources ont été fusionnées par code département (RECHERCHEV).

## Méthode
- Nuage de points (revenu médian en X, taux de pratique en Y)
- Covariance
- Coefficient de corrélation de Pearson
- Régression linéaire simple
Outil utilisé : Excel (formules natives).
 
## Résultats clés
| Indicateur | Valeur |
|---|---|
| Corrélation (Pearson) | 0,121 |
| Coefficient de détermination (R²) | 0,015 |
| Pente | +2,2 points de taux de pratique pour +10 000 € de revenu médian |
| Ordonnée | 0,202 |
 
La relation entre revenu médian départemental et taux de pratique sportive licenciée globale est **très faible** (R² = 1,5 %) : le revenu n'explique quasiment pas les écarts de pratique sportive licenciée entre départements.
 
## Interprétation
Le taux de pratique agrège plus de 100 fédérations aux profils socio-économiques très différents. Cette agrégation dilue peut être l'effet du revenu sur les pratiques coûteuses, noyé par le volume des pratiques peu coûteuses pratiquées indépendamment du niveau de vie local. Une analyse fédération par fédération donnerait probablement des corrélations plus marquées.
 
**Limite méthodologique** : l'analyse est menée sur données agrégées au niveau départemental (corrélation écologique). Elle ne permet pas de conclure sur le comportement des individus.
 
## Contenu du dépôt
- `Projet 2_Analyse bivariée_quantixquanti.xlsx` : fichier Excel complet (données brutes, fusion, calculs, graphiques)

 
