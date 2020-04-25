# Capstone 2 Project Ideas

## Proposal One: Predicting home sale prices

How much is your home worth? How much will that house you're bidding on likely go for?  
How likely are you to get the type of home you want within your budget? People looking to buy initially think of variables like neighborhood, number of bedrooms/bathrooms, and total square footage when they are trying to think of price. But is there more to it? What are the most influential features?

### P1: Approach

A linear regression is the first model that comes to mind but I could be wrong. Some EDA could shine more light on what to use.  

### P1: Application

A flask app could be built for people trying to get a quick idea for how much their home is worth. It could make suggestions for projects or remodels to increase the homes value.  
The app could also have features for those looking to buy. The application could display heatmaps showing how neighborhoods or addresses compare to their surroundings. Given a budget, the application could give people an idea of what a house that they can afford might look like.  

### P1: Data Source

This project is an ongoing "competition" on the data science website Kaggle. The data comes in csv format and is already split training and testing. There are 80 columns, including the target value SalePrice.  
<https://www.kaggle.com/c/house-prices-advanced-regression-techniques>  

---

## Proposal Two: Predicting overuse injuries in endurance athletes

Can we predict if an athlete will develop an overuse injury with enough time to mitigate it?  

Endurance athletes often push themselves to a point where their bodies can not handle the stress. Maybe they ran too far or maybe they're running to fast. Or maybe they're not recovering properly. What ever the cause is, the injury has a better chance of being avoided if the training plan is adjusted accordingly. The goal of this project is to predict when an endurance athlete will become injured and what the cause would be.

### P2: Approach

I'm not sure what model I would use for this project.  

### P2: Application

A flask app could be built for people to input basic information about themselves and their training routine. It would suggest a training pace/distance to safely work at. With more complete information that one might get from devices like a smart watch, the model could monitor someone as they train and tell them to ease up.

### P2: Data Sources

While many endurance athletes wear gps watches and other body monitors, getting access to their personal data is difficult.  
I could also try looking at the race and injury history of professional athletes. This approach would likely work with less data but it could still have some valuable output.  

---

## Proposal Three: Predicting worker productivity And Satisfaction

How much does environment influence the productivity or satisfaction of an employee?  

Do you work in open office plan or in your own private office? Do you work from home? Is the temperature uncomfortable? How much daylight is there?  
Do you work in front of a computer all day? Do you mostly go to meetings? Are you moving around? Do you interact with others?  
Our work environments are diverse and  complex with many different components. They influence how satisfied and productive we are. But how much and in what way?  

### P3: Approach

With an appropriate dataset, this might be a good problem for a neural network. My stance on this could change with some exploratory data analysis.  

### P3: Application

An application could be built to be used by managers accessing their work environment. Maybe it's built in a way that after filling out a checklist regarding their office, it could predict the productivity or satisfaction of their employees. Once the manager is convinced, the application could make suggestions for what could be changed first.  

### P3: Data Sources

This data could be challenging to track down. The Bureau of Labor Statistics collects data concerning things like compensation, output, or hours worked. The data appears to be in a database. Gallup collects data for various things like employment, corruption, and life evaluations. However, their data is proprietary and getting access might take some time or it might not be possible. The format of their data is unknown to me at the moment. Building plans are sometimes accessible online or by going through municipal channels. This would likely be in the format of a pdf. But documentation sets are ugly and inconsistent. Finding windows in a plan could be a project by itself.  
With enough searching and luck, a single dataset might be found online.  
