# Amazon_Vine_Analysis

## Overview

The purpose of this analysis is to determine the effectiveness of the paid Amazon Vine program. We'll be looking through reviews by both paid and non-paid people and seeing if all of the money Amazon is throwing at reviews is worth it and whether the pay is biasing reviewers towards giving a higher rating.

## Results

- Review count (Vine versus non-Vine). In looking at the video game dataframe I had literally 0 Vine reviews in my dataframe versus 1685 unpaid reviews. I thought at first that I had made a mistake, but the same line of code with the "Y" turned to a "N" gave me different results. See below:

<img width="508" alt="image" src="https://user-images.githubusercontent.com/105998378/192945309-81ecd3a6-7672-4792-a222-7cc009bea183.png">

- Of the unpaid reviews there were 631 5-star ratings and obviously 0 from the paid reviews.

<img width="580" alt="image" src="https://user-images.githubusercontent.com/105998378/192945723-df0e5659-d819-4157-a5b7-87190266baa9.png">

- The percentage of paid 5-star reviews was zero, and it gave me an error when I tried to divide 0 by 0. The percentage of unpaid 5-star reviews was 37.45 percent.

<img width="599" alt="image" src="https://user-images.githubusercontent.com/105998378/192945906-e43dcf34-5d37-419d-b7aa-3e26ca3c7355.png">


## Summary

There is clearly no positivity bias in the Vine program, as we had way more 5-star reviews that were unpaid than paid. While this is good, I would like to dig into the dataset and perhaps do another analysis where I looked at the average ratings of the Vine reviews and tried to determine if there was a negative bias or if, because they're getting paid to do reviews, the Vine reviewers tend to stay away from low-star ratings. 
