- sub_sampling_grid_big_grid.Rmd : algorithme qui crée les gros points tous les 300km (copier-collé de sub_sampling_grid)
- sub_sampling_grid_all_ecoregions_together.Rmd : j'imagine que j'avais fait pareil pour toute l'Afrique et plus écorégion par écorégion
- giving_a_big_cell_number_naive.R : code naif qui prend tous les points subsamplés à 10 km et calcule la distance avec les points à 300km afin d'attribuer le niveau de la case 300km à chaque petit point (et qui permet in fine le bayésien hiérarchique tous les 300km)
- visu_300km_10_km.qgz : enfin utiliser QGIS pour vérifier en sortie si on a bien les points en adéquation avec leurs localisations