# Modeling Taxi Pickups in Manhattan Using Hierarchical Bayesian Methods

![alt tag](https://github.com/haroldli93/03-Modeling-Taxi-Activity/blob/master/Taxi_Pickup_Distribution_Screenshot.png)

I recently went through some online lectures about Bayesian methods, and found it to be useful to apply the concepts I've learned to a real-world application. NYC Open Data has a massive dataset on all taxi pickups, which we've parsed here to model taxi activity for each hour of the week across 288 regions of Manhattan.

I created three interactive visualizations from this project. 

[The first interactive](http://htmlpreview.github.io/?https://github.com/haroldli93/03-Modeling-Taxi-Activity/blob/master/Taxi_Pickups_by_Census_Tract.html) shows mean hourly taxi pickups for a particular region over the course of a week.

[The second interactive](http://htmlpreview.github.io/?https://github.com/haroldli93/03-Modeling-Taxi-Activity/blob/master/Taxi_Pickups_Hourly_Map.html) shows mean hourly taxi pickups across all regions of Manhattan for a given hour of the week.

[The third interactive](http://htmlpreview.github.io/?https://github.com/haroldli93/03-Modeling-Taxi-Activity/blob/master/Taxi_Pickups_Distributions.html) showcases the distribution of hourly pickups for a particular region at different times of the day.

[The PDF doucment](https://github.com/haroldli93/03-Modeling-Taxi-Activity/blob/master/Taxi_Bayesian_Model_Write-up.pdf) describes in detail the model I used and the derivations associated with implementing the Gibbs Sampler.

All my code is neatly organized in [this iPython Notebook](https://github.com/haroldli93/03-Modeling-Taxi-Activity/blob/master/Project_3_Bayesian_Modeling_Taxi_Rides_Final.ipynb).

A summary of my entire project can be found in [this post](http://databuckets.blogspot.com/2016/04/modeling-taxi-pickups-in-new-york-city.html) in my blog [DataBucket](http://databuckets.blogspot.com)

Always open to comments and suggestions for improvement!
