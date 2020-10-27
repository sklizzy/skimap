# leadskimap


Scraper looks for relevant divs and grabs lift-name and lift-status + puts in a table? <br>
 Example:  <i> @ https://liftie.info/resort/steamboat
 
           <br> lifts are in a unordered list <br> where each item is listed under the li class 'lift'
          <br> wherein there are two span classes, witht he name of the lift and the status (open/closed) boolean
          <br> 
          </i>
          <br>
LED Assigns led number to lift-name and compares table values if open or closed which determines led color
It requests every 7 minutes which can be changed based on processing/network requirements

