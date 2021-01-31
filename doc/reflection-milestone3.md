## Milestone 3 Reflection
*By DSCI532 Group VI* <br><br>
*Jan 30 2021*<br><br>

Until this milestone, our group has successfully implemented the main function of the proposed dashboard for winery selection using R. Some minor improvements
have been added according to given suggestions.

### APP Overview
This dashboard app enables potential customers to make their wise purchase by selecting the desired winery location, wine variety, price and rating ranges. The selected one or multiple winery locations are highlighted in the choropleth map of United States. Hovering around the states will give customers the total number of reviews. Moreover, the bar chart shows the average rating over the selected wine varieties. Customers are also able to explore whether higher price would indicate higher rating from the scatter plot, so it could help them decide on the best-value bottles. Furthermore, two cards present two recommendations based on the highest value (price per rating points) and the highest rating.

### Future Implementation
- The legends of bar chart and scatter plot are not merged well at this moment and need polishment on this.
- The overall aesthetic design can be improved by font type, interface color and inserting possible images.
- Connect three plots together and make it more interactive, such that clicking on the bar can display the corresponding data on the scatter plot.
- Some concise text about introduction and guidance of this dashboard can make it more user-friendly.
- The wine selections cannot be spontaneously filtered by a given state and vise versa, which is a challenge at this moment. 
- The dropdown manu will be better presented if alphabetically ordered.
- "Value ratio" can be confusing in the first look and may need more instruction.

### APP Limitations
- Even though the dataset samples globally, the app is only restricted to united states only.
- Due to the lackage of knowledge, the wine is not aggregated well and may overwhelm customers with such large range to select from.

### Implementations in R
- The function 'mean' of the price or rating causes errors for interactivity in Python, but this goes smooth in R.
-
-
-


