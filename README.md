# DEBT — Dossier d'exécution BT d'un atelier d'usinage

Projet personnel mené seul par Ichola BOLARINWA, étudiant ingénieur à l'ESIGELEC, dominante Énergie et Développement Durable.

## Objet

Produire, comme le ferait un bureau d'études électricité, le dossier d'exécution de l'installation basse tension d'un atelier d'usinage de PME implanté dans l'agglomération de Rouen : raccordement au réseau public basse tension (segment C4, 36 à 250 kVA), schéma de liaison à la terre TT.

## Nature du projet

Étude de cas fictive. Le site, l'entreprise et le programme de machines sont inventés ; chaque donnée technique provient d'une source réelle citée (fiche constructeur, guide technique, texte réglementaire). Aucun client réel n'est impliqué. Le dossier n'a été vérifié par aucun organisme de contrôle.

## Méthode

Chaque grandeur est calculée à la main, puis vérifiée sous XLPro4 Calcul 400 (Legrand). Les écarts entre calcul manuel et logiciel sont expliqués. Chaque hypothèse de dimensionnement est écrite et justifiée dans le cahier des charges.

## Livrables

| N° | Livrable | Outil | Dossier | État |
|---|---|---|---|---|
| 00 | Cahier des charges | Claude Docs, export PDF | `00_CahierDesCharges` | Terminé (v1.0) |
| 01 | Bilan de puissance | Excel | `01_BilanPuissance` | À faire |
| 02 | Architecture de distribution | Excel, texte | `02_Architecture` | À faire |
| 03 | Plan de masse et d'implantation | AutoCAD | `03_PlanImplantation` | À faire |
| 04 | Schéma unifilaire | QElectroTech | `04_SchemaUnifilaire` | À faire |
| 05 | Note de calcul manuelle | Excel | `05_NoteCalculManuelle` | À faire |
| 06 | Note de calcul logicielle | XLPro4 Calcul 400 | `06_NoteCalculLogicielle` | À faire |
| 07 | Nomenclature chiffrée | Excel | `07_Nomenclature` | À faire |
| 08 | Synthèse | Texte, export PDF | `08_Synthese` | À faire |

## Avancement

| Jalon | Résultat attendu | État |
|---|---|---|
| J1 | Hypothèses de base validées, cahier des charges v1.0 | Terminé |
| J2 | Machines choisies, bilan de puissance | À faire |
| J3 | Architecture, plan d'implantation, premier schéma unifilaire | À faire |
| J4 | Note de calcul manuelle complète | À faire |
| J5 | Vérification sous XLPro4 Calcul et analyse des écarts | À faire |
| J6 | Nomenclature chiffrée, synthèse, dossier final | À faire |

## Nommage des fichiers

`DEBT_[NumLivrable]_[Nom]_v[X].[ext]` — exemple : `DEBT_04_SchemaUnifilaire_v2.qet`

## Sources

Voir `SOURCES.md`. Les documents de référence ne sont pas redistribués dans ce dépôt : ils sont protégés par le droit d'auteur de leurs éditeurs.

## Projets liés

Ce dossier est le premier de trois projets. L'avant-projet photovoltaïque (APV) étudiera une centrale en toiture du même bâtiment ; l'outil d'analyse de performance photovoltaïque (MPV) viendra ensuite.