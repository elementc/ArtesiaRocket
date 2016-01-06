# ArtesiaRocket
Repository of (eventually) open-source model rocket components. Shares a name with an area of Port Canaveral [before it was Port Canaveral](http://www.cityofcapecanaveral.org/index.asp?Type=B_BASIC&SEC=%7BFCF82651-D0DA-4BE5-B512-1652A96826AE%7D).

# Current Build
We emulate an existing simple Estes rocket (the EX-200) which features a mini engine mount. While all the structural components are printable,  there will always be some [vitamins](http://reprap.org/wiki/Category:Vitamin) in need of collection.

## Bill of Materials
* 1 x [Estes EX-200 kit](http://www.estesrockets.com/rockets/rtf/002450-ex-200tm), in particular:
  * 1 x Shock cord
  * 1 x Parachute
* 1 x Engine Retention Ring model from physibles/20mm (These are fragile so you may want to print some duplicates. They print fast.)
* 1 x Engine Mount model from physibles/20mm
* 4 x Fin model from physibles/20mm
* 1 x Paraboloid Nose Cone model from physibles/20mm
* 1 x Body Tube 130mm model from physibles/20mm
* 1 x Body Tube 50mm model from physibles/20mm
* 1 x Body Tube Coupler with hook model from physibles/20mm
* Glue (superglue works great!)
* Masking Tape
* Paint

## Assembly
1. Print all physibles. Clean off support materials as needed. Sand until smooth.
2. Glue fins into slots on engine mount. Glue shorter body tube onto engine mount ring.
3. Tie shock cord to coupler inner beam.
4. Glue coupler to other end of shorter body tube.
5. Pull free end of shock cord through long body tube.
6. Glue long body tube to coupler.
7. Tie free end of shock cord to nose cone loop.
8. Apply tape as necessary to nose cone friction mount. Should be able to slide into free body tube end and remain securely but pop off relatively easily.
9. Tie parachute to nose cone loop.
10. Snap engine retention ring into place at bottom of engine mount.
12. Apply paint as desired.

## Printing Pointers
Use calipers to measure your filament diameter. Underextrusion/overextrusion will KILL some of these prints. Print at 100% infill for body tubes, make sure you have good cooling and a SLOW extrusion rate (30mm/s is the our max). For nose cones, smaller infill is better, we use 20%. Complex parts like couplers and nosecones with hooks need support material. Sand all parts to be as smooth as you can get them, especially areas where support material was removed.


# License
Physible designs are generally available under the latest [Creative Commons Attribution-NonCommercial-ShareAlike license](http://creativecommons.org/licenses/by-nc-sa/4.0/).
Source code is under the [Apache License](http://choosealicense.com/licenses/apache-2.0/) unless indicated otherwise in the source.
