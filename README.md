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

Here is what I found:</br>
![ACREAGE_DESCRIBE](https://user-images.githubusercontent.com/62908910/148655141-54ca7857-020a-435b-b9ce-031a94574cc8.PNG)</br>
The acreage distribution has a standard deviation of 9, which is pretty high. Also someone bought 150 acres of land. That is nuts!</br>
![Future_Land_Use_Acreage_bins](https://user-images.githubusercontent.com/62908910/148655154-dd96c9f3-48f2-4d05-83da-20347758aa56.PNG)</br>
We see that those are outliers. Most of the acres sectioned out is up to 10 acres</br>
![Land_Use_Acreage_Frequency](https://user-images.githubusercontent.com/62908910/148655162-5f699501-1bf0-4227-b059-ae3c80018c22.PNG)</br>
Narrowing it down even further we see that there are mostly up to 4 acres of land</br>
![Land_Use_Code_Distribution](https://user-images.githubusercontent.com/62908910/148655175-d165d322-ed85-4596-933e-6977dc3b41d4.PNG)</br>
This is the land use code distribution. We see that most of the Land Use Codes full under single family homes “SF-LOW” and “SF-VL”</br>

![Land_Use_Code_Value_Counts](https://user-images.githubusercontent.com/62908910/148655191-fd11a29f-d27d-4695-8153-a77336baf487.PNG)</br>


Doing a quick value count shows us that 800 codes are for single family homes. Very few multifamily homes are being built. This would make sense if it was a place to go retire to with your own home.

So what does this data tell us? It says that there is land sectioned out for the purposes of construction mostly for single family homes and a handful of other home types.

Future Work: The Location data can pinpoint zip codes to buy land around or in. I could cluster together where there are many proposed constructions and find where there are land parcels that can be bought.
