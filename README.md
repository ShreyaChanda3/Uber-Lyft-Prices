# Data Visualization of Uber & Lyft Prices Using Tableau

### Project Overview
This project aims to visualize the pricing strategies of Uber and Lyft using data visualization techniques in Tableau. We analyze the prices of rides across different areas in Boston, Masschussetts and visualize trends in prices over time. The goal is to provide insights into the pricing strategies of Uber and Lyft to help consumers make informed decisions based on their budget and travel needs.

### Datasets
The datasets used in this project are publicly available on Kaggle:

- [Uber-Lyft Cab Prices](https://www.kaggle.com/datasets/ravi72munde/uber-lyft-cab-prices?select=cab_rides.csv)
- [Weather Data](https://www.kaggle.com/datasets/ravi72munde/uber-lyft-cab-prices?select=weather.csv)

### Data Description

**Strengths of the Datasets:**
- **Uber-Lyft Cab Prices**: Contains comprehensive data on cab rides, including distance, cab type, time stamp, destination, source, price, and surge multiplier.
- **Weather**: Provides detailed weather conditions, such as temperature, cloud cover, air pressure, rain, humidity, and wind speed.

**Limitations:**
- **Uber-Lyft Cab Prices**: Limited to data from specific cities and lacks demographic information.
- **Weather**: Covers only a few cities and a short time period, with no data on extreme weather events.

### Data Cleaning and Integration
The datasets were cleaned and integrated by extracting relevant information from the Epoch timestamp and merging them based on the common timeframe and location.

### Data Visualization and Analysis

#### Question 1: Factors Influencing Uber and Lyft Cab Prices, and how do they vary by city and time of day?

- **Descriptive Analysis**: What are the average cab prices for Uber and Lyft in each city?
  <img width="452" alt="image" src="https://github.com/user-attachments/assets/5142dea7-6859-4e9c-b944-bf8ba0147349">
  <br><br>
  - Created two sheets to visualize the average unit prices and hours for different cab types. The first sheet shows the overall average unit price and hour for each cab type. The second sheet shows the average unit price and hour for a particular source to destination. The visualization of the average cab prices by hour and source-destination helps in understanding the variations in the cab fares.

- **Predictive Analysis**: Can we predict cab prices based on factors such as distance and time of day?
  <img width="452" alt="image" src="https://github.com/user-attachments/assets/37b6f263-10b9-4c89-9728-a1dc59912b84">
  <br><br>
  - The first sheet shows the average unit price based on the shortest distance for a specific time. The second sheet shows the average unit price based on the longest distance for a specific time. The analysis revealed that the distance and time are significant factors that affect cab prices. The average unit price for the shortest distance is lower compared to the average unit price for the longest distance. This indicates that the distance of the cab ride has a direct impact on the cab fares.

- **Prescriptive Analysis**: Can we recommend the best times to use Uber and Lyft to get the lowest prices?
  <img width="452" alt="image" src="https://github.com/user-attachments/assets/26d3942b-633e-4370-a9b4-39fe16386768">
  <br><br>
  - The sheet shows the average unit price for each cab type during different times of the day, and the trend line shows the estimate of the trend going on for the prices. I used the sheet to determine which cab type service will be cheaper during specific times of the day. The analysis revealed that the time of day and cab type are significant factors that affect cab prices. The average unit price is higher during peak hours compared to non-peak hours for all cab types. However, the analysis shows that some cab types are cheaper during specific times of the day.

#### Question 2: Impact of Weather Conditions on Cab Prices

- **Descriptive Analysis**: How do typical weather conditions affect the prices for Uber and Lyft?
  <img width="452" alt="image" src="https://github.com/user-attachments/assets/10c3f3a9-b4aa-4739-b2a2-f8e173032298">
  <br><br>
  - The dashboard has two sheets. In the first sheet, I have added clouds, humidity, pressure, rain, and wind to the "Columns" section and average unit price to the "Rows" section. Here I compare the prices of different cab types based on the weather factors. The second sheet contains the trend line, which shows the estimated trend line based on the average unit price for a specific time of day, also containing the source (location) from where the cab is booked. The analysis revealed that weather factors have a significant impact on cab prices. The dashboard shows that during rainy weather, the cab prices are generally higher compared to non-rainy weather conditions. Cab prices are also higher during peak hours compared to non-peak hours for all cab types.

- **Predictive Analysis**: How to choose a ride service at certain times based on rain?
  <img width="452" alt="image" src="https://github.com/user-attachments/assets/e52877fb-da94-4a56-b83c-6a0cef350c7d">
  <br><br>
  - To create this dashboard, I have developed a visualization that predicts the average unit price of a cab from a particular source based on the presence of rain during a specific time of day.

- **Prescriptive Analysis**: How should Uber and Lyft adjust prices based on weather conditions?
  -  Based on the visualization, it can be observed that users tend to book a cab service during the onset of rain or heavy rainfall, as there are no cab rides booked while it is already raining. This could be attributed to users waiting for the rain to stop or booking when they see it has started raining and might get worse. Additionally, it is evident that Uber is more responsive to rain as its pricing drastically changes with the onset of rain, whereas Lyft shows a relatively smaller change in pricing with changes in rain. 




#### Question 3: Comparing Cab Prices Between Uber and Lyft

- **Descriptive Analysis**: How do cab prices vary based on pick-up and drop-off locations?
  <img width="452" alt="image" src="https://github.com/user-attachments/assets/dcfd29db-4a99-433d-b4e4-5856e27fa46f">
  <br><br>
  - In order to create this dashboard, I have developed visualizations for various cab types offered by Uber and Lyft. The comparison depicts the cab prices for each location based on the specific time of the day for specific pick-up and drop-off locations.

- **Predictive Analysis**: Can we predict which service (Uber or Lyft) will be cheaper for a given trip?
  <img width="452" alt="image" src="https://github.com/user-attachments/assets/a7b5cda6-e0e8-4b8c-b6de-99515eea07f3">
  <br><br>
  - Developed two sheets that provide insights on the factors affecting the cab prices. The first sheet shows the average unit price of cab types based on weather conditions at a specific time of the day. This sheet contains a scatter plot with the weather conditions as the independent variable and the average unit price as the dependent variable. The second sheet shows the average prices (low, mean, and high) for Uber and Lyft based on several factors, including the rain, source, and destination at a specific time of the day. The analysis can also help cab companies to develop pricing strategies that cater to different customer segments based on the time of day, cab type preferences and weather conditions.

- **Prescriptive Analysis**: Can we recommend which service (Uber or Lyft) to use based on the price and other factors such as distance and time of day?
  - Included graphs that depict the prices of various cab options based on location, time of day and rain conditions.



### Lessons Learned
I have learned the importance of understanding the data and how to represent it through visualization. Gained experience using Tableau for creating and interpreting visualizations and understanding various types of data visualization. Effective communication of findings through visualization was a key takeaway.

### How to Run the Project
1. Clone the repository.
2. Open the project in Tableau.
3. Ensure all necessary datasets are available.
4. Run the visualizations to explore the data and insights.

### Conclusion
This project provided insights into the pricing strategies of Uber and Lyft. By analyzing various factors such as time of day, distance, and weather conditions, I was able to recommend the most cost-effective ride options for consumers.
