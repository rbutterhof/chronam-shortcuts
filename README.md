# chronam-shortcuts

Documenting shortcuts for ChronAm Search

## Searching in a particular title

Limiting your search to a particular title can be difficult if you use the the title text facet. You can limit a search to a particular title by finding the titles LCCN/unique ID and then using that to facet. On the loc.gov site, the LCCN is the number after https://www.loc.gov/resource/[LCCN] or https://www.loc.gov/item/[LCCN].  

This is the URL for page 1 of the 8/3/1941 issue of the Detroit Evening Times
https://www.loc.gov/resource/sn88063294/1941-08-03/ed-1/?sp=1

Newspaper LCCNS often start with "sn" but they can also start with a year, like "2025". In the above example, the LCCN is sn88063294. 

One you have the LCCN for a title, you can limit that search with &fa=number_lccn:

In this example, I'm searching the pages of the Detroit Evening Times for the word "rations". 

https://www.loc.gov/collections/chronicling-america/?dl=page&ops=AND&qs=rations&searchType=advanced&fa=number_lccn:sn88063294
