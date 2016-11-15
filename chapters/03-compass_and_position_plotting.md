# Compass and Position Plotting

We've covered compass work for direction finding; now we'll move on to compass and position plotting.

Now, I'll be the first to admit that position plotting with map and compass comes in second to position plotting with a GPS. It's slower and it doesn't work when you can't see your landmarks -- darkness, fog, thick rain, snow, etc. -- but GPSs crash, batteries run dry, or maybe you left yours behind or just don't have one yet. In any event, position plotting with a compass is a useful backup skill and one that should be learned and practiced.

## Triangulation / Resection

Whether it involves GPS, compass, or both, map work -- including position plotting -- is grounded on transferring information from the real world to the map, and from the map to the real world.

The process of taking bearings from objects in the real world and transferring them to the map in order to determine position -- position plotting -- is called "triangulation" in the civilian world and "resection" by the military. For simplicity's sake, we'll use the combination phrase "Triangulation/Resection."

The Triangulation/Resection process is pretty much a universal and instructions follow. The primary difference in the process among our three recommended compasses -- the British prismatics, the military M27 lensatic, and the Brunton Combi -- is the in the mechanics of taking the bearings and we'll cover each individually.

As we've done before, let's move straight to an example, beginning with the map in Figure 35, which covers a section of the upper Green River country in Wyoming.

![A Section of the Upper Green River](figures/35.jpg)

We're on the Highline Trail along the Green River. To the southwest and southeast are Squaretop Mountain and Granite Peak, both distinctive landmarks from which we'll take our bearings. Squaretop is very large and very broad; it will be best to use one of its more distinctive features for our first bearing -- the promontory on its northwest quadrant indicated by the arrow. We take a bearing on the promontory -- it's 231 degrees magnetic. (Remember that the bearings taken with our three recommended compasses will always be magnetic, as they are "magnetic only" compasses, not adjustable for declination.) Our second bearing we take on the summit of Granite Peak, also indicated by an arrow -- it's 134 degrees magnetic.

Our two bearings -- 231 degrees from the promontory on Squaretop and 134 degrees from the summit of Granite Peak -- are magnetic, real-world bearings. In order to transfer them to our map, we must first convert them to grid bearings, as our map is UTM-gridded for Grid North.

This is where declination comes into play. Before leaving town we checked [TopoZone](http://www.topozone.com) to determine the declination in the Upper Green River country, which TopoZone tells us is 12.955 degrees east, true to magnetic, with grid declination being .829 degrees east of True North. As always, what we're after is our grid-to-magnetic declination, so in this instance we subtract the true-to-grid declination of .829 degrees from the true-to-magnetic declination of 12.955 degrees for a grid-to-magnetic declination of 12.126 degrees east, rounded off to a simplified figure of 12 degrees east. (Always round off to the nearest whole number.)

*12 degrees east*. Once you've calculated it, that's the bottom-line declination figure for your entire trip (in this instance, into the Upper Green River country) and all you need remember in terms of declination.

On to converting our magnetic bearings to grid north bearings. It works like this:

If your declination is east -- in other words, if you're anywhere west of the agonic line, basically the entire western United States or Alaska -- *you add your declination going from magnetic to grid, and subtract it if you're going from grid to magnetic*. In this instance, then, we add 12 degrees to our magnetic bearings to obtain their grid bearings: the bearing from the promontory on Squaretop becomes 243 degrees grid (231 + 12) and the bearing from Granite Peak becomes 146 degrees grid (134 + 12).

As a hypothetical for discussion's sake, let's assume for a moment that everything we've described is happening somewhere in the Atlantic region, in an area of west declination. Here the opposite is true, *you subtract your declination going from magnetic to grid, and add it if you're going from grid to magnetic*.

There's a memory crutch to help you keep this all straight. (In fact, there are quite a few, but this one has always worked for me.)

First, keep in mind that True North and Grid North are very close to being the same, and for the sake of this memory crutch, we refer to them jointly as "True-Grid."

Here goes:

* In the west, True-Grid is valued higher than Magnetism
* In the East, Magnetism is valued higher than True-Grid

This crutch, then, reminds us that out west, True-Grid is valued higher than Magnetism; hence we add when going from magnetic to grid, and subtract when going from grid to magnetic. In the east, where Magnetism is valued higher than True-Grid, we add when going from grid to magnetic, and subtract when going from magnetic to grid.

("True Grid" is a play on words for the John Wayne western *True Grit*. I know, I know. It's corny and a clear-cut case of mountain west conceit, but it works, so please cut me some slack.)

### British Prismatic or M-27 Lensatic Compass

Now that we have our grid bearings -- 243 degrees to the promontory on Squaretop and 146 degrees to Granite Peak -- we can perform a Triangulation/Resection and plot our position.

If you're using a British prismatic or military M-27 lensatic compass, a map protractor is necessary for Triangulation/Resections. There are any number of them available, but I like the standard U.S. military "Coordinate Scale and Protractor," as shown in Figure 6 of the "Map" section of the essay, or, better yet, the MapTools "Pocket Size Corner Roamer," as shown beginning with Figure 36. (The [MapTools protractor](http://www.maptools.com/products/PocketCorners.html) is very small -- 2 3/4" x 2 3/4" -- and weighs virtually nothing. It also features UTM corner scales for 1:50,000, 1:25,000, and 1:24,000 scale maps.)

If you've got a Brunton Combi, the protractor is built into the compass's design; more on that will follow.

We'll do the bearing to the promontory on Squaretop first. The first step is to place the bearing number on the edge of the protractor - in this case, 243 - on the landmark itself. (I've offset the protractor somewhat in Figure 36 for illustrative purposes.) Taking care to keep the bearing number on the landmark, the protractor is the pivoted until it is squarely aligned with the UTM grid lines on the map, as shown in Figure 36. A pencil mark is then placed in the center hole, as shown, and a straight line drawn from the landmark through the center hole, again, as shown.

![Drawing the Bearing from Squaretop](figures/36.jpg)

Next, the bearing to Granite Peak, as shown in Figure 37. Place the bearing number on the edge of the protractor -- in this case, 146 -- on the landmark itself. (I've offset the protractor somewhat for illustrative purposes.) Taking care to keep the bearing number on the landmark, the protractor is the pivoted until it is squarely aligned with the UTM grid lines on the map, as shown in Figure 37. A pencil mark is then placed in the center hole, as shown, and a straight line drawn from the landmark through the center hole, again, as shown. Your Triangulation/Resection is now complete; your position is the intersection of the two bearing lines, as indicated. (Its UTM coordinate, incidentally, is `12 05 99 053 E`, `47 87 253 N`.)

![Drawing the Bearing from Granite Peak](figures/37.jpg)

(In an ideal situation, the landmarks from which you take your bearings will be 90 degrees apart. Mother Nature isn't always so obliging; at any rate, strive to have your landmarks be no less than 45 or greater than 135 degrees apart in order to get the best possible triangulation/resection.)

The exercise in Figures 36 and 37 is a two-point Triangulation/Resection, utilizing two bearings. If you are along a real-world line of any sort clearly identified on the map -- a stream, a fenceline, or, as in this instance, a trail -- you need only perform a one-point Triangulation/Resection, taking just one bearing; the point where your single bearing line crosses your line on the map is your position. (These real-world lines -- streams, fencelines, trails, roads, etc. are often extremely useful in position plotting as well as in other aspects of back country navigation, as we will see. Usually called "baselines" in civilian parlance and "handrails" by the military, we'll use the combination phrase of "baseline/handrail.")

### Brunton Combi

As we've said, if you're using a Brunton Combi, no protractor is needed -- it's built into the compass.

Here we'll use the same grid bearings -- 243 degrees to the promontory on Squaretop and 146 degrees to Granite Peak -- to a Triangulation/Resection and plot our position.

We'll start with the bearing to the promontory on Squaretop. The first step is to set the Combi's dial to the landmark's grid bearing -- in this case, 243, as shown in Figure 38. Next place the compass's edge on the landmark, as shown, and pivot the compass, taking care to keep its edge on the landmark, until the compass's north-south grid lines are aligned with the map's north-south UTM grid lines, again, as shown. A pencil line is then drawn along this bearing.

![Drawing the Bearing from Squaretop](figures/38.jpg)

Next, the bearing to Granite Peak. Set the Combi's dial to the landmark's grid bearing -- in this case, 146, as shown in Figure 39. Next place the compass's edge on the landmark, as shown, and pivot the compass, taking care to keep its edge on the landmark, until the compass's north-south grid lines are aligned with the map's north-south UTM grid lines, again, as shown. A pencil line is then drawn along this bearing. Your Triangulation/Resection is now complete; your position is the intersection of the two bearing lines, as indicated. (Its UTM coordinate, incidentally, is `12 05 99 053 E`, `47 87 253 N`.)

![Drawing the Bearing from Granite Peak](figures/39.jpg)

The exercise in Figures 38 and 39 is a two-point Triangulation/Resection, utilizing two bearings. If you are along a real-world line of any sort clearly identified on the map -- a stream, a fenceline, or, as in this instance, a trail -- you need only perform a one-point Triangulation/Resection, taking just one bearing; the point where your single bearing line crosses your line on the map is your position.

## Combining Position Plotting with Compass Direction Finding

Let's move on to an example of a one-point Triangulation/Resection, followed by an exercise in combining position plotting with compass direction finding.

Referring to Figure 40, let's say you're moving up the trail along North Buffalo Fork in Wyoming's Teton Wilderness. (In that particular area, grid-to-magnetic declination is 13 degrees east.) Joy Peak is a clear landmark and you determine its magnetic bearing to be 177 degrees. Following our formula for converting magnetic bearings to grid bearings in areas of east declination, we add the 13 degrees to arrive at a grid bearing of 190 and draw it in with a protractor or Brunton Combi compass as shown, as we did in our Highline Trail example . A one-point Triangulation/Resection results, giving you your position as indicated in Figures 40 and 41, with the trail serving as your baseline/handrail. (The "eyeball" UTM coordinate for which is `12 05 66 840 E`, `48 69 900 N`; the point where the line of bearing from Joy Peak strikes the trail.)

![North Buffalo Fork](figures/40.jpg)

![Position Along North Buffalo Fork](figures/41.jpg)

Now that you've plotted your position, you want to make the climb to Toppan Lake and need to determine a course. Start by tracing a line -- which will become your course -- on the map from your plotted position to Toppan Lake, as shown in Figure 42.

![Plotting a Course to Toppan Lake](figures/42.jpg)

Using either a protractor (as shown in Figure 43) or your Combi compass (Figure 44), you can now determine the grid north course from your position along the trail to Toppan Lake.

![Determing the Grid North Course with a Protractor](figures/43.jpg)

![Determing the Grid North Course with a Combi](figures/44.jpg)

To use a protractor in this application, place its center hole squarely over your position, then, keeping the center hole positioned there, turn the protractor carefully until it is squarely aligned with the UTM grid lines on the map. You can then read your grid north course along the edge of the protractor where your course line strikes it which, in this case, is 167.

To obtain your grid north course with a Brunton Combi compass, place the edge of the compass along the course line you've drawn in from your position on the trail to Toppan Lake. Then, keeping the edge of the compass carefully aligned with your course line, turn the compass dial until the compass's north-south grid lines are aligned with the map's north-south UTM grid lines, as shown. The reading on the compass dial is your course; in this case, 167.

The next step will be to convert this grid course to a magnetic course so that you can put it on our non-declination adjustable compass. Now - once again following the formula in areas of east declination - we subtract the 13 degrees difference because we're going from true-grid (the map) to magnetic (our non-declination adjustable compass). This results in a magnetic course of 154 degrees, which you then put on your compass and head out. (After studying your line of travel on your map, of course.)

## Taking Bearings

### British Prismatic

British prismatics are fitted with a sighting wire engraved in a glass panel in the lid, which is raised to a 90-degree angle for taking bearings. Bearings are taken by sighting through a focus-adjustable 24x prismatic rear sight, as shown in Figure 45. (Provided courtesy of Pyser-SGI. Note that the sketch provided by Pyser depicts a prismatic graduated in mils, not degrees.)

![Taking a Bearing with a British Prismatic](figures/45.jpg)

A bearing is taken as shown. As always with any compass, it must be held level during use. With the rear sight brought directly up to the eye, look through the sight's sighting slit and align the hairline sighting wire on the object on which the bearing will be taken. The compass card will be visible at the same time through the 24x back sight prism. The bearing can then be read against the hairline sighting wire down to half a degree or even a quarter of a degree under ideal conditions.

Because of its unique design features and tritium illumination, the British prismatic permits bearings to be taken regardless of light conditions. Simply put, if you can see a landmark, you can obtain an extremely accurate bearing, day or night.

### M27 Lensatic

Like its British cousins, the U.S. military M27 lensatic is fitted with a sighting wire in the lid, which is raised to an approximate 90-degree angle for taking bearings. (See Figures 46 and 47, sourced from U.S. Military Field Manual 3-25.26, Map Reading and Land Navigation.)

![Taking a Bearing with an M27 Lensatic](figures/46.jpg)

![M27 Lensatic Manual](figures/47.jpg)

Fold the back sight down slightly and bring the compass up to the eye, as indicated. Sight down through the lensatic back sight, pushing forward on the sight with your eye until the image of the compass dial comes into focus. Look through the now-focused lensatic back sight and align the sighting wire on the object on which the bearing will be taken. The compass card will be visible at the same time through the magnifying lensatic back sight. The bearing can then be read against the black index line on the glass compass dial. (The M27 is graduated in both degrees and mils.) The degrees on the compass card are in five-degree graduations; individual degrees must be "eyeball-estimated."

Taking bearings in bad light or darkness is possible with an M-27, though the process simply doesn't work as well as when using a British prismatic.

### Brunton Combi

To take a bearing with a Brunton Combi, first set the compass dial on "North." Note the position of the back sight prism on the compass dial, as indicated in Figure 48, and raise the compass to the eye, sighting into the back sight prism as shown in Figure 49. (Figure 49 is from the Brunton website at www.brunton.com.) Keeping both eyes open, turn until the item the bearing will be taken on is atop the index line visible through the prismatic back sight, as shown in Figure 49. The large number on the bottom of the dial in alignment with the index line is the magnetic bearing to the object (and is the bearing you'll be dealing with); the smaller number on the top of the dial is the bearing from the object. The bearing is easily read in single degrees and down to half a degree under ideal conditions.

![Back Sight Prism on the Brunton Combi](figures/48.jpg)

![Taking a Bearing with a Brunton Combi](figures/49.jpg)

Like the British prismatics, accurate bearings can be taken with a Brunton Omni even in darkness, provided that a landmark is visible and identifiable and you give the compass a good "flashlight shot" before taking your bearing.
