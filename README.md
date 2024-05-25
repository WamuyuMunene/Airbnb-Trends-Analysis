AIRBNB TRENDS IN VICTORIA, AUSTRALIA

INTRODUCTION

Airbnb has grown immensely from the two hosts and three guests it started with to having over 7.7 million Airbnb listings and 5 million hosts. In the Q1 2024 period (their most profitable first quarter ever), Airbnb realized a net income of $264 million (up 126% from Q1 2023) and revenue of $2.1 billion (up 18% from Q1 2023). Airbnb has over 150 million users globally and serves an average of nearly one million guests on a daily basis.

Australia has not been left behind in this growth and specifically Victoria State that had over 44,800 listings as of March, 2024 (PriceLabs, 2024).

In this project, the aim was to uncover trends in the Airbnb market in 30 of the 79 Local Government Areas (LGAs) in Victoria, Australia. The dataset used for analysis consisted of 23,185 Airbnb listings. The project included geographic distribution analysis, hosts analysis, property analysis, amenities analysis, availability analysis and feedback analysis.

DATA CLEANING AND PROCESSING

The data cleaning process was conducted on PowerBI using power query. The data used was collected using web scraping on September 05, 2023 and needed extensive cleaning. First step involved deleting columns that would not be used for the analysis and columns that did not have any data.

After this, conditional custom columns were used to impute data from within the dataset into the appropriate fields that were missing data i.e. bathrooms, bedrooms and beds columns. Rows that did not have data after imputation were deleted. The final dataset used for analysis consisted of 23,000 Airbnb listings.

The amenities column had its data in list format and for ease of analysis and visualization some of the data was retrieved and inserted into custom columns in Boolean values i.e. the most in-demand/must-have amenities.

Data within some of the columns that used Boolean values t (True) and f (False) was converted into Yes and No for ease of understanding and readability.

Finally, DAX measures that would be useful in the analysis were created.

INSIGHTS

GEOGRAPHICAL DISTRIBUTION

Of the 23,000 Airbnb listings, the top 5 LGAs by listing count were:
·       Melbourne 7229 (31%)

·       Port Philip 2721 (12%)

·       Yarra 1761 (8%)

·       Stonnington 1506 (7%)

·       Yarra Ranges 1109 (5%)

The most popular property types overall were entire rental unit, entire home and private room in home. Yarra Ranges, Nillumbik and Cardinia had the most differentiated set of property types in their top 10 featuring properties like entire cottage, farm stay, entire cabin and tiny home. Melton was the only LGA with Dome property type in the top 10.

The average overall price was $232. Manningham had the highest average price at $392 while Brimbank had the lowest at $123.

The overall total of verified hosts was 90%. Melton had the lowest percentage of verified hosts at 84% while Nillumbik had the highest at 95%.

HOST ANALYSIS

There were 13,293 hosts. 22% of the hosts’ listings had received an overall rating of 5.00. 25% of the hosts were super hosts with Yarra Ranges being in the lead with 51% of its hosts having superhost status. 6243 hosts had 100% response rate while 3468 had 100% acceptance rate.

The hosts with the highest number of listings were:
·       MadeComfy - 1755

·       Apac - 854

·       Advante Homes - 659

·       MadeComfy Melbourne - 646

·       Hometime - 638

·       Luxico - 545

·       Sidharth - 508

·       Ava And Team - 505

·       Tiny Away - 353

·       Flexistayz – 348

5876 of the listings were listed as instant bookable by 3228 hosts. Instant bookable listings had a higher average price of $247 vs $226 for those that were not instant bookable.

Paul & Dan had 12605 reviews, the highest in the dataset, and an overall rating of 4.81.

Among the top 10 most reviewed hosts, MadeComfy had the lowest overall rating of 4.31 from 4081 reviews and Lee had the highest overall rating of 4.94 from 4578 reviews.

Among the top 10 most reviewed hosts, Ming had the lowest average price at $126 and Alix & Taj had the highest at $281.

76% of the hosts respond within 1 hour of being contacted.

16428 of the hosts had both email and phone contact information on their profile.

PROPERTY ANALYSIS

16820 of the listings were entire home/apartment listings with the most common property types being entire rental unit (9820), entire home (3609) and private room in home (2766).

8716 of the Airbnb listings had an accommodation capacity of 2 guests.

11200 of the listings had 1 bath, 11272 had 1 bedroom and 10428 had 1 bed.

There were 727 studio apartments in the listing.

The most expensive property type (Average price of $983) with more than 100 listings (120 listings) was private room in villa. These listings had an average overall rating of 4.63 and were present in 21 of the 30 LGAs. There were none in Melbourne and the LGA with the highest number was Wyndham (28 listings).

The most affordable property type ($165) with more than 100 listings (413) was entire guesthouse. They had an average overall rating of 4.82. The LGA with the highest number was Yarra Ranges (99 listings)

AMENITIES ANALYSIS

In regards to amenities, the project focused on said to be must-haves for Australian Airbnbs according to Airbnb newsroom.

Hume had the highest percentage of free parking at 98% while Melbourne had the lowest (33%). The most popular property types in Hume were private room in home and entire home while Melbourne mostly had entire rental unit properties.

Greater Dandenong had the lowest percentage of pools (2%) and Melbourne had the highest (51%).

Yarra Ranges had the highest percentage of self-check-in properties (63%).

Listings with between 4.50 to 5.00 overall rating had low percentages in pets allowed (14%), pool (23%) and gym (22%) amenities.

Listings with pool and pets allowed option available had the highest average pricing at $258 and $294 respectively.

60% of listings by superhosts had self check-in available vs 38% for hosts that did not have superhost status. 72% of listings by superhosts had patio/backyard/balcony space vs 46% for hosts that did not have superhost status

FEEDBACK ANALYSIS

Cardinia and Yarra Ranges had the highest overall rating, 4.86 and 4.85 respectively.

Yarra Ranges was the top performing in all categories except communication and value in which Cardinia was the leading LGA.

Greater Dandenong and Melbourne had the least overall rating of 4.56 and 4.58 respectively.

Regardless of being low rated Melbourne had the 5th highest rating in location of 4.86

AVAILABILITY ANALYSIS


8487 listings had no availability within 30 days of data collection. These listings had an overall rating of 4.55 and average price of $187.

1918 listings had all subsequent 30 days available from the date of data collection. These listings had an overall rating of 4.47 and average price of $388.

In both scenarios listed above in regards to availability, Melbourne had the highest percentage with 26% for no availability listings and 29% for full 30-day availability listings. They were mainly entire rental unit properties that accommodation capacity of two people and 1 bath, 1 bedroom and 1 bed. The notable difference in Melbourne, as is observed overall as well, was in average pricing with $169 for no availability listings and $446 for full 30-day availability listings.

Average pricing for Airbnbs requiring 30-day minimum stay was $160, 60-day minimum stay was $244, 90-day minimum stay was $231 and 365-day minimum stay was $3898.

CONCLUSION


Yarra Ranges is a top performing LGA in the Airbnb market in Australia as it has a high number of Airbnb listings, unique property types available for guest to stay at, the highest ration of superhosts and high ratings across all categories.

There is high supply and demand of entire rental unit properties within Melbourne.

Pets allowed is not in demand as a low ration of the listings have this provision and it has not impacted the rating.

Some must-have amenities especially for listings within Melbourne according to ratio of listings that have them are Wi-Fi, TV, kitchen, washer/dryer, essentials and air conditioning/heating.

1 bedroom/ 1 bath/ 1 bed with accommodation capacity of 2 makeup the largest ratio of supply.

Property type may be a determinant in whether there will be free parking/free street parking provided by the host.

Listings with lower, more affordable price are in higher demand than those with higher pricing.

RECOMMENDATIONS

Hosts should prioritize responding to inquiries in a timely manner as it has an impact on customer satisfaction.

Melbourne is high ranking in regards to number of listings and location rating but the hosts need to increase quality of service in regards to check-in process, value provided to guests, listings accuracy, cleanliness and communication with guests.

The recommended hosts for having a high number of reviews, high overall ratings and multiple listings available for guests would be:

Lee: https://www.airbnb.com/users/show/356845764

Alix and Taj: https://www.airbnb.com/users/show/9510598

Tiny Away: https://www.airbnb.com/users/show/154813436

Paul & Dan: https://www.airbnb.com/users/show/1739996

Sandy and Ange: https://www.airbnb.com/users/show/20400356


Fiona: https://www.airbnb.com/users/show/207219509

John: https://www.airbnb.com/users/show/7600086

Additional analysis could be conducted with sole focus on amenities so as to cover all amenities that are provided by the Airbnbs. This could be done using python.
