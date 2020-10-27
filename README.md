# leadskimap


Scraper looks for relevant divs and grabs lift-name and lift-status and puts in a table 
 Example: <i><!--
            <div data-v-9ad5b0fa="" data-v-18530604="" class="lift col no-stretch closed-lift">
              <div data-v-9ad5b0fa="" class="lift-collapsed">
                <div data-v-9ad5b0fa="" class="lift-title-box">
                  <div data-v-9ad5b0fa="" class="lift-hours closed">9:00AM - 3:00PM</div>
                  <div data-v-9ad5b0fa="" class="lift-name">Bar-UE</div>
                  <div data-v-9ad5b0fa="" class="lift-status closed">Closed</div>
                 </div>
               </div>
            </div>
           --->
          </i>
LED Assigns led number to lift-name and compares table values if open or closed which determines led color
It requests every 7 minutes which can be changed based on processing/network requirements

