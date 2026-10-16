# Dossier de relecture V1 / V2 — fiches patients

Date : 16 octobre 2026.

## État du travail

22 fiches et livrets ont une V2 de travail. L’accueil et l’affiche sont également identifiés comme brouillons. Les V1 restent publiées ; aucune V2 n’est fusionnée sur la branche de publication.

La V1 de référence est le commit `15022fc61bdeec100b287e596692af668d800934`, après l’ajout du Dr Robin Arvieu. La branche de travail est `v2-fiches-patients`.

## Comment consulter et comparer

- Ouvrir `Fiches_patients_V1_V2.html` dans un navigateur : catalogue autonome, choix de la fiche, boutons V1, V2, comparaison et changements.
- `V1/` : copie de référence des pages HTML, feuille de style et logo.
- `V2/` : pages HTML révisées, avec la même arborescence.
- `TEXTES_V1/` et `TEXTES_V2/` : extractions du texte pour la lecture par Claude.
- `DIFFS/` : différences textuelles par fiche.
- `RELECTURE/` : décisions restant à valider et motifs des changements par fiche.
- `MANIFESTE.json` : empreintes des fichiers de référence et des V2.

Les copies de lecture retirent le chatbot externe ; elles ne constituent pas des sites patients publiés. Le catalogue permet également de télécharger chaque fiche HTML autonome avec son logo et son style intégrés.

## Principes de rédaction

Conserver le logo, la feuille de style, les chapitres et les tableaux. Expliquer simplement les bénéfices recherchés, les alternatives et les risques. Une information rassurante doit contextualiser sans minimiser un risque pertinent. Ne pas promettre une technique, l’absence de douleur, une récupération complète ou un délai garanti.

Les signatures de consentement ont été remplacées par une section d’échange : cette modification est une proposition de V2 à valider dans l’organisation documentaire de l’équipe. Les sources de travail sont regroupées ci-dessous plutôt que présentées comme une validation scientifique exhaustive de chaque phrase.

## Pratique confirmée par le Dr Jameson — hernie discale simple

- Fiche générale regroupant les techniques, avec complément spécifique à l’endoscopie.
- Possibilité d’adapter l’endoscopie vers un abord mini-invasif trans-tubulaire sous loupes ou microscope.
- Sortie habituellement le jour même ou le lendemain, plus rarement le surlendemain, selon douleurs et saignement peropératoire.
- Objectif de libération du nerf et de soulagement surtout de la douleur dans la jambe ; récupération sensitive ou motrice variable ; le disque n’est pas remis à neuf.
- Lever habituellement le jour même ; marche fractionnée dans la journée, au moins 10 minutes par heure, idéalement 15 minutes, selon tolérance.
- Rééducation généralement entre S2 et S4.

Ces consignes ne sont pas généralisées aux arthrodèses, prothèses, interventions cervicales ou sacro-iliaques. Les calendriers restants sont des repères de brouillon à confirmer.

## Travail demandé à Claude pour préparer une V3

Comparer V1 et V2 fiche par fiche. Vérifier les changements de sens, les informations manquantes, les incohérences entre tableaux, FAQ et texte. Proposer une V3 en conservant la structure et un ton calme, précis et non promotionnel. Ne pas supprimer un risque pertinent pour rendre le texte plus rassurant. Distinguer les améliorations rédactionnelles des décisions médicales nécessitant l’arbitrage du Dr Jameson.

Pour chaque chiffre, protocole ou recommandation, vérifier la source, sa population et sa pertinence pour l’intervention. Ne pas inventer de pourcentage ni de consigne locale. Un risque rare ne signifie pas un risque nul. Les informations de financement et de droit social dépendent du dispositif et du régime ; ne pas confondre indication clinique et remboursement.

Les balises noindex de la branche V2 sont volontaires pour les brouillons. Avant une publication V3 sur rachis.paris, réviser les URL canoniques, l’indexation, les liens et les données structurées. L’existence d’une FAQ ne garantit pas un affichage particulier par Google.

## Sources de travail consultées

- [SFCR — fiches d’information des patients](https://www.sfcr.fr/espace-patients/fiches-informations)
- [HAS — information de la personne sur son état de santé](https://www.has-sante.fr/jcms/c_1261551/delivrance-de-l-information-a-la-personne-sur-son-etat-de-sante)
- [ANSM — RCP Hydrocortancyl, mise à jour du 22 avril 2025](https://agence-prd.ansm.sante.fr/php/ecodex/rcp/R0432726.htm)
- [SFAR — prévention thromboembolique, recommandations 2024](https://sfar.org/prevention-de-la-maladie-thromboembolique-veineuse-peri-operatoire/)
- [HAS — activité physique et lombalgie commune chronique, 2024](https://www.has-sante.fr/jcms/p_3506163/fr/fiche-prescription-d-activite-physique-lombalgie-commune-chronique)
- [HAS — évaluation SpineJack, 23 juillet 2024](https://www.has-sante.fr/upload/docs/evamed/CNEDIMTS-7463_SPINEJACK_23%20juillet%202024_7463_avis.pdf)
- [NICE — dénervation par radiofréquence et bloc diagnostique, NG59](https://www.nice.org.uk/guidance/NG59/chapter/recommendations)
- [NICE — fusion sacro-iliaque mini-invasive, HTG436](https://www.nice.org.uk/guidance/htg436)
- [Assurance Maladie — préparer la reprise du travail](https://www.ameli.fr/assure/droits-demarches/maladie-accident-hospitalisation/arret-travail-maladie/reprendre-travail-apres-arret-maladie)
- [Assurance Maladie — temps partiel thérapeutique, employeurs](https://www.ameli.fr/entreprise/vos-salaries/arret-de-travail/reprise-temps-partiel-therapeutique)
- [Centinel Spine — guide fabricant ProDisc L, conditions IRM propres au modèle](https://www.centinelspine.com/guides/uploads/file/cent_prodisc_l_patientguide_v8_worldwide.pdf)

La HAS sur la lombalgie commune ne constitue pas un protocole postopératoire universel. Les recommandations NICE sont un complément clinique, pas une règle française de remboursement. Les consignes fabricant sont propres au modèle ; ProDisc L ne représente pas tous les implants.

## Validation avant diffusion

Les V2 sont des propositions de relecture. Elles n’ont pas reçu une validation clinique finale. L’arbitrage médical, les protocoles locaux et la validation de la V3 reviennent au Dr Jameson et à l’équipe concernée.
