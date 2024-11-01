# Electric-Vehicles-Dataset-Data-Analaysis
Performed Data Cleaning and Data Analysis of the Electric Vehicles Dataset to find the relationship between the features in the dataset and visualize the same using matplotlib and seaborn.

The notebook provides a data analysis of an electric vehicle dataset, covering several aspects:

1. **Data Loading & Cleaning**: 
   - Imports necessary libraries (`numpy`, `pandas`, `matplotlib`, `seaborn`).
   - Loads the dataset and displays an initial preview.
   - Checks for NaN and infinite values, removing invalid entries from the `FastCharge_KmH` column.

2. **Exploratory Data Analysis (EDA)**:
   - Analyzes and visualizes various features:
     - **Body Style**: Counts each vehicle body style and highlights the most common (SUV) and least common styles (MPV and Station).
     - **Powertrain Types**: Uses a pie chart to show that AWD is the most common type.
     - **Range and Price Correlation**: Uses a scatter plot, finding a positive correlation between range and price.
     - **Rapid Charging**: Lists vehicles without rapid charging capability.
     - **Fast Charge Performance**: Identifies vehicles with the highest and lowest values in `FastCharge_KmH`.
     - **Brand Analysis**: Displays the number of models per brand, showing Tesla as the brand with the most models.

3. **Advanced Visualizations**:
   - **Plug Type vs Price**: A swarm plot reveals that Type 2 CCS plug types cover a broader price range.
   - **Seats Analysis**: Averages the number of seats across vehicles.
   - **Efficiency by Segment**: Uses a bar plot to show segment efficiency, noting that Segment N has the highest efficiency.

The notebook effectively uses plots and queries to uncover relationships and patterns within the dataset.
