# Predicting-the-City_Cycle-in-Fuel-Consumption
## Background Information

### Data Files
The main file we used is mpg.data.xlsx, which contains information about eight car attributes (e.g., MPG, cylinders, horsepower, car name). These helped us provide car rental companies the necessary information  when updating their fleets by predicting fuel efficiency (MPG).

### Resources
The dataset is provided under the Creative Commons CC0 1.0 Universal (CC0 1.0) 'Public Domain Dedication' license ( https://creativecommons.org/publicdomain/zero/1.0/ ) , so we are authorized to use it in this project.

### Data Description
We were provided with the Auto MPG dataset, which includes the following characteristics:

![image](https://github.com/user-attachments/assets/9e47cf20-def0-43d5-b60e-475380100b5b)

Our table contains eight attributes, as shown below:

![image](https://github.com/user-attachments/assets/792c14c7-0577-4f7d-b6ae-13a2b1d251b4)

### Data Processes
#### Exploratory Data Analysis
The first step in our analysis was exploring the data. We began by importing the necessary Python libraries to visualize the data and calculate key metrics for our model. Below you can see some of our frequently used commands for that step.

![image](https://github.com/user-attachments/assets/44edf878-c6ed-48af-b91d-74f1c84c5711)

![image](https://github.com/user-attachments/assets/bfad36f3-0204-42ac-be51-2741745657ae)

After identifying key metrics during the EDA step, we proceeded with adjustments and corrections for erroneous values.

![image](https://github.com/user-attachments/assets/3165264a-36fb-4e0a-a683-128cc1037a3d)

![image](https://github.com/user-attachments/assets/61e359f7-495d-4cad-96fa-098c12d63cfb)

![image](https://github.com/user-attachments/assets/508aafc6-43b5-44f5-bcaf-c9746b2e2d76)

To end the exploratory part of the project we analyzed continuous variables by plotting our key variable 

![image](https://github.com/user-attachments/assets/f8c25ea5-92e6-499a-9d4c-9dffee5d8a15)

![image](https://github.com/user-attachments/assets/c628743b-38fe-4bda-8458-7b1c087a1e25)

Following that, we analyzed trends in fuel efficiency and model year over time.
![image](https://github.com/user-attachments/assets/87a6c81d-041e-4c1d-94d0-4732a38454dd)
![image](https://github.com/user-attachments/assets/345a570d-0345-4191-bc26-8867aebaa0ec)

#### PreProcessing 
##### For the preprocessing, first step was to drop unwanted columns and check for null values and duplicates. 
![image](https://github.com/user-attachments/assets/5b2e9cdf-f9ba-4bb8-a143-f72dd88d435e)

![image](https://github.com/user-attachments/assets/c80c450e-847a-44cb-9b91-811537eb6382)

##### After dropping null values for our target variable and replacing nulls in other columns with median, we changed the data type for columns 'displacement' and 'horsepower' as shown below:

![image](https://github.com/user-attachments/assets/7f074e3d-8ce3-4e01-9fdf-8dc84c088d0f)

For feature extraction, we splitted the 'car name' column into brand and model. Made some corrections for the name of the brand and one hoted encoded the final ones into the fifteen largest and others.

![image](https://github.com/user-attachments/assets/ba253599-936a-48cc-916e-e79908824dce)

![image](https://github.com/user-attachments/assets/cb9ec789-2d5e-4a21-a028-6339511420b8)





















