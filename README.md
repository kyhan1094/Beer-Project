
## This project is to recommend beers based on important features. 

**The data consists of columns of following features:**


*"beer_ABV , beer_beerId , beer_brewerId , beer_name , beer_style	, review_appearance, review_palette, review_overall, review_taste, review_profileName, review_aroma, review_text, review_time"*

## Output

This recommendation system will return two inputs from the users (desired beer ABV and prefer beer style), then it will recommend top 5 recommended beers by the closed ABV of user input from user's beer style choices. 

The engine uses the sub dataset that is filtered by 5/5 rated on all categories: taste, aroma, appearance, palette and overall

**Example output:**

beer_recommand(10,'American IPA')

I would recommand following 5 beers based on what you typed:  
['DFG IPA', 'Fritzkrieg Hop IPA', 'Jai Alai IPA - Cedar Aged (Humidor Series)', 'Jai Alai IPA', 'Jai Alai IPA - White Oak']
