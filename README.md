# Alpenglow-Swift
Open-source hardware repo for the Glider Swift.

Hello my fellow fiber enthusiasts.  Here you will find all files needed to reproduce parts for the Alpenglow Glider Swift.  It's all under a permissive CERN Open Hardware License v2, the text of which is included in this repo.  It does require attribution, so if you make something with these files, give a shout-out to Alpenglow Industries.  

Note that we were purchasing parts and materials in large batches, so our sources that are listed in the [Swift BOM spreadsheet](AlpenglowSwiftBOM.xlsx) may or may not be relevant for you.  Use it as a starting point.  The ReadMe docs in each folder will have more info about the parts that folder describes.  Below is a discussion of some design choices and manufacturing considerations.

## Replacement Struts
Alpenglow Industries sold repair kits when we announced the shutdown of the business.  If you need replacement struts, the files needed to laser cut struts for your swift are in the Swift Struts folder.  Please also note [the Swift SN Config spreadsheet](https://github.com/AlpenglowIndustries/Alpenglow-Swift/edit/main/README.md#:~:text=%23%20Alpenglow%2DSwift), as there were several different strut configs over the production cycle of the swifts and you want to be sure to get the correct config for your serial number (found marked on the shaft inside of the clamp).  There are several small businesses with laser cutters in the fiber world, try reaching out to see if they'll cut struts for you and what the cost will be.  Note that almost all the acrylic used in Glider Swifts was specialty - Alpenglow was ordering large quantities directly from one of the factories that make it in China and arranging for sea freight shipping.  Small businesses buying this material at retail prices from distributors here in the States will absolutely be paying more for it.  As we become aware of businesses and individuals that are willing to cut and provide replacement swift struts, we will link them here.

Carrie Sundra - individual - best reachable thru [Discord](https://discord.com/users/461976578734161920) and [old emails](mailto:info@alpenglowyarn.com) still work.  Turn-around time is highly variable.

## 3D Printed Parts
The Swift Hubs and Raising Collar were all printed out of ABS, which is an engineering plastic.  It's smelly, requires good ventilation or filtration, an enclosed printer, and a heated print bed.  Printing these out of PLA is not recommended because it warps and deforms when it's hot out or is left in a hot car.  Early batches were printed with PETG, but we had some squeaking issues that required sanding the hubs to fix and it was a real pain in the ass.  ABS is the best material.  If you can't or don't want to print ABS, use Craftcloud to find a print farm that will, prices are extremely reasonable these days.

The Linear Bearing was printed with an MJF process which is highly specialized and reproduces complex shapes very accurately, which was needed for batch consistency with our swifts.  You can outsource this via Craftcloud as well.  It can be printed with an FDM process (normal 3D printer that uses filament) with PETG, but depending on your printer, your filament, and settings, it may turn out too loose or too tight.

The Swift Finial (the little plastic knob on the top with the Alpenglow logo) was printed with PETG in-house by Alpenglow.

## Raising Collar Assembly Notes
This was actually the best part about this swift, I got the overall idea from a cheap-ass amazon swift and designed a custom Raising Collar / Locking Plate assembly for the Glider Swift.  The shape of the Raising Collar went through many many iterations and is extremely particular - there is a reason for every curve and protrusion.  Please steal this assembly and use it in your designs, it will work with a 12mm shaft.  It will not work with a 1/2" shaft, every part and the hubs would have to be modified for the slightly larger diameter.  Seriously, yarn people deserve nice tools that operate without having to use two hands to fuck with some dumb-ass wood screw.

## Swift Strut Ties
These are computer fan mounts.  We went through a lot of iterations of different types of ties - my favorite were using large piercing horseshoes and the beta units were originally made this way.  Unfortunately, the balls at the ends of the horseshoes tended to loosen over time and fall off.  The silicone fan mounts were my last effort before I went back to using string - which it turns out is a just fine and nice way to tie struts together.  String doesn't get caught on yarn, it doesn't affect the smoothness of opening and closing the swift, and it's easily replaceable.  I know people hate it and maybe think it's "cheap", but it's actually quite effective.  Anyway, the fan mounts are available off the shelf in black, but not white.  The white ones were custom shot for Alpenglow and the min order was 10,000.  Carrie saved some from the trash, [contact her](mailto:info@alpenglowyarn.com) if you need any.

## Swift Clamps
We got these directly from a factory in China that makes a variety of table clamps.  You can find similar ones on amazon.  Make sure it fits a 12mm shaft, clamps designed for 1/2" shafts maaaay work but they'll be a little sloppy.

## Swift Bag
Yeah I know, we got these direct from China as well.  I priced these out in the US and they were 4x as expensive and required much higher minimum orders (500 or 1000).  There was absolutely no way I could work with that pricing, I would have had to increase the price of the swift by at least $20 and it was already one of the more expensive swifts on the market.  I strongly felt that a bag needed to be provided for scratch protection while stored, so I went with the option I could afford.  It's basically a shortened yoga mat bag with the Alpenglow logo printed on it, made out of pre-shrunk 100% cotton.

