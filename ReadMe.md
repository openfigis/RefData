This is the FAO Fishery and Aquaculture Reference Data repository.


file naming:
-------------

- CL_*   "code-lists": contains the identifier and mapping to other codes and descriptions; 

- HCL_*  "hierarchical code-lists": contains the grouping information, a pointer (foreign key) from the reference object (parent) to the children

- FSJ_*  FishStat metadata; we use it to define FishStatJ and the query panel

- DSD_* "Data Structure Definition": describes how information in a specific dataset is structured. It defines the dimensions, measures and their related attributes. 

raw data download:
*.csv  "time-series" file with the name <DATASET>_<TIMESERIES>.csv


All information contents in the files in CSV (comma-separated values) formatted as UTF-8. 
To open these files in Excel, go to the menu
Data->From Text and select File origin "65001: Unicode UTF-8" and comma delimiter

When using time-series data, in order to obtain the aggregates presented in the 
summary tables of the "FAO Yearbook of Fishery and Aquaculture Statistics" which exclude production figures 
for aquatic plants, crocodiles, aq. mammals, pearls and mother-of-pearl, corals and sponges data should be filtered using a Custom Group:
"Fish, crustaceans and molluscs, etc."(1801).

Please note that the list of species disseminated here, reflects the ASFIS standarad compatible with the data being published.
As such, it does not adhere entirely to ASFIS due to differing publication schedules.

TERMS OF USE/LICENSE:
--------------------
https://www.fao.org/contact-us/terms/db-terms-of-use/en

The Food and Agriculture Organization of the United Nations ("FAO") is mandated to collect, analyze, interpret, and disseminate information related to nutrition, food, and agriculture.
In this regard, it publishes a number of databases on topics related to FAO’s mandate, and encourages the use of them for statistical, scientific, and research purposes. 
Accordingly, all databases provide datasets free of charge, in machine-readable format, and subject to the terms of use of this agreement ("Dataset terms") and the Terms and Conditions regarding the Reuse of Web content , which are incorporated herein by reference.

FAO encourages you to use FAO databases for research, statistical, and scientific purposes. You may access, download, create copies and re-disseminate datasets subject to these Dataset terms.

C BY-NC-SA 3.0 IGO

This work is made available under the Creative Commons Attribution-NonCommercial-ShareAlike 3.0 IGO license (CC BY-NC-SA 3.0 IGO; https://creativecommons.org/licenses/by-nc-sa/3.0/igo ). In addition to this license, some database specific terms of use are listed: Terms of Use of Datasets.

When you access, download, or otherwise extract any data from any dataset, you agree to comply with the CC BY–NC–SA 3.0 IGO, and all terms specified in this Dataset Terms.

COPYRIGHT & DISCLAIMER CLAUSES
-----------------------------
All requests for translation and adaptation rights, and for resale and other commercial use rights should be made via www.fao.org/contact-us/licence-request or addressed to copyright@fao.org.

The designations employed and the presentation of material in this information product do not imply the expression of any opinion whatsoever on the part of the Food and Agriculture Organization of the United Nations (FAO) concerning the legal or development status of any country, territory, city or area or of its authorities, or concerning the delimitation of its frontiers or boundaries. The mention of specific companies or products of manufacturers, whether or not these have been patented, does not imply that these have been endorsed or recommended by FAO in preference to others of a similar nature that are not mentioned.

FAO declines all responsibility for errors or deficiencies in the database or software or in the documentation accompanying it, for program maintenance and upgrading as well as for any damage that may arise from them. FAO also declines any responsibility for updating the data and assumes no responsibility for errors and omissions in the data provided. Users are, however, kindly asked to report any errors or deficiencies in this product to FAO.
The word "countries" appearing in the text refers to countries, territories and areas without distinction. 
The designations employed and the presentation of material in the map(s) do not imply the expression of any opinion whatsoever on the part of FAO concerning the legal or constitutional status of any country, territory or sea area, or concerning the delimitation of frontiers.

For comments, views and suggestions relating to this data, please email to:
Email: Fish-Statistics-Inquiries@fao.org

(c) FAO 2024
