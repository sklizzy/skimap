# leadskimap


Scraper looks for relevant divs and grabs lift-name and lift-status + puts in a table? <br>
 Example:  <i> @ https://liftie.info/resort/steamboat
 
          lifts are in a unordered list where each item is listed under the li class 'lift'
          wherein there are two span classes, with the name of the lift and the status (open/closed) boolean         
          
 </i>         
LED Assigns led number to lift-name and compares table values if open or closed which determines led color
It requests every 7 minutes which can be changed based on processing/network requirements

