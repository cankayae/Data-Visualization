# Data Visualization Of Volusia County Sale Analysis Data

In this project, I aim to visualize proptery sales using two dimension: time and price. The data source of this project can be found at https://vcpa.vcgov.org/#gsc.tab=0 Data was organized using PostgreSQL and QGIS to create a sale analysis table. Then, the relation between property sale prices and the time since sales took place was visualized using Tableau. The dataset used for this project can be found in the project GitHub repository and titled as Volusia County Sales.zip.   
Below, there are four figures depicting the relationship of the two main attributes, sale price and time. Two attributes in the dataset that have an influence on sale price were also included in the visuals. 

![Figure 1](https://user-images.githubusercontent.com/82909354/116007793-79854800-a5df-11eb-97e6-c79e054c2e04.png)

Figure 1 presents the minimum price value of properties in Volusia county over time, more specifically from 2017 till 2020. The attributes (1) median of months since the sale, (2) sale and (3) sale price were depicted in the visual. As seen in Figure 1, there is a linear trend between minimum property sale price and sale year, which suggests that the minimum property price increased as time passed. On the other hand, the median of months since sale decreased from 46 months to 8 months over time, implying that properties were selling at a faster rate in recent years.  

![Figure 2](https://user-images.githubusercontent.com/82909354/116007805-81dd8300-a5df-11eb-88b9-cd93b95932d2.png)

Figure 2 reflects the average price value of properties in Volusia county over the last four years. As seen in Figure 2, the height of each bar reflecting average property price had a growing trend. The average property price was $200,088 in the second quarter of 2017 whereas the average property price exceeded the 250K range starting in the third quarter of 2019, more specifically between the months of July-September. The highest average property value was reported in the third quarter of 2020 as $274,225, which remained almost the same in the last quarter of 2020 ($274,221). The orange-colored line reflects the median of months since the sale and implies a negative linear trend. In other words, the negaive linear trend suggests that properties were selling more quickly over time. 

![Figure 3](https://user-images.githubusercontent.com/82909354/116007810-86a23700-a5df-11eb-821f-72603a2ee411.png)

Figure 3 present the same information depicted in Figure 2 using a line graph instead of a bar graph. 

![Figure 4](https://user-images.githubusercontent.com/82909354/116007815-899d2780-a5df-11eb-992f-4bfe4e650b43.png)

Figure 4 includes the following four attributes: (1) sum of property price, (2) year of sale, (3) median months of sale and (4) zip code. The reason why zip code was added into the visual was because it had an impact on property sale price. As reflected in the visual using different colors, the median months of sale decreased over time.  The median months of sale was close to 50 months in 2017 (large circles shown in red color) whereas the median months sale drastically decreased in 2020 (small circles shown in purple color). Moreover, Figure 4 shows that properties located in same zip codes remained relatively in the same price range with a few exceptions. As pointed out in the figure, the sum of property values in 32124 zip code drastically increased from $33,702 in 2017 to $363,515 in 2020 ($119,723 in 2018 AND $346,799 in 2019). 


