# Maps and Coordinate Systems

## Introduction

The technology available to us today in the form of GPS, combined with tools and resources used for centuries -- map and compass -- makes back country navigation for the serious hunter more feasible and field-practical than ever before.

Back country navigation should mean more than being able to find your way back to camp or getting yourself sorted out when you're turned around. Regardless of species, hunting style, topography, or location the hunter can -- indeed, should -- integrate the aggregate resources of map, compass, and GPS directly into his hunting strategy. With GPS, the *right* compass, and the *right* map system, the hunter, trained and practiced in their interwoven use, can roam the back country at will, hitting chosen spots day or night.

I've trained hundreds of fellow cops, rural firefighters, search and rescue volunteers and hunters in back country navigation, and over the years I've developed a hands-on navigation system for serious hunters that emphasizes practicality and utility above all else, focused on a theme of solving the problems most commonly encountered.

Many hunters buy a GPS with the notion that it's going to solve all their navigation problems and replace maps and compasses, and it doesn't help that GPS manufacturers don't do much to dispel this notion. This is poor strategy; the fact is that it's far more effective to combine the resources of all three -- map, compass, and GPS -- in an effective, comprehensive system, the components of which actually serve as backups, each for the other.

Map, compass, and GPS -- we'll deal with them one at a time, covering their interwoven use as we go. I'll be happy to answer any questions through the Kifaru Hunting or Military forum boards.

## Map

The most important facet of the system -- and the least dispensable -- is the map, specifically the United States Geological Survey 7 1/2" topographic maps, 1:24,000 scale (1 inch = 24,000 inches, or 2,000 feet), which cover -- and are available for -- the entire United States outside of Alaska, which is covered by the USGS's 1:63,360 scale (1 inch = 1 mile) topos. (In addition, the USGS also has available the smaller-scale 1:100,000 topos for the lower 48 and the 1:250,000 scale series for Alaska. I like to call maps of this scale "reconnaissance maps." Depending on topography and circumstances, these, too, can be very useful.)

### Grid Systems

There are two grid systems that can be used with USGS topo maps: Latitude-Longitude (Lat-Lon) and Universal Transverse Mercator (UTM). We'll cover Lat-Long first, as a general familiarity with it is helpful, but as we'll see, the best system for land navigation -- especially the for the hunter -- is UTM. (Be aware that your GPS can be set for any grid system you like -- it takes only a second to change -- but it almost certainly came from the factor defaulted to Lat-Lon. We'll discuss changing the setting in the "GPS" section of the essay.)

Every map grid system basically works the same way; a coordinate is a combination of position along a east-west line and a north-south line. The most basic version is your hometown phone book map - City Hall is at G-5, Smith Park is at B-11, and so forth.

Lat-Lon is grounded on two sets of imaginary lines, beginning with parallel lines of latitude, which circle the earth from east to west. The Equator is zero degrees latitude, parallel lines of latitude north of the Equator are referred to as parallels of north latitude; those south of it are called parallels of south latitude.

Imaginary lines of longitude, called meridians, circle the earth from pole to pole, beginning at zero degrees longitude at Greenwich, England running east and west from Greenwich and meeting at the International Date Line on the opposite side of the globe.

Lat-Lon coordinates are expressed in geometric terms of degrees, minutes, and seconds; each degree is made up of 60 minutes, each minute of 60 seconds, and here's where the trouble starts for the land navigator. Coordinate information here is expressed in mathematical terms, not in units of actual ground distance, and trying to correlate the two is a nightmare. To make matters worse, while latitude is a constant anywhere on the planet -- one minute of latitude subtends a nautical mile of 2,000 yards -- longitude is not constant; meridians of longitude are constantly converging as you move north or south of the Equator. The bottom-line, real-world headache for the land navigator: Lat-Lon coordinates are more difficult to plot on a map, because they represent a grid system for a sphere (the earth) transferred to a flat surface (the map). That's why 7 1/2" topo maps are rectangles and not squares: the map boundaries on the east and west sides are actual meridians of longitude 7 1/2 minutes apart and the north and south boundaries are parallels of latitude, also 7 1/2 minutes apart.

Universal Transverse Mercator (UTM) has been dealing with all of Lat-Lon's problems since 1947, when it was adopted by virtually every military ground force in the world.

First and foremost, UTM beats Lat-Lon's most fundamental shortcoming by taking the spherical shape of the earth out of the formula; it puts a flat grid system on a flat surface. Here's how: picture an orange representing the earth sliced twice, peel-deep only, from pole to pole, with the slices at a ninety-degree angle. Pull one of the peels off and look at it; you're holding a peel that's pointed at both ends and bowed out in the middle. Now place the peel on a table, flatten it out, and *then* put your map grid on it -- that's UTM.

UTM covers not quite the entire planet -- the extremes of both polar regions are left out, but it's OK; a different grid system built into your GPS called UPS covers these areas, in case you draw out on a penguin hunt or a visit to Santa's Castle. The resulting flattened map of the world starts the International Date Line and, moving east, divides the planet into 60 zones of 6 degrees of longitude each. The zones covering the lower 48 states, for instance, are zones 12 through 19, moving west to east.

Here's where we leave Lat-Lon behind, even as a general reference. Everything from here on out is expressed in actual land measurements under the metric system. It helps here to get a basic handle on two metric measurements: meters and kilometers. A meter is about 39 inches -- a little over a yard. Your memory crutch here, when dealing with a distance expressed in meters, is either to add a healthy dab to convert the distance to yards or, alternatively, multiply the distance in meters by 1.1 to obtain a more precise calculation -- whichever you find handier. An object 300 meters away then, is "a dab over 300 yards;" if you do the math, about 330 yards. 400 meters is about 440 yards, 600 meters is close to 660 yards, and so on.

A kilometer -- a "click" to those in or who spent time in the military -- is 1,000 meters or about 1,100 yards. It's the metric system's rough equivalent, in general terms, of a mile and to convert kilometers to miles, multiply by .6 or 6/10s. 5 kilometers (5K) is thus about 3 miles, 10 kilometers is about 6 miles, 30 kilometers about 18 miles, and so forth.

OK, here's how it works in a nutshell: a UTM coordinate is your distance from west to east across your zone in meters -- your Easting -- and, again in meters, your distance north of the Equator -- your Northing. That's it. Period. The key thing to remember about UTM is that it only deals with two directions: west moving east and south moving north: the numbers always get bigger as you go east, and they always get bigger as you go north. Always. Everything, therefore, is east and north, or, if you prefer, right and up. The way UTM breaks down, every square meter has -- indeed, *is* -- its own coordinate.

Let's try an example to illustrate. The summit of Hawks Rest in Wyoming's Yellowstone River country appears on the UTM-gridded map in Figure 1. Its UTM coordinate is expressed -- and will appear on your GPS if you're standing on top -- as follows:

    12 5 73 548 E
      48 83 868 N

![Hawks Rest](figures/01.jpg)

The top number -- the Easting, identified by the "E," -- is always expressed first, and the first number in the Easting is always the zone number; in this instance, zone 12. The rest of the number tells us that the Easting itself is 573,548 meters across zone 12 from west to east.

The second, lower number is the Northing, identified by an "N," which identifies the Northing as 4,883,868 meters north of the Equator. Where the Easting and Northing meet on the map is your UTM coordinate.

Refer now to Figure 2. The map in Figure 2 is identical to Figure 1's map - it's UTM-gridded and "rulered" in 100-meter increments. The Easting figures appear along the top of the map, and the Northings on both sides. As always, let's do the Easting first.

![Hawks Rest Plotted](figures/02.jpg)

As indicated, our Easting is `12 5 73 548`. Look at the Easting figures along the top of the map and you'll see, from left to right, the Eastings `12 5 72 000`, `12 5 73 000`, `12 5 74 000`, `12 5 75 000` and `12 5 76 000`. Because UTM coordinates reflect actual distances in meters, we know that there are 1,000 meters (1 kilometer) between each of these major graduations; that is, 1,000 meters between 72 and 73, between 73 and 74, between 74 and 75, and between 75 and 76. Between each of these major graduations, the map is "rulered" along the edge in 10 increments of 100 meters each.

To find our Easting of `12 5 73 548`, we move along our Eastings on the top of the map to `12 5 73 000`, then continue to move east, counting 5 100-meter increments to reach an Easting of `12 5 73 500`. We then "eyeball calculate" 48 more meters, continuing our move east roughly halfway to the next 100-meter increment (halfway would be 50) to reach our Easting of `12 5 73 548`, as indicated in Figure 2. We now have our Easting; we know that we are somewhere on this south-to-north line, which has been penciled in.

To complete the process, we now move to our locate our Northing, which is `48 83 868`.

Referring again to Figure 2, look at the Northing figures on the left (or right) side of the map and you'll see, from bottom to top, the Northings `48 83 000`, `48 84 000`, and `48 85 000`. Just as with our Eastings, because UTM coordinates reflect actual distances in meters, we know that there are 1,000 meters (1 kilometer) between each of these major graduations; that is, 1,000 meters between 83 and 84, and between 84 and 85. Between each of these major graduations, the map is "rulered" along the edge in 10 increments of 100 meters each.

To find our Northing of `48 83 868`, we move up our Northings on the side of the map to `48 83 000`, then continue to move north, counting 8 100-meter increments to reach a Northing of `48 83 800`. We then "eyeball calculate" 68 more meters, continuing our move north roughly a little more than halfway to the next 100-meter increment (halfway would be 50) to reach our Northing of `48 83 868`, as indicated in Figure 2.

With our Easting and Northing in hand, we can now plot the position. A line -- which I call a "plotting line" parallel to the Easting grid lines is drawn mentally (or physically, as in Figure 2) running south-north for our Easting, and a second "plotting line" is drawn parallel to the Northing lines for our Northing. The intersection of these lines on the Figure 2 map is our coordinate, `12 5 73 548 E`, `48 83 868 N`, the summit of Hawks Rest. (Once again, note that you can physically draw in the plotting lines, or "eyeball plot" your position with imaginary lines.)

*Remember: it's important that plotting lines be drawn parallel to the UTM grid lines, not the lines bordering the edge of the map.*

Recalling that the numbers always get bigger going east and north, if you were standing at the coordinate above, then moved 10 meters east and 10 meters north, your new coordinate would be as follows:

    12 5 73 558 E
      48 83 878 N

Let's go now to the UTM-gridded map in Figure 3 for additional examples.

![McKay, Murrary, and Scotty Lakes](figures/03.jpg)

There are 3 UTM coordinates for identifiable landmarks in this exercise, as follows -- use the same sequence we just used to find the summit of Hawks Rest and plot them:

    McKay Lake
    12 7 13 332 E
      46 81 245 N

    Murray Lake
    12 7 12 492 E
      46 82 075 N

    Scotty Lake
    12 7 12 367 E
      46 79 910 N

That's UTM. It's simple, it's practical, and it's easy to work with. Is it important to remember that an Easting represents the distance in meters west to east across your zone, or that the Northing is the distance north of the Equator in meters? Not really. What *is* important is that this is how your GPS is going to provide you your position, which you can then plot with accuracy on a topographic map. And as we'll explain the "GPS" section of the essay, UTM also works in reverse: you'll be able to plot a UTM coordinate from your topo, tap it into your GPS, and let it and your compass take you there.

The key here -- and you will hear it again -- is to *practice*: the more you use UTM coordinates in practice map plotting, the more readily, quickly, and accurately you'll be able to do it when you really need it.

Remember:

 * The numbers always get bigger as you go east, and they always get bigger as you go north. Always.
 * Everything is east and north, or, if you prefer, right and up.
 * Every square meter has -- indeed, is -- its own coordinate.
 * It's important that plotting lines be drawn parallel to the UTM grid lines, not the lines bordering the edge of the map.

## Topographic Maps

Though in terms of quality there are none better on earth, the "store-bought" USGS topos have their drawbacks. The maps themselves are large and can be difficult to handle in field conditions, especially when you're trying to do grid plots or compass triangulations / resections; there just aren't many good writing/work surfaces available at 9,000 feet. And before you can do any plotting or serious triangulations / resections, you have to grid the maps by hand, using either the Latitude-Longitude (Lat-Lon) or Universal Transverse Mercator (UTM) tick marks [Figures 4 and 5]. ("Store-boughts" are not UTM-gridded and "rulered" like the maps you used in figures 1 through 3; these were generated by a special topographic map program called Terrain Navigator that we'll be discussing soon.)

Figure 4 is the northwest corner of the 7 1/2" Dundee Meadows (Wyoming) topo.

![Dundee Meadows](figures/04.jpg)

As indicated, the northwest corner of the map is a precise Lat-Lon coordinate, 43 degrees, 52 minutes, 30 seconds north latitude, 110 degrees west longitude. Also indicated are several of that particular topo's tick marks; the zone 12 Easting tick marks `5 81 000`, `5 82 000`, and `5 83 000` can be made out along the top of the map, as can the Northing tick marks `48 57 000` and `48 58 000` along the left-hand edge. One of the corner's Lat-Lon tick marks can also be seen along the top of the map; the tick for the longitude 109 degrees, 57 minutes, 30 seconds, shorthanded to read 57' 30".

These are the marks that are used to hand-grid -- using a pencil and straight edge -- a standard "store-bought" topographic map. If you're using Lat-Lon, you must connect the Lat-Lon tick marks; if employing UTM, the UTM tick marks must be used to create a grid, as shown in Figure 5.

![Connected UTM Tick Marks](figures/05.jpg)

Then, with that accomplished, a Lat-Lon scale or ruler or UTM corner scale [Figure 6] is necessary to plot a coordinate, depending on which grid system you're using.

![Ruler and Corner Scale](figures/06.jpg)

Here the UTM grid/UTM corner scale approach is much the superior of the two; the Lat-Lon/Lat-Lon ruler approach is more complex and vulnerable to mistakes. Figure 6 features a combination Lat-Lon ruler and scale and UTM scale manufactured by Brunton and the long-standard U.S. military issue map protractor with its UTM corner scales.

There are other problems with "store-bought" topos, not the least of which is that areas you seem to need most are often near the edges, compelling you to butt two, three, or even four maps together with transparent tape, creating a real nightmare.

The solution to just about every problem involving standard "store-bought" topographic maps can be found in what I consider to be the best mapping software program available, MapTech's Terrain Navigator.[^1] As outlined below, Terrain Navigator mapping software deals with all the issues very handily.

Terrain Navigator features every 7 1/2"-1:24,000 USGS and 1:100,000-scale map in the United States outside of Hawaii (plus all the 1:63,360 and 1:250,000 Alaskan topos) on CD, packaged state by state. Available through dealers and directly from [MapTech](http://www.maptech.com). The state-by-state packages sell for about $99.95 per state, except for Maine, New Hampshire, Vermont, Massachusetts, Rhode Island, and Connecticut, which are bundled into one package, and New Jersey, Delaware, Maryland, and Washington DC, which are bundled into another. (Bear in mind that for your hundred bucks you're getting every 1:24,000 and 1:100,000 topo for the entire state or region you choose in the lower 48 or every 1:63,360 and 1:250,00 map for Alaska, including Terrain Navigator's numerous features, which will be described shortly.)

Once you have Terrain Navigator for whatever state or states you hunt, you can start "rolling your own" maps. Any decent color inkjet or color laser printer will do; in fact, the color inkjet printers produce a somewhat higher quality map.

MapTech's website offers a unique feature. At no charge, you can download a full-featured demo of Terrain Navigator, which includes a single USGS 7 1/2" topographic map, one of the Colorado quads. Once you've read through the "Map Problems, Map Solutions" section, which follows next, you might want to print it out, then download the Terrain Navigator demo to get a hands-on feel for things.

## Map Problems, Map Solutions

### Map Problem: Due to its size, the 7 1/2" topo can be unwieldy to carry in the field.

Terrain Navigator Solution: Just select the area you want on the 1:24,000 scale map (1:1 zoom ratio) and print it out at a rate of 48% on a sheet of 8" x 11 (letter size) paper, using either plain paper or special water-resistant paper such as that made by outfits like Rite-in-the-Rain. The result is a map covering virtually the same area of the standard 7 1/2" 1:24,000 topo, normally about 27" x 22," reduced in size to a sheet of typing paper readily folded and slid into a shirt pocket. (For the Alaskan 1:63,360 scale topo, just select your area and print at a rate of 126.72%.) You also have the option of Portrait or Landscape format -- your choice, depending on your needs for the particular area.

### Map Problem: The standard "store-bought" 7 1/2" topo must be gridded by hand to plot coordinates; in addition, a plotting protractor or other device must be used in order to plot a coordinate with any degree of precision.

Terrain Navigator Solution: When you're setting up your map to be printed out at a rate of 48%, the option to UTM-grid the map is selected. The final printed-out 8" x 11 map comes out gridded and "rulered" along the edges in 100-meter increments, enabling you to accurately plot your position without the use of a protractor or similar device. (Refer to the maps and exercises you used in figures 1 through 3.) As a built-in plus, the grid and "rulered" edges also provide a distance scale in meters and kilometers covering the entire map.

In yet another plus, using the 48% printout setting on the 1:24,000 scale topo on Terrain Navigator produces a map gridded at exactly the standard military scale of 1:50,000, enabling the optional use of a 1:50,000 UTM corner scale for even greater precision. (For the Alaskan 1:63,360 topos, just select your area, select the UTM-grid option, then print at the rate of 126.72%, which will result in a UTM-gridded 1:50,000-scale mape, enableing the use of a 1:50,000 corner scale, if so desired.)

(The optional use of the UTM corner scale -- especially the one built into the Brunton Combi compass -- will be covered in the compass section of the essay.)

### Map Problem: Due, once again, to its size, it is difficult to spread out a standard 7" topo and plot a position as provided by a GPS.

Terrain Navigator Solution: With the letter-sized, UTM-gridded map produced by Terrain Navigator, plotting a position from a GPS-supplied coordinate involves nothing more than opening the map and "eyeball calculating" the UTM coordinate as supplied by your GPS. This is feasible because the map is already gridded and "rulered" along the edges in 100-meter increments. (Refer again to maps and exercises used in figures 1 through 3.)

This process works equally well in reverse. A location of interest -- a small meadow, say, or a timbered bench -- is identified on your topographic map. In the field, accurately determining its coordinate on a "store-bought" 7 1/2" topo can be challenging. With our letter-sized, UTM-gridded map produced by Terrain Navigator, however, determining the coordinate is easy because our compact map is already UTM-gridded and "rulered" along the edges in 100-meter increments.

In Figure 7 two small meadows are circled and marked.

![Marked Meadows](figures/07.jpg)

Take the westernmost meadow first and calculate its Easting by drawing an imaginary (or real) plotting line from it down to the "rulered" bottom of the map -- this will give you an "eyeball calculation" Easting of about `12 5 74 800`. Now draw your imaginary or real plotting line from the meadow to the right to the "rulered" right-hand side of the map to determine your Northing -- about `48 81 550`. Now you have a complete UTM coordinate for the meadow: `12 5 74 800 E`, `48 81 550 N`.

Use the same process for the easternmost meadow, and you'll find its UTM "eyeball calculated" coordinate to be `12 5 76 150 E`, `48 82 300 N`. (Remember, it's important that plotting lines be drawn parallel to the UTM grid lines, not the lines bordering the edge of the map.)

### Map Problem: Marking and/or penciling standard topographic maps -- and/or performing compass triangulations -- is difficult under field conditions due to map size and lack of any sort of writing surface. When handling a compass triangulation, another problem often arises when the landmark or object that is being used for the triangulation is distant and requires an impractically-long straightedge to draw the line of bearing on the map.

Terrain Navigator Solution: The map size problem is solved by the UTM-gridded 8" x 11 map. The writing surface problem is solved by packing along a compact Saunders memo-size clipboard. (Dimensions app. 6"x9," weight about 5 ozs., cost less than $2.00) The need for a long straightedge to handle compass triangulations is eliminated by the map's small size -- the edge of a small map protractor serves perfectly (the standard military issue is ideal) or the baseplate of the Brunton Combi compass works equally well. And the UTM gridlines provide beautiful right angles, handy for compass triangulations / resections. (Some feel that GPS eliminates the need for compass triangulations in order to plot a position -- plus it isn't usually workable at night and the topography doesn't always cooperate -- but it's a skill that jumps into sharp focus if your GPS suddenly becomes a casualty. I very much recommend knowing how to do triangulations / resections as a backup at the very least; we'll cover them in the "Compass" section of the essay.

![A Saunders memo-size clipboard with a Brunton Combi Compass and Leatherman Wave Tool, included for scale. A clipboard -- even a miniature one that weighs only 5 ounces -- usually doesn't make anybody's backpack-hunting list, but it can be handier than an extra pocket and does double duty in many ways around the Tipi, especially in the camp kitchen](figures/08.jpg)

### Map Problem: For some perverse reason, the areas on a standard topo map the hunter needs most are often near the edges, compelling him to butt multiple adjoining maps together with transparent tape, which is a real headache.

Terrain Navigator Solution: Terrain Navigator's "Seamless Mode," in which the map boundaries are defined by the user. When creating the UTM-gridded 8"x11" map, you simply select the "Seamless Mode," which eliminates the standard "store-bought" topographic map boundaries. Select the area you want, then print out the map at the UTM-gridded 48% rate previously described. In the "Seamless Mode," the program ignores the standard map's borders and provides its own.

![The map's southeast corner is southeast of Deep Lake](figures/09.jpg)

![Terrain Navigator "Seamless Mode" enabled you to butt two, three or even four maps together, printing out a UTM-gridded, "rulered" topo combining areas of all.](figures/10.jpg)

### Map Problem: In the field, maps get soaked, torn, otherwise rendered unusable, or even lost.

Terrain Navigator Solution: Print out two or three copies of each map you'll need for your hunt and leave the copy or copies in camp, ready to replace any that are damaged or lost. Cost: a few sheets of paper and some printer ink.

## Other Terrain Navigator Features and Advantages

 * Find maps and place names quickly; if the place name of a creek, mountain, river, etc., appears on the USGS map, then Terrain Navigator's search mode will find it. It will also find the location of any coordinate that you tap into it.
 * As you move the cursor over the Terrain Navigator map, it's providing grid coordinates and altitude in whatever system you've chosen.
 * Terrain Navigator's maps can be viewed in either a conventional 2-D or 3-D mode.
 * "Waypoints" and "Landmarks" (depending on which brand of GPS you're using) can be transferred manually or electronically from Terrain Navigator to your GPS and vice versa.
 * Terrain Navigator calculates and displays distances, lines of sight, terrain profiles and other data almost instantly.

## Map Datum

One more very important factor in working with Terrain Navigator (and later, when we get to the "GPS" section in the essay) concerns a thing called Map Datum. Though the Map Datum issue will start out sounding complicated, it's something that is dealt with very quickly and simply.

Map Datums are of tremendous importance in surveying and mapmaking -- they are the system or model that was used by the surveyor to relate the actual location of ground features to coordinates and locations on the map or system of maps.

![Every USGS store-bought topo map identifies its Map Datum, usually near the lower left-hand corner of the topo.](figures/11.jpg)

Your GPS will offer up a very long list of options under "Map Datum." *What's important here is that the Map Datum option you select for your GPS matches the Map Datum on the map -- the individual topo -- that you're working with*. New GPSs come from the factory defaulted to WGS 84 (World Geodetic System 1984), but because virtually every "store bought" USGS topo for the United States uses the NAD 27 Map Datum -- I've yet to encounter one that doesn't -- select NAD 27 (North American Datum 1927) if you're using these off-the-shelf maps. (As it happens, you can double-check. Every USGS store-bought topo map identifies its Map Datum, usually near the lower left-hand corner of the topo, as shown in the 7 1/2" topo in Figure 11.)

If your GPS offers different breakdowns of NAD 27, choose NAD 27 CONUS (North American Datum 1927 Continental United Sates) if you're in the lower 48 and, if you're in Alaska, select NAD 27 ALASKA. (If you're in Alaska but your GPS doesn't offer the NAD 27 ALASKA option, just stick with NAD 27.)

In any event, you can always double-check the Map Datum for your particular "store bought" topo. Every USGS topo map identifies its Map Datum, usually near the lower left-hand corner of the sheet.

In Canada, the situation is a bit more complicated, as the Centre for Topographic Information's National Topographic System is currently revising all existing Canadian topographic maps (1:50,000 and 1:250,000 scale) from NAD 27 to NAD 83 (North American Datum 1983), which, for all intents and purposes, is identical to WGS 84. The principle is the same: always check the map you're using and make sure its Map Datum is matched by the Map Datum setting for your GPS.

If you opt to use MapTech Terrain Navigator, you'll find that you can set the program's Map Datum for NAD 27, WGS 84, or NAD 83. *Again, it's important that everything matches*. If your GPS is set for NAD 27, select NAD 27 in Terrain Navigator. If you're running WGS 84 on your GPS, choose WGS 84 in Terrain Navigator. (The same thing applies to NAD 83). The importance is this: if your GPS Map Datum settings don't match those for the map you're using, you could end up being off by hundreds of yards.

[^1]: *Editor's Note*: All of the features which the author discusses are available online via [CalTopo](http://caltopo.com/). CalTopo is an excellent mapping service which the editor strongly recommends.
