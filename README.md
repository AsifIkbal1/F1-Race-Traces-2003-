# F1-Race-Traces-2003-
F1 Race Traces — 2003 🏁
# Formula One Race Traces — 2003

This notebook shows race traces for each F1 race in 2003, using the [Formula 1 Race Data][2] data set, which is sourced from [ergast.com](http://ergast.com/mrd/),
and the [Formula 1 Race Events dataset](https://www.kaggle.com/jtrotman/formula-1-race-events) using data from Wikipedia.

A race trace is a way to visualise the progress of an entire Grand Prix, they show gaps between cars and general field spread, as well as the relative pace of each car throughout the race (as line gradient).
The traces are calculated from cumulative race lap times, adjusted by the median lap time at that point in the race.
You can think of the horizontal zero line as a *virtual reference car* doing the average lap time of the field, lines above are faster and lower are slower.

- Line **colours** for each driver are based on general team colours.
- **Fastest lap** is marked with a ★
- **Safety car** affected laps are highlighted in yellow - gaps between cars shrink.
- **[Virtual safety cars][1]** were introduced in 2015 and force all cars to slow - this causes the lines to spread out temporarily as the leaders have completed more of the first affected lap at racing speeds (some now highlighted in orange).
- Laps where a car went via the **pit lane** are marked with a &#9679; (for years with pit-stop data: 2012 onwards).
- **Overtakes** are visible where the lines cross, often due to pit-stops.
- Truncated lines indicate **retirement** from the race.

A **shadow** at the bottom shows which cars have have been lapped by the lead car, this helps to see some effects:
 - Leaders will often make a pit-stop to *avoid* slower traffic ahead.
 - The backmarkers must allow leading cars through - the edge of the shadow shows *why* their lines suddenly dip.
 - Leaders may ease off to let a lapped car through at the end of a race.

*Note:* good safety car data is hard to find! The data scraped from Wikipedia appears to have a few mistakes; the 
virtual safety car highlights are my estimates, using the lap-time data.

*Tip:* to see better resolution, &lt;*Right click*&gt; &rarr; *Open Image in New Tab*.


## Revisions

<pre>
V2: moved legends to bottom to allow more width
V3: added constructors championship plot and driver/team table links
V4: add origin to championship traces & link for 2021
V5: add fastest lap marker
V6: added laps per position and top drivers chart
V7: safety car, red flag & lapped cars highlighting
</pre>


## All F1 Race Traces

There is a notebook for every year that has lap-time data:

[1996](https://www.kaggle.com/code/jtrotman/f1-race-traces-1996), 
[1997](https://www.kaggle.com/code/jtrotman/f1-race-traces-1997), 
[1998](https://www.kaggle.com/code/jtrotman/f1-race-traces-1998), 
[1999](https://www.kaggle.com/code/jtrotman/f1-race-traces-1999), 
[2000](https://www.kaggle.com/code/jtrotman/f1-race-traces-2000), 
[2001](https://www.kaggle.com/code/jtrotman/f1-race-traces-2001), 
[2002](https://www.kaggle.com/code/jtrotman/f1-race-traces-2002), 
[2003](https://www.kaggle.com/code/jtrotman/f1-race-traces-2003), 
[2004](https://www.kaggle.com/code/jtrotman/f1-race-traces-2004), 
[2005](https://www.kaggle.com/code/jtrotman/f1-race-traces-2005), 
[2006](https://www.kaggle.com/code/jtrotman/f1-race-traces-2006), 
[2007](https://www.kaggle.com/code/jtrotman/f1-race-traces-2007), 
[2008](https://www.kaggle.com/code/jtrotman/f1-race-traces-2008), 
[2009](https://www.kaggle.com/code/jtrotman/f1-race-traces-2009), 
[2010](https://www.kaggle.com/code/jtrotman/f1-race-traces-2010), 
[2011](https://www.kaggle.com/code/jtrotman/f1-race-traces-2011), 
[2012](https://www.kaggle.com/code/jtrotman/f1-race-traces-2012), 
[2013](https://www.kaggle.com/code/jtrotman/f1-race-traces-2013), 
[2014](https://www.kaggle.com/code/jtrotman/f1-race-traces-2014), 
[2015](https://www.kaggle.com/code/jtrotman/f1-race-traces-2015), 
[2016](https://www.kaggle.com/code/jtrotman/f1-race-traces-2016), 
[2017](https://www.kaggle.com/code/jtrotman/f1-race-traces-2017), 
[2018](https://www.kaggle.com/code/jtrotman/f1-race-traces-2018), 
[2019](https://www.kaggle.com/code/jtrotman/f1-race-traces-2019), 
[2020](https://www.kaggle.com/code/jtrotman/f1-race-traces-2020), 
[2021](https://www.kaggle.com/code/jtrotman/f1-race-traces-2021),
[2022](https://www.kaggle.com/code/jtrotman/f1-race-traces-2022).

 [1]: https://en.wikipedia.org/wiki/Safety_car#Virtual_safety_car_(VSC)
 [2]: https://www.kaggle.com/cjgdev/formula-1-race-data-19502017
 [3]: https://www.kaggle.com/jtrotman/formula-1-race-events
--------------------------------------------------------------------------------------------------------------------
# Formula One Race Traces — 2003

This notebook shows race traces for each F1 race in 2003, using the [Formula 1 Race Data][2] data set, which is sourced from [ergast.com](http://ergast.com/mrd/),
and the [Formula 1 Race Events dataset](https://www.kaggle.com/jtrotman/formula-1-race-events) using data from Wikipedia.

A race trace is a way to visualise the progress of an entire Grand Prix, they show gaps between cars and general field spread, as well as the relative pace of each car throughout the race (as line gradient).
The traces are calculated from cumulative race lap times, adjusted by the median lap time at that point in the race.
You can think of the horizontal zero line as a *virtual reference car* doing the average lap time of the field, lines above are faster and lower are slower.

- Line **colours** for each driver are based on general team colours.
- **Fastest lap** is marked with a ★
- **Safety car** affected laps are highlighted in yellow - gaps between cars shrink.
- **[Virtual safety cars][1]** were introduced in 2015 and force all cars to slow - this causes the lines to spread out temporarily as the leaders have completed more of the first affected lap at racing speeds (some now highlighted in orange).
- Laps where a car went via the **pit lane** are marked with a &#9679; (for years with pit-stop data: 2012 onwards).
- **Overtakes** are visible where the lines cross, often due to pit-stops.
- Truncated lines indicate **retirement** from the race.

A **shadow** at the bottom shows which cars have have been lapped by the lead car, this helps to see some effects:
 - Leaders will often make a pit-stop to *avoid* slower traffic ahead.
 - The backmarkers must allow leading cars through - the edge of the shadow shows *why* their lines suddenly dip.
 - Leaders may ease off to let a lapped car through at the end of a race.

*Note:* good safety car data is hard to find! The data scraped from Wikipedia appears to have a few mistakes; the 
virtual safety car highlights are my estimates, using the lap-time data.

*Tip:* to see better resolution, &lt;*Right click*&gt; &rarr; *Open Image in New Tab*.


## Revisions

<pre>
V2: moved legends to bottom to allow more width
V3: added constructors championship plot and driver/team table links
V4: add origin to championship traces & link for 2021
V5: add fastest lap marker
V6: added laps per position and top drivers chart
V7: safety car, red flag & lapped cars highlighting
</pre>


## All F1 Race Traces

There is a notebook for every year that has lap-time data:

[1996](https://www.kaggle.com/code/jtrotman/f1-race-traces-1996), 
[1997](https://www.kaggle.com/code/jtrotman/f1-race-traces-1997), 
[1998](https://www.kaggle.com/code/jtrotman/f1-race-traces-1998), 
[1999](https://www.kaggle.com/code/jtrotman/f1-race-traces-1999), 
[2000](https://www.kaggle.com/code/jtrotman/f1-race-traces-2000), 
[2001](https://www.kaggle.com/code/jtrotman/f1-race-traces-2001), 
[2002](https://www.kaggle.com/code/jtrotman/f1-race-traces-2002), 
[2003](https://www.kaggle.com/code/jtrotman/f1-race-traces-2003), 
[2004](https://www.kaggle.com/code/jtrotman/f1-race-traces-2004), 
[2005](https://www.kaggle.com/code/jtrotman/f1-race-traces-2005), 
[2006](https://www.kaggle.com/code/jtrotman/f1-race-traces-2006), 
[2007](https://www.kaggle.com/code/jtrotman/f1-race-traces-2007), 
[2008](https://www.kaggle.com/code/jtrotman/f1-race-traces-2008), 
[2009](https://www.kaggle.com/code/jtrotman/f1-race-traces-2009), 
[2010](https://www.kaggle.com/code/jtrotman/f1-race-traces-2010), 
[2011](https://www.kaggle.com/code/jtrotman/f1-race-traces-2011), 
[2012](https://www.kaggle.com/code/jtrotman/f1-race-traces-2012), 
[2013](https://www.kaggle.com/code/jtrotman/f1-race-traces-2013), 
[2014](https://www.kaggle.com/code/jtrotman/f1-race-traces-2014), 
[2015](https://www.kaggle.com/code/jtrotman/f1-race-traces-2015), 
[2016](https://www.kaggle.com/code/jtrotman/f1-race-traces-2016), 
[2017](https://www.kaggle.com/code/jtrotman/f1-race-traces-2017), 
[2018](https://www.kaggle.com/code/jtrotman/f1-race-traces-2018), 
[2019](https://www.kaggle.com/code/jtrotman/f1-race-traces-2019), 
[2020](https://www.kaggle.com/code/jtrotman/f1-race-traces-2020), 
[2021](https://www.kaggle.com/code/jtrotman/f1-race-traces-2021),
[2022](https://www.kaggle.com/code/jtrotman/f1-race-traces-2022).

 [1]: https://en.wikipedia.org/wiki/Safety_car#Virtual_safety_car_(VSC)
 [2]: https://www.kaggle.com/cjgdev/formula-1-race-data-19502017
 [3]: https://www.kaggle.com/jtrotman/formula-1-race-events


