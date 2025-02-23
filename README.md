# Wrong-transport-scheme-for-CDEK
OpenSource code for CDEK
This code's input is an Excel list with typical data with parcels from warehouse A to warehouse B, and the output is the list of parcels were sorted wrongly (destination office from A != B)
Even if it is easy, this code gives CDEK 1.5h/week per sorting centre to monitor the wrong transport schemes and adjust it on time. Economy is about 122'000 rubles/week.
As the input we upload the file from the inner WMS programm to get the whole pool of parcels from A to B within a week. Then run the code in Colab and download the .xlsx file with only the wrong sorting schemes and UID codes of parcels were misshipped.
