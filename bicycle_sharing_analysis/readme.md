# Bicycle Sharing Data Analysis
This project analyzes the encoded customer data from Mobike and Didi. The raw csv file in the `raw_data` folder are too large to be uploaded (>80MB).

### **Results Overview**

- Daily order histogram:

<img src="./figures/day_order_histogram.png" width="800">
  
- Hourly order histogram:

<img src="./figures/hour_order_histogram.png" width="800">
    
- Effect of wind on distance:

<img src="./figures/wind_distance_compared.png" width="800">
      
- Wind levels effect:

<img src="./figures/wind_effect.png" width="800">
        
- Effect of workday or not:
        
<img src="./figures/workday_compare.png" width="800">

- End location 2D-histplot:

<img src="./figures/heatmap_end.png" width="800">

### **Note**
The 2D histplots of each journey location frequencies are plotted using professional graphical visualization tool called **folium**. Check the `output` folder to see the html heatmap in details.
