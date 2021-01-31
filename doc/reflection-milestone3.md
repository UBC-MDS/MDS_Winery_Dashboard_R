## Milestone 3 Reflection
*By DSCI532 Group VI* <br><br>
*Jan 30 2021*<br><br>

## Milestone 3 Implementation
- Right now, our dashboard allows customers to filter the wine data for multiple desired US states and wine varieties, using the left-side dropdown menu. In addition, there are two sliders that filter the data based on wine price and rating points. This enables customers to narrow down their selection.
- The choropleth map in the top right works as a heatmap, showing the number of reviews in the selected state. Hovering over the map will give an indication of the total number of wines in that state (this is not yet dependent on filtered selection). 
- There are two plots. The first is a scatter plot showing the relationship between average price and points for all of wine varieties that fall under the filtered criterion. Furthermore, there is a bar chart that displays the average rating for each of the filtered wine varieties. 
- Finally, recommendations are given to the customer based on the filtered criterion. The two recommendations are given based on the wine with the highest number of points as well as the wine that is considered to have the best value (number of points given the wine's price)

### Future Implementation
- There is currently no interactivity between the adjacent bar and scatter plots. We want to be able to give extra information based on selections on the graph
- Add an additional bar chart providing the counts of the selected filter.
- Have the hovering feature on the map given an output that is based on the filtered selection
- The value-vatio scale is not as clear as we would like. A majority of the data has a value ratio between 0 and 3, with outliers as high as 21. We need to find a way to implement a more balanced scale without having to remove outliers entirely (most of the filtering effects occur in the low-medium range). 
- Add a 'data tab' that can be used to browse the different names of wines based on the filtered selection.
- The filtered selection of the state dropdown does not affect the options of the variety dropdown (and vice versa). 
- Provide some text introducing the app and providing guidance to make the interface more user-friendly.
- Improve the overall aesthetic design (text, figure sizes, color schemes etc.).

## R Vs Python

There we both pros and cons to using R over python. We found that it was much easier to perform data frame manipulations to filter and select data based on the user's input. We also found ggplot2 in general to be a little more intuitive compared to altair for plotting. One of the major downsides of using R for this milestone was that Dash and Heroku are not as compatible with the language. The error messages were not as clear and deployment was much more confusing. We also felt that it was a little more difficult to work with BootstrapLayout in R. Overall, we are likely to stick with python for the final version of our project. 

## Adressing TA Feedback 
We agree with all of the feedback that we received in Milestone 1. We are still working to improve the aesthetic of our app to look better than the initial sketch that we provided. However, we were more focussed on implementing the mechanics of the app. We will be working on improving this for the final milestone. With regards to map interactivity, we want to implement what was mentioned about having a two-pronged filter with the map and the location dropdown. We will attempt this in milestone 4. 
