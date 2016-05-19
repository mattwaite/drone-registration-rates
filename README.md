#Drones per capita

This is a quick joining of the FAA's recently released drone registrations by zip code data and Census Zip Code Tabulation Area data to calculate a per capita rate. Saying a zip code in a large city has more than a zip code in a rural place doesn't tell you anything more than more people live in one place over another. To compare a big place to a small place, you need to calculate a rate. To do that, you need population. So that's what I've done. Warning: It's pretty noisy. There are two places in the US where the Census Bureau reports 1 person living and the FAA reports 1 drone being registered -- a zip code in Oakville, N.Y. and Pullman, Wash. That doesn't pass the smell test for me -- something's wrong in the data. 

But if you filter out zip codes of less than 100 people, you get more interesting answers. Here's the top 10 larger zip codes by per capita rate:

City|State|Postal Code|Number of Registrations|Population|drone_rate
----|-----|-----------|-----------------------|----------|----------San Francisco|CA|94104|13|223|5829.596413Como|CO|80432|4|104|3846.153846Dameron|MD|20628|4|133|3007.518797Millbrook|IL|60536|3|111|2702.702703Southmayd|TX|76268|5|186|2688.172043Concan|TX|78838|4|149|2684.563758Little Deer Isle|ME|4650|4|151|2649.006623Brandamore|PA|19316|3|116|2586.206897melrose|MT|59743|3|123|2439.02439Berlin|ND|58415|3|123|2439.02439

The data for both all zip codes and larger zip codes is in this repository and is yours to use as you see fit.