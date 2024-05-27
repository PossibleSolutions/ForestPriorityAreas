# PotentialForestPriorityAreas
Zonation is a prioritization tool (Moilanen et al. 2005, https://royalsocietypublishing.org/doi/10.1098/rspb.2005.3164) which takes ecological spatial data (species, habitats etc.) as input data. Zonation software creates a priority ranking based on these biodiversity features and other possible selection criteria (e.g. data on costs, connectivity etc.). In this repo, previous Zonation prioritization results (Mikkonen et al. 2018, https://helda.helsinki.fi/items/7f18c3b7-50c0-432b-a62e-f9955d0b2de1, in Finnish) are being utilized in post-processing analyses to select the top 30 % and top 10 % areas out of forest stands in three Finnish provinces (Uusimaa, Pirkanmaa, Kainuu). The priority areas are then mirrored to the current conservation areas to suggest potential priority forest areas either for conservation or closer-to-nature forestry. Post-processing analyses allow us to calculate statistics on identified potential priority forest areas (by group, e.g. fertility class, age class, protection class). Zonation raster values were linked to forest stand polygons with QGIS Zonal statistics tool (r"YourPathToFileWithZonationValues"). 

Zonation raster values were linked to forest stand polygons with QGIS Zonal statistics tool (r"YourPathToFileWithZonationValues").

Region of interests, forest stands can be dowloaded from  
https://avoin.metsakeskus.fi/aineistot/Metsavarakuviot/Maakunta/  
Variable description   
https://www.metsakeskus.fi/sites/default/files/document/mvjaete-koodisto-ja-tietokantakuvaus_0.xlsx

Zonation results to base the prioritization on, can be downloaded from  
https://ckan.ymparisto.fi/dataset/monimuotoisuudelle-tarkeat-metsaalueet-high-biodiversity-value-forests-2018-zonation-fin-eng-sw

Conservation areas can be partly found from  
https://ckan.ymparisto.fi/dataset/luonnonsuojelu-ja-eramaa-alueet  
https://ckan.ymparisto.fi/dataset/luonnonsuojeluohjelma-alueet  
https://ckan.ymparisto.fi/dataset/valtion-muut-suojelualueet  
https://ckan.ymparisto.fi/dataset/natura2000-alueet  
Conservation data from private areas is not always open data
