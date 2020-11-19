## Internet History

Visualize (Google Chrome) internet history activity and recommend websites based on the current time. 

This is definitely in progress, and I plan on adding more visualization as well as a better predictive model.

Also, I promise everything is from a fake history file :)

----

###Visualization

####Top 5 sites visited
![alt tag](https://github.com/ImAJason/Internet-History/blob/master/Images/Top5%20Sites.png)


####Overall look at Internet Activity throughout the day
![alt tag](https://github.com/ImAJason/Internet-History/blob/master/Images/histogram.png)


####Internet activity on weekdays vs weekends
![alt tag](https://github.com/ImAJason/Internet-History/blob/master/Images/weekdayend.png)

----

###Site Recommendation

After testing potential choices via cross validation, Gradient Boosting seemed like the best model for this specific project. However, the accuracy was not very good (<.75). Looking into other possibilites such as stacking/combining models, with one hot encoding as a possible option. Overall, this is a learning experience and I would love any advice or suggestions.

####Site recommendation example:
![alt tag](https://github.com/ImAJason/Internet-History/blob/master/Images/Site Recommendation.png)
