# gmaps
--------
Current state: minimal working version<br>
Supports: Windows 7, python 2.7<br>
Packages used: csv, json, os, sys<br><br>　
Outputs a bunch of google map images for list of x,y coordinates in CSV file for (very) quick viewing of x,y locations.
--------
config.json file holds below config settings:<br>　
API keys<br>
output map size, magnification, type (hybrid, satellite)<br><br>
Please set as necessary.<br>　
--------
To run:<br>
gmaps.py [sourceCSVfile.csv]<br><br>
Replace with source CSV file holding x,y coordinates.<br>
If CSV in same file as python file, can use relative path. Otherwise use absolute path.<br><br>
By default outputs target html file into same directory as python file.


