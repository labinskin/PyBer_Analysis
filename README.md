# PyBer_Analysis

##### **Overview**

V. Isualize has given you and Omar a brand-new assignment. Using your Python skills and knowledge of Pandas, you’ll create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, you’ll create a multiple-line graph that shows the total weekly fares for each city type. Finally, you’ll submit a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

##### Results
![](https://github.com/labinskin/PyBer_Analysis/blob/main/Resources/Summary%20of%20Data.png)
By looking at the DataFrame summary of the PyBer data of Rural, Suburban, and Urban rideshares, there are a few main ideas that we can takeaway.

Urban rides make up approximately 61% of the company's total fares, while Rural rides make up only approximately 7% of total fares, with Suburban rides making up approximately 30% of the total profits. It seems the pure number of rides drives this, with there being thirteen times more total Urban rides than Rural rides.

With this, while Urban rides by far have the highest number of total rides, it has the lowest average fare and average fare per driver. Urban also has more drivers (about 1.48 drivers for every ride). This glut of drivers, even with the high volume, means that urban drivers need to have more rides and riders than they have to earn their money, as they are competing amongst themselves for customers.

Whereas, while there are far fewer Rural rides, the average fare per ride is higher, along with the average fare per driver. This is likely caused by a few different reasons. First, there are far fewer Rural drivers. Unlike there being more drivers than total rides for Urban, for Rural (and Suburban), there are more rides than drivers (about .68 drivers for every ride). This means drivers have more opportunity. Second, Rural may also have higher fares per ride and driver because of the distance between locations. Whereas, in urban environments the drivers might be closer to their rider and the distance relatively short. Rural drivers might have to travel a ways to pick-up the rider and then an additional distance to drop them off, incurring a higher total fare and higher fare per driver.

Last, Suburban drivers are somewhat in the middle. There are .78 drivers for every ride. So drivers are not oversaturating the demand and competing with each other for riders. They earn a decent fare, unlike Urban, but not as much as Rural. However, with it being Suburban, their rides might not be as long as Rural and the distance to pick-up a rider might be shorter too, causing a lower fare per ride and per driver than Rural.

![](https://github.com/labinskin/PyBer_Analysis/blob/main/Resources/Line%20Plot%202.png)
By looking at the Line Plot, we can see the total fares plotted out. By looking at this, it shows that Urban is fairly consistent at making at least $2000 per day (not every day, there are two dips below), with a couple of swings close to $2500 a day and a couple closer to $2000. Suburban typically hovers around the $1000 a day mark, with only one major sharp increase around the end of February and a small sharp decrease around the beginning of April. Suburban seems more consistent on a day to day basis. Whereas, Rural has two sharp increases at the end of February and end of March/beginning of April. Rural never broke $500 a day (maybe meeting it on April 1). After April 1, there is a decline the rest of the month, with no bounce back.

##### Summary

