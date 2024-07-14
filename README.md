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

![Visualization](https://github.com/user-attachments/assets/2db71d70-2e5e-4f43-877e-eabd20a1bfa9)
<br><br>
![Visualization](https://github.com/user-attachments/assets/c527b0ba-7c96-4181-8acc-943bfa15f3c0)
<br><br>
![Visualization](https://github.com/user-attachments/assets/91a8e2cf-2f0f-4e8a-b00d-0bb16304ef44)
<br><br>
![Visualization](https://github.com/user-attachments/assets/dea0c5aa-ffce-4015-964a-ebbddf34a45d)

#### Question 2: Impact of Weather Conditions on Cab Prices

- **Descriptive Analysis**: How do typical weather conditions affect the prices for Uber and Lyft?
  - We visualized the cab prices based on weather factors and time of day using Tableau.
- **Predictive Analysis**: How to choose a ride service at certain times based on rain?
  - We developed a visualization predicting the average unit price of a cab from a particular source based on the presence of rain.
- **Prescriptive Analysis**: How should Uber and Lyft adjust prices based on weather conditions?
  - We analyzed that users tend to book a cab service during the onset of rain or heavy rainfall.

![Visualization](https://github.com/user-attachments/assets/f0034a20-3acd-4ad4-a4aa-1fd68ca8e8f1)
<br><br>
![Visualization](https://github.com/user-attachments/assets/4d5f2c1b-caba-449a-90bc-923c2a2b8912)
<br><br>
![Visualization](https://github.com/user-attachments/assets/6dbcf065-9f57-4e9b-b1fe-d53721e055d2)
<br><br>
![Visualization](https://github.com/user-attachments/assets/6439970d-e9f6-4b80-a112-f11b8a99add3)

#### Question 3: Comparing Cab Prices Between Uber and Lyft

- **Descriptive Analysis**: How do cab prices vary based on pick-up and drop-off locations?
  - We developed visualizations for various cab types offered by Uber and Lyft.
- **Predictive Analysis**: Can we predict which service (Uber or Lyft) will be cheaper for a given trip?
  - We provided insights on the factors affecting cab prices using two sheets.
- **Prescriptive Analysis**: Can we recommend which service (Uber or Lyft) to use based on the price and other factors such as distance and time of day?
  - We included graphs that depict the prices of various cab options based on location, time of day, and rain conditions.

![Visualization](https://github.com/user-attachments/assets/ca2348b9-5e54-4d5d-9fa1-126dafd6561e)

### Lessons Learned
We learned the importance of understanding the data and how to represent it through visualization. We gained experience using Tableau for creating and interpreting visualizations and understanding various types of data visualization. Effective communication of findings through visualization was a key takeaway.

### How to Run the Project
1. Clone the repository.
2. Open the project in Tableau.
3. Ensure all necessary datasets are available.
4. Run the visualizations to explore the data and insights.

### Conclusion
This project provided insights into the pricing strategies of Uber and Lyft. By analyzing various factors such as time of day, distance, and weather conditions, we were able to recommend the most cost-effective ride options for consumers.
