# Principaux frais mensuels prélevés par les banques traditionnelles

Ce dossier contient les données qui ont servi à préparer le [tweet que nous consacrons chaque année](https://twitter.com/memobank/status/1620458155116486656) à l’évolution des frais fixes prélevés par les banques traditionnelles. Les frais bancaires fixes correspondent aux frais que toutes les entreprises sont censées payer chaque mois, quel que soit l’usage qu’elles font de leur compte courant.

## Contenu du CSV

Les valeurs contenues dans le CSV sont séparées par des virgules (`,`).

| Colonne | Définition |
| --- | --- |
| `banque` | Nom de la banque |
| `url_brochure_tarifaire` | L’URL de la brochure tarifaire sur le site de la banque |
| `commission_mouvement_fixe` | Commission de mouvement fixe minimum par mois (€) |
| `commission_mouvement_variable` | Commission de mouvement variable maximum prélevée sur les mouvements sortants (%) |
| `virement_sepa_sortant` | Coût d’un virement SEPA sortant ordinaire effectué en ligne (€) |
| `paiement_prelevement_sepa` | Coût d’un paiement (sortant) effectué auprès d’un créancier par le biais d’un prélèvement SEPA (€) |
| `ecriture_comptable` | Montant prélevé sur chaque mouvement (entrant comme sortant) enregistré sur le compte (€) |
| `tenue_compte` | Frais mensuels de tenue de compte (€) |
| `actualisation_compte` | Frais mensuels d’actualisation administrative et juridique du compte (€) |
| `banque_distance` | Frais mensuels de banque à distance (€) |
| `total_frais_fixes` | `commission_mouvement_fixe` + `tenue_compte` + `actualisation_compte` + `banque_distance` |

## Sources

Données issues des brochures tarifaires des banques traditionnelles, édition entreprise, pour l’année 2023.

- [Banque Palatine](brochures/2023-tarifs-banque-palatine.pdf)
- [Banque Populaire (Paris)](brochures/2023-tarifs-banque-populaire.pdf)
- [BNP Paribas](brochures/2023-tarifs-bnp.pdf)
- [BRED](brochures/2023-tarifs-bred.pdf)
- [Caisse d’Épargne (Île-de-France)](brochures/2023-tarifs-caisse-epargne.pdf)
- [CIC](brochures/2023-tarifs-cic.pdf)
- [Crédit Coopératif](brochures/2023-tarifs-credit-cooperatif.pdf)
- [Crédit Mutuel (Île-de-France)](brochures/2023-tarifs-credit-mutuel.pdf)
- [HSBC](brochures/2023-tarifs-hsbc.pdf)
- [La Banque Postale](brochures/2023-tarifs-la-banque-postale.pdf)
- [Memo Bank](brochures/2023-tarifs-memo-bank.pdf)
- [Société Générale](brochures/2023-tarifs-societe-generale.pdf)
