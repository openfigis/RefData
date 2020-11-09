This is the FAO Fishery and Aquaculture Reference Data repository.


file naming:
-------------
-TS_*  "time-series": corresponds to the contents of the FAO database and structure according to a series of codes (CL);

-CL_*  "code-lists": contains the identifier and mapping to other codes and descriptions; 

-HCL_*  "hierarchical code-lists": contains the grouping information, a pointer (foreign key) from the reference object (parent) to the children

-DSD_* "Data Structure Definition": describes how information in a specific dataset is structured. It defines the dimensions, measures and their related attributes. 

In this release the colum names have changed slightly; and columns are ordered alphabetically. The change was required, as we migrated from the legacy FIGIS/RTMS to the corporate MDM system. 
We do apologise for any inconvenience caused.

file encoding:
-------------
Character enconding system in CSV files
All information contents in the files in CSV (comma-separated values) format are made available in UTF-8. 
To open these files in Excel, go to the menu
Data->From Text and select File origin "65001: Unicode UTF-8" and comma delimiter

Note: When using time-series data, in order to obtain the aggregates presented in the 
Summary Tables of the "FAO Yearbook of Fishery Statistics - Aquaculture Production" which exclude production figures 
for aquatic plants, pearls and mother-of-pearl, data should be filtered using a Custom Group:
"Fish, crustaceans and molluscs, etc."(1801).

COPYRIGHT & DISCLAIMER CLAUSES
---------------------
FAO encourages the use, reproduction and dissemination of material in this information product. Except where otherwise indicated, material may be copied, downloaded and printed for private study, research and teaching purposes, or for use in non-commercial products or services, provided that appropriate acknowledgement of FAO as the source and copyright holder is given and that FAO�s endorsement of users� views, products or services is not implied in any way.
All requests for translation and adaptation rights, and for resale and other commercial use rights should be made via www.fao.org/contact-us/licence-request or addressed to copyright@fao.org.

The designations employed and the presentation of material in this information product do not imply the expression of any opinion whatsoever on the part of the Food and Agriculture Organization of the United Nations (FAO) concerning the legal or development status of any country, territory, city or area or of its authorities, or concerning the delimitation of its frontiers or boundaries. The mention of specific companies or products of manufacturers, whether or not these have been patented, does not imply that these have been endorsed or recommended by FAO in preference to others of a similar nature that are not mentioned.

FAO declines all responsibility for errors or deficiencies in the database or software or in the documentation accompanying it, for program maintenance and upgrading as well as for any damage that may arise from them. FAO also declines any responsibility for updating the data and assumes no responsibility for errors and omissions in the data provided. Users are, however, kindly asked to report any errors or deficiencies in this product to FAO.
The word "countries" appearing in the text refers to countries, territories and areas without distinction. 
The designations employed and the presentation of material in the map(s) do not imply the expression of any opinion whatsoever on the part of FAO concerning the legal or constitutional status of any country, territory or sea area, or concerning the delimitation of frontiers.

For comments, views and suggestions relating to this data, please email to:
Email: Fish-Statistics-Inquiries@fao.org

(c) FAO 2020
