# MOST25_Mercedes
Integration of Mercedes Benz W211 MOST-25 Fiber Optic Network and Raspberry Pi 3 B+
https://en.wikipedia.org/wiki/MOST_Bus

I recently bought a older, Mercedes diesel.
It is a great car, but the 13-year old on-board computer is really lame.
But it does have a pretty interesting fiber optic network on-board.

Several local Mercedes owners have upgraded to Android head units; they are pretty nice and all....
As far as I can tell, however, these head units end up as just dummy audio devices with respect
to the fiber optic network, and still require an extra $100 converter just to do that.

It seems pretty straightforward to actually leverage the attributes of the fiber optic network and add
an additional, bona fide node to the fiber network to add more modern capabilities without destroying 
the car's original equipment.

To this end, I am starting out with:

      Raspberry Pi 3 B+ 
            Running Raspbian GNU/Linux 9 (stretch), kernel 4.14.69-v7+
     
      --- via I2S ---
            https://en.wikipedia.org/wiki/I%C2%B2S

      M25I MOST 25 Optical Interface
            https://www.simplemedianetworks.com/product/m25i-most-25-optical-interface
          
             
I also plan to use the Raspberry Pi as a serial interface to the CAN Bus for other automation, monitoring, and diagnostics.
