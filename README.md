# Gangs and Displacement in Port-au-Prince, Haiti

## Find my page here. https://bennett-hanson.github.io/Gangs-and-Displacement-in-Haiti/

I sought to analyze the data from the International Organization for Migration's assesment of the displacement caused by insecurity and gangs in the Haitian capital of Port-au-Prince. That data, from March 2023, can be found here (https://data.humdata.org/dataset/haiti-displacement-idps-baseline-assessment-iom-dtm/resource/00acbb24-2a1c-4b14-9a2d-7217f6c37d81).

__Questions I explored:__
- The number of IDPs / IDPs per commune/neighborhood
- Site types (spontaneous or host communities)
- Where did the IDPs come from? 
- How many people over 60? Under 18?
- How many sites are inaccessible?
- Is there tension between the host community and the IDPs?
- What assistance has been received? Food? Health? Cash? Education?
- Do the IDPs have identification?
- Cholera deaths among IDPs

__Findings:__
- Over 127,000 IDPs were counted by IOM in Feb and March 2023
- The areas known as 6th Turgeau and 2nd Varreux (Canaan - Jerusalem) saw the largest waves of out-migration due to gang violence since 2020.
- Most displaced people are seeking shelter in the commune of Port-au-Prince, followed by Delmas and Cité Soleil.
- About 82% of the sites visited by IOM are what are "host communities."
- Half of the IDPs are children (27,773 boys and 36,131 girls). People over the age of 60 made up just 6% of the displaced population.
- Tension exists between the IDPs and their hosts in about a quarter of host communities (55 sites).
- Obout 5% of sites had received food, health or cash assistance, while 4% received water and sanitation aid and less than 1% received education or psychosocial assistance.
- Humanitarian workers can access these displacement sites about 81% of the time. In the cases when the sites aren't accessible, 60% of the time it's due to physical constraints; 40% of the time it's due to insecurity.
- In about 39% of the IDP sites, the majority of displaced persons don't have personal identification documents.
- At least 590 people in these displaced camps have died from cholera.

__Data collection methods:__
- IOM included data from 459 IDP sites and host communities during their visit in February and March 2023; however, 172 of these entries had very little to no data, so I removed them from my analysis. This left 287 sites to analyze. Analysis was done with Python in Jupyter Notebook.
- I used a geojson map file showing Haiti's fourth-level administrative divisions from the University of Texas Austin (https://geodata.lib.utexas.edu/catalog/stanford-pg534pk2788).
- The names of the fourth-level administrative divisions didn't always match between the UT map and the IOM data, so I used OpenStreetMap to clarify irregularities.
- Contextual research was aided by documents from UN OCHA. 

__Skills I learned:__
- How to auto-translate cells in Google Sheets, which I used to translate the original data from French to English
- How to crop and simplify a geojson in Mapshaper
- How to make and edit a map in Datawrapper
- How to align data/names between geojson and Datawrapper

__If I had more time, I would explore:__
- When were people displaced? What were the most common days/months of displacement?
- Average people per square meter at sites
- A map of where IDP sites are located
- How to make and effectively display a map showing the gangland territories
- Change the names of the locations on the interactive Datawrapper chart from French to English
- Change the Google Maps embed to a fancier interactive map

### Contact

Bennett Hanson, bennett@globalpressjournal.com | Twitter: @bennett_hanson
