# Citi Bike Study

Prepared by Corey Lawson-Enos

## Summary
* Tableau visualizations that study New York's Citi Bike bicycle share program's ride datasets years 2019 through 2021. A detailed station map with month/year ticker animates increases and decreases in station activity over the course of the three years.

* Questions asked and charted include:
  - Which periods were most active for the entire program? 
  - Which stations are most/least active?
  - How has ridership changed over the three-year period? 
  - Is the intrduction of electric bikes impacting ridership?

## Access
* Visit: https://public.tableau.com/app/profile/corey.lawson.enos/viz/citi-bike-challenge/CitiBikeStudy?publish=yes
* twbx Tableau file also available for download from this repository.

## Analysis
* Summary ride counts point to the pandemic's short-term impact, with an observable dip in 2020. The sizable rebound that followed in 2021 suggests perhaps Citi Bikes may now be considered by many to be a safer form of transportation than crowded bus or subway.
* Avergage ride duration also noticeably increased during the height of the pandemic, suggesting riders were willing to bike longer distances to avoid bus/subway. A spike is observable in the summer of 2021 as well, when the Delta variant surged. Increase is also shown as Omicron began to spread late in the year.
* A look into monthly ride totals demonstrates a seasonal pattern, though, with the warmer months showing the highest activity levels indepdent of the virsus's variant activity.
* As anticipated, the pandemic's shelter-in-place period of April 2020 reflects the program's lowest activity point. See also April 2020 station map tick (snapshot below).
* The program's casual ridership has increased significantly. The percentage of casual rides doubled from 2019 to 2021, pandemic notwithstanding. Pandemic health/safety considerations may be a significant factor, but further investigation into the larger availability of electric bikes, the program's overall expansion, and marketing to the tourism industry should all be considered as well.
* Classic/electric bike data is available after February 2021 only, but numbers already show that electric rides are widely popular. 40% of the membership chose electric during the eleven months of available data, as well as a significant 55% of casual riders. A link between the availability of electric bikes and increased casual ridership may be observed.

## Technologies
Tableau, Pandas

## Dashboard Preview

![Activity Charts](Images/activity.png)

![Ridership Charts](Images/ridership.png)

## Station Map Preview

![Station Map](Images/map.png)

## Sources

* ![Citi Bike System Data] (https://ride.citibikenyc.com/system-data)
* Metropolitan New York and Jersey City datasets for 2019-2021 downloaded, cleaned, and summarized in Pandas.
* Summary csv tables exported from Pandas saved in this repository's Data folder.

## Contact
E-mail: clawson131@gmail.com<br>
LinkedIn: https://www.linkedin.com/in/corey-lawson-enos/
