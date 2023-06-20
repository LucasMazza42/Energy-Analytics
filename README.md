# Renewable Energy Study
This is a study into the development of renewable energy and adoption patterns around the world. 

- The first part of my research looks into understand the adoption of renewable energy in: The United States, China, Russia, India, United Kingdom and Canada 
- Let's first understand the dataset: 
- understanding the data: 
    - Entity: is the name of the contry
    - Code: code for the country 
    - Year: year studied - Updated to 2021
    - Renewables (% equivalent primary energy): The value for this indicator represents the percentage of energy consumed from renewable sources relative to the total energy consumed from all sources

1) This graph represents the percentage of energy provided by renewable energy sources from 1966 to 2021. 
<img width="1151" alt="Screenshot 2023-06-17 at 10 40 02 AM" src="https://github.com/LucasMazza42/RenewableEnergy/assets/47802441/8916540d-6bde-48a4-b308-599b292eef9d">



- Interesting insights: 
    - Canada and India peaked much earlier than other countries
    - United kindgdom has has rapid growth from 2000 to 2021
    - Canada surpasses all countries in the % of energy provided by renewable sources

2) Biggest jump from year to year in each country: 
<img width="862" alt="Screenshot 2023-06-17 at 10 39 29 AM" src="https://github.com/LucasMazza42/RenewableEnergy/assets/47802441/01a3b14d-01d9-4314-a8b2-a4ec3e1a2145">

   
   - Interesting insights: 
        - United kingdom has by far the biggest push in 2020 
        - All biggest jumps came in 2020 - interesting due to covid-19 happening at the same time. 
3) Smallest jump from year to year in each country: 
   <img width="862" alt="Screenshot 2023-06-17 at 10 40 21 AM" src="https://github.com/LucasMazza42/RenewableEnergy/assets/47802441/5da88c45-2b9c-4fd4-813f-1971960581eb">
    
    
    - Interesting insights: 
        - United Kingdoms lowest year to year usage of renewables came directly after the highest

Look into the amount of energy being provided in each country from year to year by each of the main sources of renewables: Wind, Solar, Geo Biomass, Hydro Generation: 

- WIND: 
<img width="1047" alt="Screenshot 2023-06-17 at 10 41 04 AM" src="https://github.com/LucasMazza42/RenewableEnergy/assets/47802441/951b936c-9767-4cc7-8684-53b212aa644c">


- SOLAR
<img width="1052" alt="Screenshot 2023-06-17 at 10 40 41 AM" src="https://github.com/LucasMazza42/RenewableEnergy/assets/47802441/0b716d61-02ad-4014-a816-86047344b708">


- GEO BIOMASS: 
<img width="1053" alt="Screenshot 2023-06-17 at 10 40 51 AM" src="https://github.com/LucasMazza42/RenewableEnergy/assets/47802441/03d7a1e2-eddd-4992-9006-2664f86b6303">


- HYDRO: 
<img width="1055" alt="Screenshot 2023-06-17 at 10 41 17 AM" src="https://github.com/LucasMazza42/RenewableEnergy/assets/47802441/f46b1c8f-c115-4186-9e68-9d5afcf73951">


4) Solar capacity in each country - the ability and amount of solar energy a country is able to store: 
<img width="1204" alt="Screenshot 2023-06-17 at 10 42 18 AM" src="https://github.com/LucasMazza42/RenewableEnergy/assets/47802441/1a20d9ab-47ca-493f-8ea7-c86274956bbb">

- Interesting insights: 
    - China makes a big effort to produce alot of energy through renewable efforts, but represented as a percentage of the total energy produced. It still is not as much as say Canada. 
    - China in every category is producing the most amount of total energy.


- Wind Turbine data in the USA: data source: https://eerscmap.usgs.gov/uswtdb/api-doc/#keyValue
    <img width="689" alt="Screenshot 2023-06-17 at 11 01 16 AM" src="https://github.com/LucasMazza42/RenewableEnergy/assets/47802441/f691ae14-5800-4736-a2f9-bd43e6a27392">
       
       - High concentration in central United States

- Age of manufacturing: 
      <img width="1046" alt="Screenshot 2023-06-17 at 11 02 48 AM" src="https://github.com/LucasMazza42/RenewableEnergy/assets/47802441/a2f40651-23a2-4665-96f0-b16aabf5883c">
- Top 20 years of manufacturing: 
<img width="1055" alt="Screenshot 2023-06-17 at 11 16 42 AM" src="https://github.com/LucasMazza42/RenewableEnergy/assets/47802441/fb839f2b-5784-4876-bfd1-58715025ecc8">

- Top 10 companies with the most amount of turbines in the USA:
<img width="1141" alt="Screenshot 2023-06-17 at 11 10 05 AM" src="https://github.com/LucasMazza42/RenewableEnergy/assets/47802441/d1901b0a-b0dc-4c64-bc52-fb87a659eb62">
    
    - GE is the top producer
    - AVG cost of wind turbine 2 to 4 million 


- Wind turbine statisitcs:
    - Costs are decreasing 
        - Source: https://meic.org/cost-of-wind-vs-fossil-fuels/
            - Wind turbine cost per megawatt-hour between $32 and $62 
            - Coal cost per megawatt-hour between $57 and $148 
    - Turbine capacity is increasing: 
        - <img width="1266" alt="Screenshot 2023-06-17 at 2 12 06 PM" src="https://github.com/LucasMazza42/RenewableEnergy/assets/47802441/8a85834a-6d68-4425-a778-0a607d1b5d73">  
    - Growth of the amount of turbines in the US: 
    <img width="876" alt="Screenshot 2023-06-17 at 2 44 15 PM" src="https://github.com/LucasMazza42/RenewableEnergy/assets/47802441/aecd1e19-005c-4af2-8985-0437015b32d1">
    
    
ESTIMATING OPTIMAL CONDITIONS: 

- Data collected from SCADA system in Turkey. Measurements were taken in 10 minute intervals. Source : https://www.kaggle.com/datasets/berkerisen/wind-turbine-scada-dataset

- Description: 
    - Date/Time (for 10 minutes intervals)
    - LV ActivePower (kW): The power generated by the turbine for that moment
    - Wind Speed (m/s): The wind speed at the hub height of the turbine (the wind speed that turbine use for electricity generation)
    - Theoretical_Power_Curve (KWh): The theoretical power values that the turbine generates with that wind speed which is given by the turbine manufacturer
    - Wind Direction (°): The wind direction at the hub height of the turbine (wind turbines turn to this direction automaticly)
        - Wind turbine will automatically rotate in order to be in the direction to harvest the most amount of energy 
- Power produced vs wind speed: 
    - <img width="978" alt="Screenshot 2023-06-18 at 9 15 34 PM" src="https://github.com/LucasMazza42/RenewableEnergy/assets/47802441/ad6246c9-1c4a-44d3-961f-0ac4bec3af8c">
    - looks similar to a Sigmoid distiribtion - this could be useful in prediction
    

- Power vs wind direction: 
    - <img width="853" alt="Screenshot 2023-06-20 at 2 41 37 PM" src="https://github.com/LucasMazza42/RenewableEnergy/assets/47802441/886c90b3-d5ea-4b5f-852e-5c1c3cf6ea0d">
    - Not too many insights...high right skew just due to abundance of datapoints at specific angles of the hub - visual is a little miss leading
    - To drive the point home - this is a plot of the frequency of the wind direction in the dataset: 
        <img width="840" alt="Screenshot 2023-06-20 at 2 32 10 PM" src="https://github.com/LucasMazza42/RenewableEnergy/assets/47802441/51dbce6e-5240-4850-b8a1-aeb1f502d21c">
     - The frequency of the angle of the hub is likely due to the weather patterns in the area. 


- Model for predicting output power:
    - This MLR model aims to predict the amount of power given the windspeed and the direction of the wind: 
    - <img width="852" alt="Screenshot 2023-06-18 at 9 28 52 PM" src="https://github.com/LucasMazza42/RenewableEnergy/assets/47802441/ac04d7f4-f1c7-4146-8c70-91e519175db1">
    - <img width="329" alt="Screenshot 2023-06-18 at 9 30 56 PM" src="https://github.com/LucasMazza42/RenewableEnergy/assets/47802441/29967b19-9585-4df3-ae4d-dff9b14359f3">
    - R^2 value can be summed up as: 
        - How good does our model fit the data
        - Represented as a value between 0, 1
        - Higher value -> better fit
        - .83 means out fit is GOOD
    - MSE value can be summed up as: 
        - Average difference between actual value and the predicted from the model - Sum of the average error 
        - ...more context is required to interpret this number in this situation








    




