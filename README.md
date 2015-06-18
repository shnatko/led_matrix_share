# led_matrix_share
Eagle files for LED matrix control board / analog mux array for IR sensing

Details on the build of the LED matrix ( in coffee table form ) can be found at http://shnatko.tumblr.com

The control_FET files contain the schematic and board files for a single 8x8 common anode 8x8 RGB LED array driving via SPI 
from a microcontroller ( Arduino Due in my case ).
Multiple boards can be chained together to form larger arrays ( matrix I built using them is 16x32 )

The sense_mux files are for a second PCB used to multiplex 64 analog input signals down to 4 outputs pins for input into
the microcontroller.  Again, additional details on how it is used at http://shnatko.tumblr.com

Also included in this package is the MBI.lbr Eagle library in which I created a few components which I needed for the board layout.
