# [U.S. school shootings map](http://interactive.nydailynews.com/map/school-shootings/)

## How to update the school shootings map

1. Update the spreadsheet with the latest shooting found here: https://everytownresearch.org/school-shootings/
1. Convert the spreadsheet to JSON: https://www.csvjson.com/csv2json
1. Update [www/data/2018.json](www/data/2018.json) with the new JSON.
1. Update the Data Last Updated date in [www/index.html](www/index.html).
