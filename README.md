<b><p align=center>TATA Data Visualisation Virtual Internship-FORAGE</p></b>
---

This repository contains solutions of all the assignments or tasks that were required to be completed for FORAGE hosted TATA Visualisation Virtual Internship Program.


<b>Tools Used:</b>

Excel: Utilized for data preparation and cleaning by removing records with negative unit prices and quantities sold.

Tableau: Utilized for creating visualizations and extracting meaningful insights from the data.

---

<b> TASK-1 </b>

To prepare for your meeting, you need to draft questions that you think will be important and relevant to the CEO and CMO. This preparation will be your guide as you develop your presentation. For this task, you are only required to draft the questions. Make sure to think both quantitatively and qualitatively. You’ve been provided a dataset in the resources below to use as the basis for your exploration. Review this data, taking note of what information has been provided, what insights you can garner, and what is relevant to both the CEO and CMO respectively. Create a set of four questions that you anticipate each business leader will ask and want to know the answers to. Make sure you differentiate your questions, as both the CEO and CMO view business decisions through different lenses. Submit your eight questions in total (4 for the CEO and 4 for the CMO) in the text submission box below.


Here is the breakdown of type of questions each role might ask when reviewing a business dataset:


<u><b>For the CEO perspective </b></u>

1.Who are our top customers on region basis by purchase volume and what value-added offerings or loyalty strategies can we implement to further strengthen these relationships?

2.What is our current market share across these countries and what actions can we take to maintain our position while expanding into untapped markets?

3.Based on trends and forecasts, which products are underperforming across countries and should we consider discontinuing them to avoid potential revenue loss?

4.What is the revenue contribution of each country to our overall performance and what tailored expansion strategies should we pursue to maximize growth in high-potential regions?



<u><b>For the CMO perspective</b></u>

1.What is conversion rate of each channel across different countries and how can we further optimize it?

2.Which marketing strategy should we implement to effectively target qualified leads in untapped high, potential regions?

3.How can we build a system to analyze and customer feedback for testimonials driven content and data backed marketing strategy?

4.What is customer acquisition cost across different countries and how can we optimize it without compromising netsales and overall growth

---

<b> TASK-2.Choosing the Right Visuals</b>

This task involved answering five multiple-choice questions to determine the most appropriate type of visualization for different scenarios.

Q1: The CEO of the retail store is interested to view the time series of the revenue data for the entire year. The CEO is interested in viewing the seasonal trends and wants to dig deeper into why these trends occur. This analysis will be helpful for the CEO to forecast for the next year. Which visual would most likely help the CEO analyse the data?

<p align="center">Answer: Line chart </p>


Q2: The CMO is interested in viewing the top 10 countries which are generating the highest revenue. Additionally, as a subcomponent, they would also like to see which products are contributing to the total revenue being generated by each country. Which visual would enable the CMO to view the revenue for each country and the breakdown by products on a single chart?

<p align="center">Answer: Stacked bar chart </p>


Q3: The CEO of the online retail store wants to see how much average revenue is generated by each country. They are interested in viewing the following metrics on the visual: Minimum value First quartile value Median value Third quartile value Maximum value Which chart would you create to show the above metrics for the average revenue generated by each country?

<p align="center">Answer: Box Plot </p>


Q4: The CMO of the online retail store wants to view the information on the top 10 customers by revenue. They are interested in a visual that shows the greatest revenue-generating customer at the start and gradually declines to the lower revenue-generating customers. The CMO wants to target the higher revenue-generating customers and ensure that they remain satisfied with their products. Which visual would help the CMO understand the data on revenue generated by the top 10 customers?

<p align="center">Answer: Column chart </p>


Q5: The CEO is looking to gain insights on the demand for their products. They want to look at all countries and see which regions have the greatest demand for their products. Once the CEO gets an idea of the regions that have high demand, they will initiate an expansion strategy which will allow the company to target these areas and generate more business from these regions. He wants to view the entire data on a single view without the need to scroll or hover over the data points to identify the demand. Which chart would be most useful to provide the CEO information on the demand in each region?

<p align="center">Answer: Map chart </p>


---

<b> TASK-3.Creating Effective Visuals</b>

This task involved creating effective visuals using Tableau in order to answer four questions that the CMO and CEO requested.

These are the questions requested by the management:

<b>Question 1</b>

The CEO of the retail store is interested to view the time series of the revenue data for the year 2011 only. He would like to view granular data by looking into revenue for each month. The CEO is interested in viewing the seasonal trends and wants to dig deeper into why these trends occur. This analysis will be helpful for the CEO to forecast for the next year.

![Line_chart](images/Question.1.png)



<b>Question 2</b>

The CMO is interested in viewing the top 10 countries which are generating the highest revenue. Additionally, the CMO is also interested in viewing the quantity sold along with the revenue generated. The CMO does not want to have the United Kingdom in this visual.

![Alt text](images/Question.2.png)


<b>Question 3</b>

The CMO of the online retail store wants to view the information on the top 10 customers by revenue. He is interested in a visual that shows the greatest revenue generating customer at the start and gradually declines to the lower revenue generating customers. The CMO wants to target the higher revenue generating customers and ensure that they remain satisfied with their products.

![Alt text](images/Question.3.png)


<b>Question 4</b>

The CEO is looking to gain insights on the demand for their products. He wants to look at all countries and see which regions have the greatest demand for their products. Once the CEO gets an idea of the regions that have high demand, he will initiate an expansion strategy which will allow the company to target these areas and generate more business from these regions. He wants to view the entire data on a single view without the need to scroll or hover over the data points to identify the demand. There is no need to show data for the United Kingdom as the CEO is more interested in viewing the countries that have expansion opportunities.

![Alt text](images/Question.4.png)


---

<b> TASK-4.Communicating Insights and Analysis </b>

This task required developing a script or recording a video presenting my findings to the CEO and CMO based on the four questions they asked and the visuals I have created in the previous tasks.When writing my script,I am required to speak about the entire process, including the initial data load and clean-up steps so that leaders know I’ve done my due diligence in providing error-free analysis. 

<u><b> SCRIPT: </b></u>
<b><p align="center"><a href=https://public.tableau.com/app/profile/palak.kakkar3333/viz/Tcs_internship_project/Dashboard_OnlineRetailstore>Dashboard </a> </b>

Hello everyone!

I am Palak, a consultant here. I am very glad to present my insights that I gathered after reviewing store’s data and I have firm faith that these insights would be valuable for the management and store’s growth.
While the 2010-11 dataset is comprehensive and insightful, I have focused my analysis on the year 2011 only to provide a more detailed and actionable perspective.

Prior to analysis, I ensured data integrity by addressing issues such as negative quantities for returns and correcting erroneous unit prices through data transformation techniques in order to get rid of the bad data which would impact the analysis.

So, Let’s begin. 

Regarding the first query,
Since the management inquired about the revenue trends for 2011 to assess seasonality in retail sales. So, as per the data, the first 8 month of sales from January to August were very stable with an average of $6.85 million. After that there was an increasing trend in revenue from month of September up till November, the highest increase being in September of almost 40% over previous month.
Unfortunately, Since the data for month of December is insufficient, I have excluded it from the analysis as no inferences can be made from it.
So, to conclude, the data suggests opportunities to capitalize on peak periods through targeted strategies.

Regarding the next question wherein the management is interested in viewing the top 10 countries which are generating the highest revenue. I understand that the management wants to identify potential growth regions where demand may boost. I analyzed the top 10 countries by revenue, excluding the UK which has highest contribution in store revenue so far.
Here, Blue colour represents quantity and orange represents revenue. As per this data of quantity demanded and revenue, out of these Top 10 nations, Countries such as Ireland, Netherlands, Germany, France, and Australia exhibit significant growth potential and focused expansion is required to tap into these emerging markets. So, I would propose concentrating on these nations.



Now moving forward to third topic of study wherein management wants to view information of top 10 customers by revenue. Previous to this, we were talking about revenue trends and opportunities for expansion in order to ensure store’s aim of growth, increasing revenue and finding and exploiting opportunities of expansion, which is great, but at the same time, it is equally important to ensure customer retention and providing best to our existing customers.

So, for the same, as we can see in this chart. Here are the top 10 customers and along with their customer ids, I have added details about their countries as well. Highest one is from Netherlands and out of these 6 are from UK,2 from Ireland and one from Australia. Also, the fact that the highest revenue producing customer spent only 10% more than the second highest demonstrates that the revenue distribution indicates a diversified customer base, reducing dependency on a single client and country.

Now, moving on to the next and last topic of our study, this map chart concludes by comparing the places that have produced the highest demand to those that have not. I have excluded UK from the analysis as required since the management is interested in knowing areas that have expansion opportunities that is untapped regions.
So from this analysis, the regions which had a high demand in year 2011 are Netherlands, Ireland, Germany, France, Australia so company should invest more in these nations to further boost demand and profits.

Along with that this map shows there is no market for our products in regions like Russia, USA, Malta, Brazil, Bahrain. These are huge unexplored regions for our store which might turn out to be our major customers if proper market environment analysis and tailored strategies are implemented. Investing in these regions would turn out to be a major income and customer base source for us.

That’s all from my side. I appreciate your attention and am open to any questions or further analysis if needed.

Thank you.
