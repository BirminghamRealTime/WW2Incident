# Possible Analytical Ideas

Existing graphs here:-
* http://dmtlab.bcu.ac.uk/BIRT/visuals/may15.html
* http://dmtlab.bcu.ac.uk/BIRT/visuals/may16.html

*Did we know anything that Google didnt*

## Speed Data Geographic Analysis
### *Aims*
* To try and provide some geographical focus to the existing speed data
* Demonstrate speed of propagation of congestion around the network and potentially speed of improvement at the end. (I’ve already got a visualisation for this in mind)
* Reasons behind the fluctuations in the initial few hours
* 95% of scoot loops don't report data between 09:30 and 12:30 on 15th

### *Assumptions*
* This analysis just uses the SCOOT sensors that have been georeferenced on open streetmap (about 300). It therefore doesn't include all sensors that the BCU analysis uses
* It compares current data with historic. The historic data is taken by averaging the 'normal' (i.e. non bank holiday) days since 1/04/2017
* Red dots mean that traffic speeds are at least 15% lower than historic speeds for a minimum of 3 consecutive 5 minute periods 

### *Results*
* Monday 15th afternoon version (12:00-00:00) here :- https://drive.google.com/open?id=0BwGwrLWk0TYpdkZhRnJnVW5vMkk
* Tuesday 16th version (06:00-00:00) here:- https://drive.google.com/open?id=0BwGwrLWk0TYpeThKNVNTZnJJTlk
* better quality video is possible, I just haven't done it yet

### *Analysis*
* Most obvious effect is traffic on the A34 comes quickly to a standstill. This is probably due to traffic not being able to use the A38M and therefore coming off at M6 J7. There are limited effects on other roads near to junctions - i.e. Soho Road, Bristol Road, Coventry Road.
* Patterns are different from Monday to Tuesday. Tyburn Road and the City Centre appear more affected on Monday.

### *Possible improvements*
* possibly need to do arrows to show direction of traffic (thats in the data already)
* Is there any HE data available?

## Examine traffic flow data to understand demand
### *Aims*
* Do people leave their cars in the city centre and walk home?
* Is demand lower on Tuesday morning, and by how much

### *Assumptions*
* Simple graphs now produced, using the geographically located counters only.
* Green is the day in question, Blue is the historic trend. X axis is time in 5 minute periods (divide by 12 to get hour of day)

### *Results*
*  Monday - https://drive.google.com/open?id=0BwGwrLWk0TYpVzFXRno1R0MtTTA
*  Tuesday - https://drive.google.com/open?id=0BwGwrLWk0TYpcjY1emNYYXJBc2M
*  Individual sensor date looks as follows: https://drive.google.com/open?id=0BwGwrLWk0TYpdm5TUnpFZ21reFU
*  Green is normal traffic (or no data) - blue is 15% above normal, red is 15% below normal

### *Analysis*
* Traffic flows are a bit higher than normal. Is this because of the A38M / M6 being closed adding extra traffic to the local network
* Longer morning peak on the Tuesday morning
* Long peak on the monday afternoon
* Higher flows on most roads - except for tyburn road. Worst looks like Walsall Road.

## Examine car park data
* To find out how many cars are left in the city centre on the Monday
* To see the extent of demand on the Tuesday morning (initially looks like retail car parks are half empty, but business related ones are still quite full)

## Examine cycle counter data (when available)
* Particularly to look at modal shift (and locations) on the Monday morning

## Freight
* Showed it to head of transportation. Wants to know if we have anything on freight

## Code
* post the code!!!
