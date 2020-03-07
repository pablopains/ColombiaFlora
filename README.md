***
# ColombiaFlora
***

## Index script sections
### 1. Standardize and join data of plants of Colombia
### 2. Match names against POWO taxonomy using PyKew
### 3. Geographic cleaning using CoordinateCleaner
### 4. Results and Summary

 ## results columns
  ### Match names against POWO taxonomy:
  #### .submittedToPOWO
  #### search_unique_POWO  
  #### nomenclaturestatus_POWO
  #### author_POWO
  #### kingdom_POWO
  #### group_POWO
  #### order_POWO
  #### family_POWO
  #### name_POWO
  #### rank_POWO
  #### url_POWO
  #### fqId_POWO
  #### synonyms_homonyms_POWO
  
  ### Geographic cleaning:
  #### .submittedToCoordinateCleaner
  #### .val  # Invalid lat/lon Coordinates  
  #### .equ  # Records with Identical lat/lon
  #### .zer  # Zero Coordinates 
  #### .cap  # Coordinates in Vicinity of Country Capitals
  #### .cen  # Coordinates in Vicinity of Country and Province Centroids
  #### .sea  # Non-terrestrial Coordinates 
  #### .urb  # Records Inside Urban Areas
  #### .con  # Coordinates Outside their Reported Country
  #### .inst # Records in the Vicinity of Biodiversity Institutions
  #### .dpl  # Duplicated Records
  #### .summary

## Developers
* Pablo Hendrigo Alves de Melo - melo.hendrigo@gmail.com - [GitHub](https://github.com/pablopains)
