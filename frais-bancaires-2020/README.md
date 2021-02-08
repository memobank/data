# Principaux frais mensuels prélevés par les banques traditionnelles

Ce dossier contient les données qui ont servi à préparer l’article : [Pourquoi les frais bancaires sont moins prévisibles que les trains suisses](https://memo.bank/magazine/comparaison-frais-bancaires-2020).

## Contenu du CSV

| Colonne                         | Définition                                                                                |
| ------------------------------- | ----------------------------------------------------------------------------------------- |
| `banque`                        | Nom de la banque                                                                          |
| `url_brochure_tarifaire`        | L’URL de la brochure tarifaire sur le site de la banque                                   |
| `commission_mouvement_fixe`     | Commission de mouvement fixe minimum par mois (€)                                         |
| `commission_mouvement_variable` | Commission de mouvement variable maximum prélevée sur les mouvements sortants (%)         |
| `virement_sepa_sortant`         | Coût d’un virement SEPA sortant ordinaire effectué en ligne (€)                           |
| `prelevement_sepa_sortant`      | Coût d’un prélèvement SEPA effectué par un créancier sur le compte de l’entreprise (€)    |
| `ecriture_comptable`            | Montant prélevé sur chaque mouvement (entrant comme sortant) enregistré sur le compte (€) |
| `tenue_compte`                  | Frais mensuels de tenue de compte (€)                                                     |
| `actualisation_compte`          | Frais mensuels d’actualisation administrative et juridique du compte (€)                  |
| `banque_distance`               | Frais mensuels de banque à distance (€)                                                   |
| `total_frais_fixes`             | `commission_mouvement_fixe` + `tenue_compte` + `actualisation_compte` + `banque_distance` |

## Sources

Données issues des brochures tarifaires des banques traditionnelles, édition entreprise, pour l’année 2020.

- [Banque Palatine](brochures/2020-tarifs-banque-palatine.pdf)
- [Banque Populaire (Paris)](brochures/2020-tarifs-banque-populaire.pdf)
- [BNP Paribas](brochures/2020-tarifs-bnp.pdf)
- [Caisse d’Épargne](brochures/2020-tarifs-caisse-epargne.pdf)
- [CIC](brochures/2020-tarifs-cic.pdf)
- [Crédit Agricole (Paris)](brochures/2020-tarifs-credit-agricole.pdf)
- [Crédit Coopératif](brochures/2020-tarifs-credit-cooperatif.pdf)
- [Crédit du Nord](brochures/2020-tarifs-credit-du-nord.pdf)
- [Crédit Mutuel](brochures/2020-tarifs-credit-mutuel.pdf)
- [HSBC](brochures/2020-tarifs-hsbc.pdf)
- [La Banque Postale](brochures/2020-tarifs-la-banque-postale.pdf)
- [LCL](brochures/2020-tarifs-lcl.pdf)
- [Memo Bank](brochures/2020-tarifs-memo-bank.pdf)
- [Société Générale](brochures/2020-tarifs-societe-generale.pdf)
