# Répartition des cotes de crédit attribuées par la Banque de France

Ce dossier contient une partie des données qui ont servi à préparer l’article : [Ce que l’épidémie de Covid change dans le crédit aux entreprises](https://memo.bank/magazine/covid-change-credit-entreprises/).

## Contenu du CSV

Les valeurs contenues dans le CSV sont séparées par des virgules (`,`).

| Colonne           | Définition                                                                                                      |
| ----------------- | --------------------------------------------------------------------------------------------------------------- |
| `annee`           | Année de la campagne de cotation                                                                                |
| `3++`             | Nombre d’entreprises ayant reçu une cote de crédit de 3++ (excellente)                                          |
| `3+`              | Nombre d’entreprises ayant reçu une cote de crédit de 3+ (très forte)                                           |
| `3`               | Nombre d’entreprises ayant reçu une cote de crédit de 3 (forte)                                                 |
| `4+`              | Nombre d’entreprises ayant reçu une cote de crédit de 4+ (assez forte)                                          |
| `4`               | Nombre d’entreprises ayant reçu une cote de crédit de 4 (correcte)                                              |
| `5+`              | Nombre d’entreprises ayant reçu une cote de crédit de 5+ (assez faible)                                         |
| `5`               | Nombre d’entreprises ayant reçu une cote de crédit de 5 (faible)                                                |
| `6`               | Nombre d’entreprises ayant reçu une cote de crédit de 6 (très faible)                                           |
| `7`               | Nombre d’entreprises ayant reçu une cote de crédit de 7 (au moins un incident de paiement)                      |
| `8`               | Nombre d’entreprises ayant reçu une cote de crédit de 8 (menacée)                                               |
| `9`               | Nombre d’entreprises ayant reçu une cote de crédit de 3++ (compromise)                                          |
| `total_cotations` | Nombre total de cotations (entre 3++ et 9) attribuées par la Banque de France au 31 décembre de l’année étudiée |

## Sources

Données sur la répartition des entreprises par [cote de crédit](https://entreprises.banque-france.fr/cotation-des-entreprises/comprendre-la-cotation-banque-de-france/comprendre-la-cote-de-credit) issues de la [page de présentation de la base de données FIBEN](https://www.fiben.fr/presentation/lessentiel-de-fiben) (Banque de France).

Pour les années précédentes, se reporter aux versions archivées de la page FIBEN :

- [2020](https://entreprises.banque-france.fr/sites/default/files/media/2021/01/21/fiben_cotation_chiffres_cles.pdf)
- [2018](https://web.archive.org/web/20200422083116/https://www.fiben.fr/presentation/lessentiel-de-fiben)
- [2019](https://www.fiben.fr/sites/bdf_fiben/files/medias/fiben_2019.png)
- [2017](https://web.archive.org/web/20180830224931/https://www.fiben.fr/presentation/lessentiel-de-fiben)
