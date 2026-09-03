# Point Mort Aligneurs

Tableau de bord interactif pour comparer le coût de production des aligneurs **thermoformés** vs **imprimés directement**, et calculer le seuil de rentabilité de l'investissement dans la station d'impression directe (imprimante, polymérisateur, lavage).

Toutes les valeurs (prix des résines, temps de fabrication, coût des machines, volumes annuels) sont modifiables directement dans la page : change un champ et le tableau des coûts, les cartes et le graphique se mettent à jour tout seuls.

## Ce que ça calcule

- Coût par gouttière et par traitement complet, thermoformage vs impression directe
- Comparaison entre deux machines de découpe (VHF vs LAC) pour le thermoformage
- Seuil de rentabilité de l'investissement dans l'impression directe (gouttières, cas patients et années)
- Économie annuelle en rythme de croisière une fois le seuil dépassé
- Graphique des économies cumulées dans le temps, avec le seuil de rentabilité mis en évidence

## Comment la publier sur GitHub Pages

1. Crée un nouveau repository (ex. `point-mort-aligneurs`)
2. Charge `index.html` et ce `README.md` à la racine du repository
3. Va dans **Settings → Pages**, sélectionne comme source la branche `main` (dossier `/root`) et enregistre
4. La page sera en ligne sur `https://<ton-nom-utilisateur>.github.io/<nom-du-repo>/`

Aucune build, aucune dépendance à installer : c'est un seul fichier HTML statique.

## Notes sur les données

Les prix et temps de fabrication saisis comme valeurs de départ sont ceux communiqués pour le cabinet de référence (80 gouttières/mois). Ce sont des estimations signalées dans la page : le volume de résine par gouttière imprimée directement (non publié par le fabricant) et les années de vie utile estimées pour l'équipement.

Version française du tableau de bord original en italien (Pareggio Allineatori).
