# Udacity_DataAnalysis_DataVisualizations
Project Date: 30/08/2020

Communication is important. Becuase it make us express our thoughts and ideas. And failing to express our ideas to others could cause catastrophies. <br>
Since not all people are experts in statistics, we should express the result of analysis in a manner which clearly conveys our message. <br>
One project in udacity's data analyst nano degree is to analyze then visualize the results to practice communication. In this project, I chose to analyze a data set from  Ford Gobike riders in 2019-12. This data set contains observations of of bike renters in December 2019 in San Francisco. <br>
Each observation includes:

        Trip Duration (seconds)
        Start Time and Date
        End Time and Date
        Start Station ID
        Start Station Name
        Start Station Latitude
        Start Station Longitude
        End Station ID
        End Station Name
        End Station Latitude
        End Station Longitude
        Bike ID
        User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual)
I have used python libraries such as: pandas, matplotlib, seaborn, NumPy. Then the jupyter notebook as the working space to analyze the data. After the data is cleaned and prepared to analyses, I have used exploratory analysis to explore the patterns in the data. You may find the whole exploring code in Ford Goride riders 2019-12.ipynb. Finally, fter the analysis, a visualization slide deck is produced to communicate with others in explanatory analysis. <br><br>

#### Summary of Findings <br><br>

> The trip duration approximately follows normal distribution where most of renters' trip 6 minutes. Count decreases as duration increases. <br>
> 1.1% of renters rent the bike for more than 1 hour. <br>
> There is a renter rented a bike for 10 days. <br>
> 52% of renters are subscribers. 48% are custromers. <br>
> Customers tend to spend a couple more minutes on their trip than subscribers. <br>
> Subscribers count is higher than customers during all week days. <br>
> Most bike riders rent bikes on weekdays not weekend. <br>
> On weekends, bike riders trip duration increase by a couple of minutes. <br><br>

#### Key Insights for Presentation <br><br>

> The data doesn't have variety of quantitative features. <br>
> All the performed analysis was only for a month 2019-12 <br>
> duration_sec was converted to duration_min. <br>
> end and start timestamps are splited to 4 columns (start_date, start_time, end_date and end_time). <br>
> start_station_latitude, start_station_longitude, end_station_latitude, end_station_longitude, duration_sec, start_station_name, and end_station_name columns were dropped. <br>
> Two new columns were added weekend and day of week. <br><br>






To access the website and aquire data: https://www.lyft.com/bikes/bay-wheels/system-data
