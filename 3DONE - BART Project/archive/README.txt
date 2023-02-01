README
http://64.111.127.166/origin-destination/

This data represents BART ridership by origin and destination (O-D) pairs. 
Each .csv file is compressed into a gz/gzip archive and contains 
five columns representing Day, Hour, Origin Station, Destination Station, and Trip Count. O-D pairs 
with a trip count of "zero" were ignored during file output to reduce file size. 
For a list of station name abbreviations visit https://www.bart.gov/sites/default/files/docs/Station_Names.xls