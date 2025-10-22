## Video Plan
- Evren discusses vanderberg / krauss code and results for 2.5 minutes
- Ella discusses Harris positional code and results for 2.5 minutes
- Gigi discusses Harris dynamical code and results for 2.5 minutes
- 2.5 minutes dedicated to answering the research questions as a group (to be filmed in the thursday zoom call)

# Evren code talking points
- Data collection was based on a 2023 paper (show paper) which used total energy and orbital angular momentum to seperate in-situ and accreted GC's in the Milky Way --> shows pattern in the FeH vs. Age data that we can compare the vandenBerg and Krause data to to find suspected accreted globular clusters
- Data reveals in-situ GC's tend to be slightly older and have larger metalicites
- The 'Chemical Bimodality' present in the MW only appears within the in-situ GC's while all accreted ones seem to keep to lower Fe/H values
- There is slight overlap for accreted and in-situ GC's for the oldest and lowest metalicity clusters, but there is a clear divide for younger ones
- Using plot from paper, we devised a rough line that seperates accreted from in-situ GCs
- We then create a mask that selects all the clusters below the line
- We then can take this data and add it to an empty list, which checks for duplicates before adding the GC
- This gives us a rough outline of suspected GC's based off of their Age and Fe/H ratio

# Ella code talking points
- Accreted GCs lie in the galactic halo, meaning GC's found furthest from the galaxies centre are more likely to be accreted
- We can use the positional data in Harris part 1 to make a 3D scatterplot and roughly identify GCs which lie in the halo
- Made three two dimensional scatterplots in each axes combination (ie x,y / x,z / y,z)
- These scatterplots have been coded with interactive cursors so that we can pick a likely range of radii within which the accreted globular clusters would lie
- Import these bounds into the filtering cells to find for each frame (ie x,y / x,z / y,z) which are the most likely candidates for accreted globular clusters.
- wrote a 'detect_duplicates' which removed any GC's which occur in the list twice (which happens if a GC sits in the accreted boundary for more than one axis)
- Finally, we clean up the list using the last 3 lines of code which print only the name of the Globular cluster and not the 'object type'


# Gigi code talking points




## Research questions talking points