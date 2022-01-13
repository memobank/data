# Principaux frais mensuels prélevés par les banques traditionnelles

## Contenu du CSV

Les valeurs contenues dans le CSV sont séparées par des virgules (`,`).

| Colonne                         | Définition                                                                                         |
| ------------------------------- | -------------------------------------------------------------------------------------------------- |
| `banque`                        | Nom de la banque                                                                                   |
| `url_brochure_tarifaire`        | L’URL de la brochure tarifaire sur le site de la banque                                            |
| `commission_mouvement_fixe`     | Commission de mouvement fixe minimum par mois (€)                                                  |
| `commission_mouvement_variable` | Commission de mouvement variable maximum prélevée sur les mouvements sortants (%)                  |
| `virement_sepa_sortant`         | Coût d’un virement SEPA sortant ordinaire effectué en ligne (€)                                    |
| `paiement_prelevement_sepa`     | Coût d’un paiement (sortant) effectué auprès d’un créancier par le biais d’un prélèvement SEPA (€) |
| `ecriture_comptable`            | Montant prélevé sur chaque mouvement (entrant comme sortant) enregistré sur le compte (€)          |
| `tenue_compte`                  | Frais mensuels de tenue de compte (€)                                                              |
| `actualisation_compte`          | Frais mensuels d’actualisation administrative et juridique du compte (€)                           |
| `banque_distance`               | Frais mensuels de banque à distance (€)                                                            |
| `total_frais_fixes`             | `commission_mouvement_fixe` + `tenue_compte` + `actualisation_compte` + `banque_distance`          |

## Sources

Données issues des brochures tarifaires des banques traditionnelles, édition entreprise, pour l’année 2022.

- [Banque Palatine](brochures/2022-tarifs-banque-palatine.pdf)
- [Banque Populaire (Paris)](brochures/2022-tarifs-banque-populaire.pdf)
- [BNP Paribas](brochures/2022-tarifs-bnp.pdf)
- [Caisse d’Épargne](brochures/2022-tarifs-caisse-epargne.pdf)
- [CIC](brochures/2022-tarifs-cic.pdf)
- [Crédit Agricole (Paris)](brochures/2022-tarifs-credit-agricole.pdf)
- [Crédit Coopératif](brochures/2022-tarifs-credit-cooperatif.pdf)
- [Crédit Mutuel](brochures/2022-tarifs-credit-mutuel.pdf)
- [La Banque Postale](brochures/2022-tarifs-la-banque-postale.pdf)
- [Memo Bank](brochures/2022-tarifs-memo-bank.pdf)
- [Société Générale](brochures/2022-tarifs-societe-generale.pdf)
