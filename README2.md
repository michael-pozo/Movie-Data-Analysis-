# Considerations for Entering the Movie Industry 


## Business Question

Microsoft is looking for new ways to bring in additional revenue in the new year. They have seen many of their competitors enter into the movie space with success and want to know what the correct entry strategy would be for them. 

## The Data

Datasets from two unique sources were used in this analysis. The first is an ERD containing characteristic data of movies such as title names, genres and director names from the website IMDB (https://www.imdb.com/). The second comes from the website The Numbers (https://www.the-numbers.com/) and contains financial information such as movie production budgets and worldwide box office sales. 

## Approach

The approach taken involved examining the datasets for information that may be relevant to a movie's success. Each dataset was then cleaned by removing irrelavent columns, null values and duplicate entries. Individual datasets from both IMDB and The Numbers were merged to create overlapping datasets containing characteristic and financial data for movies. Visualizations were created from the datasets to illustrate insights that Microsoft would find impactful.  

## Results

![box_office_sales_by_month](https://user-images.githubusercontent.com/66101132/215112512-df89a175-c3ae-4112-95b9-a080af28a4e4.png)

* Median box office sales fluctuate by month with clear peaks in June, July and November 
* This trend holds true for both domestic and foreign markets

![genrebyprofit](https://user-images.githubusercontent.com/66101132/215112584-479c22ae-5ce6-47c5-a42a-b51282727571.png)

* Within peak months, the top five most profitable genres are Animation, Adventure, Sci-Fi, Action, and Fantasy
* Animation is the most profitable genre with a median profit 106% greater than the median profit of the group listed above

<img width="463" alt="Director Shortlist" src="https://user-images.githubusercontent.com/66101132/215113972-c40d5a07-2b58-49fc-ada0-d3e8731d51af.png">

* Microsoft should pursure the best directors in the genre based on profitability and ROI. The directors in the table above rank in the top ten in both categories 

![budget_profit_corr](https://user-images.githubusercontent.com/66101132/215112645-b2b78df0-54d7-42ab-90cc-c4b2ab46cc02.png)

* There is a moderately positive correlation between production budget and profit in the animation genre
* The middle 50% of budgets have a high concentration of movies with outsized profits. This indicates the potential to make large profits without spending more than the median genre budget 

## Recommendations

Microsoft should consider the following recommendations when entering into movie production 
* Release movies in June, July or November to maximize audience size and box office sales 
* Produce movies in the Animation genre to make the most amount of money per film 
* Select a director with a proven track record of high profitability and ROI by using the director shortlist
* Don't overspend as larger production budgets are not strongly correlated with increased profits 

## Next Steps

The data available can help predict what type of movie Microsoft should make, when they should release it, which directors they should use and how much money they should spend. Given additional data, it is possible to enhance these recommendations as well as create new ones. Some topics of interest are:
* The merged IMDB and The Numbers dataset only goes through 2019. The movie industry was completely upended by Covid-19 as the quarantine and subsequent rise of streaming completely changed the way consumers watch movies. More recent data would provide more context on the current state of the movie industry 
* One of the main recommendations was to make animated movies. Microsoft owns a lot of its own content through Xbox Studios. It would be very interesting to see which original titles are the most popular to see if there is an opportunity to create movies from their own content
