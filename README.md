# ForestPriorityAreas
Zonation assesment takes ecological aspects into consideration and scores (forest) areas based on these background factors. In this repo, Zonation values are utilized in priority assesment and to select the top 30 % and top 10 % areas out of forest stands. These areas are then mirrored to the current conservation areas to possibly suggest priority forest areas and to calculate statistics (by group, e.g. fertility_class, age_class, protection_class) about them.

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
