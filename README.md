# Amazon_Vine_Analysis

## **Overview of Amazon_Vine_Analysis**

### To study the dataset for PC collected from Amazon and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Use PySpark to determine if there is any bias toward favorable reviews from Vine members in the dataset.

## **Results**

- **How many Vine reviews and non-Vine reviews were there**

   * Urban areas had the highest numbers in Total Rides, Total Drivers, and Total Fares; Rural areas had the lowest numbers in all the studies above.
  
  <img src="Images/Total_Rides_Drivers_&_Fares.PNG" width=300><br />
  
   * Rural areas had the highest average fare per ride and average fare per driver; Urban areas had the lowest numbers in the studies above.
  
  <img src="Images/Avg_Fare_Per_Ride_&_Driver.PNG" width=500><br />
  
   * Throughout the study of the Total Fare between January and April 2019, Urban areas had the highest total fare among the city types; Rural areas had the least total fare. Urban and Suburban areas appeared to reach their highest total fare in late February; Rural areas had reached their highest number at the end of March/the beginning of April. 
  
  <img src="Images/PyBer_fare_summary.png" width=500><br />

## **Summary**

- **In order to minimize the disparities among the city types, please consider the following suggestions:**

  * Increase the rate for Urban and Suburban areas.
  
  * Hire more drivers for Rural areas.
