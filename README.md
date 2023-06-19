# Zeiss-LSM-780-tile-stitching
**Prepares tile scan tiffs from Zen software for stitching in ImageJ by:**
1. Detecting x- and y- positions of each tile
2. Saving a tile position text file that has the corresponding x- and y- positions for each tile (in the correct format for ImageJ)
3. Open ImageJ --> Plugins --> Stitching --> Grid/Collection stitching
4. Choose "Positions from file" in "Type" dropdown
5. Select directory (i.e. output directory of this code)
6. Unselect "Computer overlap (otherwise apply coordinates from layout file)
7. Select "Display fusion" if you wish to view the stitching result straight away

