# Lyft-Pricing-Model
#Lyft Pricing Model for a one way trip with multiple variables. 
#Prompt
#Pretend you’re the pricing product manager for Lyft’s ride-scheduling feature, and you’re launching a new city like Toledo, Ohio.

The prevailing rate that people are used to paying for rides from the airport to downtown (either direction, one way) is $25. The prevailing wage that drivers are used to earning for this trip is $19.

You launch with exactly this price: $25 per ride charged to the rider, $19 per ride paid to the driver. It turns out only 60 or so of every 100 rides requested are finding a driver at this price.

(While there is more than one route to think about in Toledo, for the sake of this exercise you can focus on this one route.)

Here’s your current unit economics for each side:

Drivers: 

Customer acquisition cost (CAC) of a new working driver is roughly $500

At the prevailing wage, drivers have a 5% monthly churn rate and complete 100 rides / month

Riders: 

CAC of a new rider is $10 to $20 (it’s sensitive to the rate of acquisition, since existing marketing channels are only so deep) 

Each rider requests 1 ride / month on average

Churn is interesting: riders who don’t experience a “failed to find driver” event churn at 10% monthly, but riders who experience one or more “failed to find driver” events churn at 33% monthly

You’ve run one pricing experiment so far: when you reduced Lyft’s take from $6/ride to $3/ride across the board for a few weeks, match rates rose nearly instantly from 60% to roughly 93%.

Your task is to maximize the company’s net revenue (the difference between the amount riders pay and the amount Lyft pays out to drivers) for this route in Toledo for the next 12 months. Let’s assume that you cannot charge riders more than the prevailing rate.

The core question is: how much more or less do you pay drivers per trip (by changing Lyft’s take)? Your goal is to maximize net revenue for the next 12 months on this route.
