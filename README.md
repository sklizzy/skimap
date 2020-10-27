# leadskimap


Scraper looks for relevant divs and grabs lift-name and lift-status + puts in a table? <br>
 Example:  <i> @ https://liftie.info/resort/steamboat
 
          lifts are in a unordered list where each item is listed under the li class 'lift'
          wherein there are two span classes, with the name of the lift and the status (open/closed) boolean         
          
 </i>         
LED Assigns led number to lift-name and compares table values if open or closed which determines led color
It requests every 7 minutes which can be changed based on processing/network requirements
<br>
metar_retrofit is a AIO program from JJSilvas Neo(pixel)Sectional project https://github.com/JJSilva/NeoSectional
orginially pulls data from the faa aviation weather website working off airport ICAOs and weather designations, but shoudl be realtively simple to switch for pulling text from liftie on the status of resort lifts

