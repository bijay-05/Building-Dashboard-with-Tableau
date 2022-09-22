# Building-Dashboard-with-Tableau
This repository contains the data (csv file) for the guided project **Building Dashboard with Tableau** from [YouTube Video](https://www.youtube.com/watch?v=_qReGTOrKTk). Besides these, different **KPIs** to be included on the dashboard are listed below.
- Revenue per State
- Revenue based on month of the year
- Revenue based on Age
- Quantity ordered to discount percentage correlation
- Percentage of Revenue per Region
- Revenue per Category per Gender

Few important tips for reproducing the work.
- We minimized the labels of `sum(Total)` with format number options.
- While visualizing the **Revenue per Age**, we need to make `Age bins` measure discrete. So that each age group can be visualizied individually.
- From **Quantity ordered to discount percentage correlation**, it was clear that there is positive correlation between discount percentage and quantity ordered. In order to visualize the scatter plot between the fields **Quantity Ordered** and **Discount Percent**, we must convert them to dimensions instead of measures.
- For **Revenue per category per gender**, we created butterfly chart, which is not available on Tableau. For butterfly chart, we created two **Calculated Fields**, namely **Female Revenue** & **Male Revenue** from **Total** field, each one representing the total revenue of an individual gender.
- We also created a filter based upon **Category** field, which impacts the whole dashboard.


#### The interactive dashboard is available on [Tableau Public](https://public.tableau.com/views/RevenueDashboard_16638319859020/RevenueDashboard?:language=en-US&:display_count=n&:origin=viz_share_link)

![Revenue Dashboard](https://user-images.githubusercontent.com/86017045/191694816-8aa4e4a6-d964-4bbc-907a-ab1095fa75be.png)
