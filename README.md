# Challenge 
Created by [N. Stevens](https://www.usfca.edu/faculty/nathaniel-stevens)

This challenge is inspired by the [culture of experimentation at Netflix](https://www.youtube.com/watch?v=WRGW6xHLy3k) with a hypothetical problem and a web-based response surface simulator. Our goal is to optimize the Netflix homepage by way of minimizing browsing time. 

## Problem

When faced with so many viewing options, Netflix users often experience choice-overload and can be overcome by decision paralysis, which negatively impacts Netflix because a user may become overwhelmed and may ultimately lose interest and not watch anything. We conduct a series of experiments to learn *what* and *how* the following 4 factors influence browsing time:   
**Tile Size**: Ratio of a tile’s height to the overall screen height. Aspect ratio is fixed   
**Match Score**: Predicted likelihood of user’s enjoyment.  
**Preview Length**: the duration (in seconds) of a show or movie’s preview.  
**Preview Type**: The type of preview that autoplays (Teaser/Trailer vs Actual Content)  

## Experimentation
We access the response surface simulator on the web. We upload a design matrix (experimental conditions) and collect results. The simulator mimics the random assignment of n=100 users to each condition and returns the response variable, i.e. browsing time. We are limited to a maximum of 40 experiments, which mimics real-life budget and time constraints. 


