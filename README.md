***
# ColombiaFlora
***

## Index script sections
### 1. Standardize and join data of plants of Colombia (SiB Colombia and GBIF - Global Biodiversity Information Facility)
### 2. Match names against POWO taxonomy using PyKew
### 3. Geographic cleaning using CoordinateCleaner
### 4. Results and Summary

    #' @title ColombiaFlora
    #' @author Pablo Hendrigo Alves de Melo (melo.hendrigo@gmail.com)
    #' @description 1. Standardize and join data of plants of Colombia, 
    #' @description 2. Match names against POWO taxonomy using PyKew,
    #' @description 3. Geographic cleaning using CoordinateCleaner
    #' @description 4. Results and Summary

    #' @section 0. Preparation
    {} # end

    #' @section 1.Standardize and join data of plants of Colombia
    #' @section 1.1 - Join data 
    {} # end

    #' @section 2. Match names against POWO taxonomy
    #' @section 2.1 - Prepere POWO check
    {} # end

    #' @section 2.2 - POWO check
    {} # end

    #' @section 2.3 - Update POWO check
    {} # end

    #' @section 3. Geographic cleaning
    #' @section 3.1 - CoordinateCleaner
    {} # end  

    #' @section 4. results and Summary 
    #' @section 4.1 - Join results
    {} # end

    #' @section 4.2 - Summary
    {} # end

***
## Merge columns
***
  #### source (GBIF or SIB)
  #### scientificName_Source
  #### taxonRank_Source
  #### occurrenceID                  
  #### basisOfRecord
  #### modified
  #### institutionCode
  #### collectionCode
  #### catalogNumber
  #### identificationQualifier
  #### identifiedBy
  #### dateIdentified
  #### typeStatus
  #### recordNumber
  #### recordedBy
  #### countryCode
  #### stateProvince
  #### municipality
  #### locality
  #### year
  #### month
  #### day
  #### decimalLatitude
  #### decimalLongitude
  #### elevation
  #### occurrenceRemarks
  #### fieldNotes
  #### vernacularName
  #### samplingProtocol"

***
## Results columns
***

### Match names against POWO taxonomy:
  
  #### .submittedToPOWO
  #### search_unique_POWO (species name without author used in POWO search) 
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
  #### .val  (Invalid lat/lon Coordinates)
  #### .equ  (Records with Identical lat/lon)
  #### .zer  (Zero Coordinates)
  #### .cap  (Coordinates in Vicinity of Country Capitals)
  #### .cen  (Coordinates in Vicinity of Country and Province Centroids)
  #### .sea  (Non-terrestrial Coordinates) 
  #### .urb  (Records Inside Urban Areas)
  #### .con  (Coordinates Outside their Reported Country)
  #### .inst (Records in the Vicinity of Biodiversity Institutions)
  #### .dpl  (Duplicated Records)
  #### .summary

***

## Developers
* Pablo Hendrigo Alves de Melo - melo.hendrigo@gmail.com - [GitHub](https://github.com/pablopains)
