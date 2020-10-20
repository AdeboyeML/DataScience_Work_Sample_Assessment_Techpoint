[//]: # (Image References)

[image3]: ./foodie_images/average_cost_foodie.PNG "avg_cost"
[image1]: ./foodie_images/heatmap_foodie.PNG "heat_map"
[image2]: ./foodie_images/best_rest_foodie.PNG "best_rest"
[image4]: ./foodie_images/exp_rest_foodie.PNG "exp_rest"
[image5]: ./foodie_images/aff_rest_foodie.PNG "aff_rest"
[image6]: ./foodie_images/new_foodie.PNG "new_foodie"
[image7]: ./foodie_images/common.png "cuisines"

# DataScience_Work_Sample_Assessment_Techpoint
Exploratory and Geographic analysis on Foodie Dataset - A Work Sample Assessment





### Data Science work sample assessment - Xtern 

### Please, Note: The visualizations in the notebook can ONLY be viewed using this [nbviewer link](https://nbviewer.jupyter.org/github/AdeboyeML/DataScience_Work_Sample_Assessment_Techpoint/blob/main/Data_Science_Work_Sample_Assessment.ipynb) 


#### Visualization Tools Used:

- Plotly
- Folium

#### Situation

Where are my foodies at? 😋 

In order to make FoodieX the best delivery service in town, the data science team is focusing its efforts on analyzing the data set to provide useful insights into the business. 

You can find a data set below with restaurant information. The data set contains Restaurant ID, Latitude, Longitude, Cuisines, Average Cost, Minimum Order, Rating, Votes, Reviews, and Cook Time.

#### Your Task

Review the data and draw four conclusions you can find from the data set. Some ideas of conclusions could include: trying to identify the trending restaurants with your own scoring algorithm (can be as simple as the best rating or most votes or both!), clustering restaurant locations to figure out the optimized FoodieX pick up zones, estimating cook time based on restaurant info, and demonstrating your findings using a data visualization tool. As an important member of the FoodieX team, you get to come up with your own analysis! So try your best to dig out any useful information out of this data set. The sky's the limit! 🤓


### Conclusions from the 10 findings I was able to analyze from this dataset:

- All restaurants included in this dataset are located around ***Rushville, Brookville, Shelbyville, Greensburg, Greenfield, Columbus, Batesville, Newcastle, Versailles, McCordsville*** in Indianapolis. These locations are the **hotspots** for restaurants in Indianapolis based on this dataset.



- Based on the geographic heatmap, the above-mentioned ***hotspots locations*** are the **best pick-up zones** for food delivery



- ***67% of cuisines have 30 minutes cooking time, 24% have 45 minutes cooking time, 3% have 65 mins cooking time, 0.3% have 120 minutes cooking time while the rest have 10 and 80 minutes cooking time.***



- The **best restaurants** with above 4.5 rating have the **most votes and reviews** among all restauarants in this dataset.



- Most restaurants in this dataset **are affordable (about 99%)** i.e. less than or equal to 50 Dollars Average cost and Minimum order per cuisines, while ***only a few of them (about 0.1%) are expensive*** i.e. above 50 Dollars Average cost and Minimum Order.



- About 92% of the restaurants have 50 Dollars Minimum Order, 6.5% have 99 Dollars Minimum Order, 1.2% have 0 Dollars Minimum Order, while the rest are shared by the remaining restaurants.



- About 6.8% restaurants in this dataset are ***newly-opened or soon-to-be-opened*** and are situated around the above-mentioned locations.



- The most affordable cuisines (top 10) in Indiana i.e. less than 20 Dollars Average costs, based on this dataset are: ***North Indian, Fast Food, Chinese, Beverages, South Indian, Desserts, Biryani, Street food, Rolls, Mughali***.



- The most expensive cuisines (top 10) in Indiana i.e. above 20 Dollars Average costs, based on this dataset are: ***North Indian, Chinese, Italian, Continental, Mughali, Asian, European, Thai, Salad, Finger Food.***



- The most common cuisines (top 10) in Indiana based on this dataset are: ***North Indian, Chinese, Italian, Continental, Mughali, Beverages, South Indian, Street Food, Fast Food.***



- Overall, the most common cuisine is **North Indian, available in about 43% of the restaurants included in this dataset, and some of these restaurants are concentrated in Rushville, Shelbyville and Batesville.**




### - Some Major Findings

### - Locations of Restaurants grouped by their respective "Average Cost" per cuisine.
![avg_cost][image3]



### - Hotspots of Restaurants in Indianapolis (identifiable pick-up zones).
![heat_map][image1]



### - Location of the Best Restaurants in Indianapolis.

- **Two Red Icons** are the Restaurants with the highest ratings, one of them also has the highest numbers of votes and reviews.

![best_rest][image2]



### - Location of the Most expensive restaurants in Indiana.
![exp_rest][image4]


### - Location of affordable restaurants grouped by "Average Cost" of cuisines.
![aff_rest][image5]


### - Newly opened and Soon-to-be-opened restaurants.
![new_foodie][image6]



### - Most Common Cuisines in Indianapolis -- Top 20.
![cuisines][image7]
