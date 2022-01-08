# FL_Saratoga_Analysis
A breif analysis of Saratoga, Florida data
Future Land Use — Analyzing Saratoga, FL

I heard from friends that Florida is a hotspot for real estate. I typed into Google “Florida Real Estate” and this article popped up from Yahoo Finance.

https://finance.yahoo.com/video/florida-dominates-hottest-real-estate-200737522.html

It seems Saratoga is a retirement haven and may be a place where old folks with nest eggs will set up shop with beautiful and quiet scenery.

I found future land use data for Saratoga county here:

https://data-sarasota.opendata.arcgis.com/datasets/future-land-use-view-only/explore?location=27.341159%2C-82.533813%2C13.20

I was curious what this data had to offer. There were many columns that I could not make sense of such as the location data which I assume is integrated with their GIS software.

I only took the columns “ACREAGE”, “LANDUSECODE” since they were the most sensible out the data.

Here is what I found:
The acreage distribution has a standard deviation of 9, which is pretty high. Also someone bought 150 acres of land. That is nuts!
We see that those are outliers. Most of the acres sectioned out is up to 10 acres
Narrowing it down even further we see that there are mostly up to 4 acres of land
This is the land use code distribution. We see that most of the Land Use Codes full under single family homes “SF-LOW” and “SF-VL”
Doing a quick value count shows us that 800 codes are for single family homes. Very few multifamily homes are being built. This would make sense if it was a place to go retire to with your own home.

So what does this data tell us? It says that there is land sectioned out for the purposes of construction mostly for single family homes and a handful of other home types.

Future Work: The Location data can pinpoint zip codes to buy land around or in. I could cluster together where there are many proposed constructions and find where there are land parcels that can be bought.
