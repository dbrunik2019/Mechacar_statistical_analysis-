# MechaCar_Statistical_Analysis
MechaCar_Statistical_Analysis
### overview 
Jeremy is looking into a new Auto project. There are production issues and we are looking to get insight from the data to help expedite these issues.We used the basics of statistics and hypothesis testing to test certain qualities of the mechaCar. My background with the CFA exams prepared me nicely for this content, and it was good to revist the concepts of linear regression, P values, and Hypothesis testing. 

## Deliverables
Deliverable 1 Linear Regression to Predict MPG
Deliverable 2 Summary Statistics on Suspension Coils
Deliverable 3 T-Test on Suspension Coils
Deliverable 4 Design a Study Comparing the MechaCar to the Competition

### Data sources and software
Data Source MechaCar_mpg.csv and Suspension_Coil.csv
Data Tools tidyverse, dplyr, ggplot2 and MechaCarChallenge.RScript.
Software RStudio and R

### del 1
![call for  regression summary stats](https://user-images.githubusercontent.com/100965117/176709396-c66deee9-90eb-4cf1-b8fb-fa389293dc9e.PNG)

1. Vehicle lenght and clerance are non random variace contributors. Size and clerance impact miles per gallon on mecha car. Weight, spoiler angle and AWD have P values that indicate random varaince, meaning that they are not significant variables. 
2. P values is smaller than the .05 so we REJECT THE NULL. the P is smallest level at which you can reject the null. so if we were to go over the P, then we would ACCEPT THE NULL. here though, we reject. 
3. R squared is a level of quality. this is the predicitve power of the model, the higher the R^2 the higher the explanatory power of the model. SO here, we can say that the R squared is high enough to have some explanatory power for this mechacar model.
### del 2
Summary statisics provided below. 
#### lot summary 
![lot_summary mean medain variance sd](https://user-images.githubusercontent.com/100965117/176709455-984e2dc0-c156-4149-a681-6728cb6f45c1.PNG)

#### total _ summary 
![total_summary mean median variance sd](https://user-images.githubusercontent.com/100965117/176709511-0c9d6d75-54b4-44b5-b892-b4f09ddea71a.PNG)



Box plot 
![Capture](https://user-images.githubusercontent.com/100965117/176709592-31fa47e2-048f-4820-b41e-31dec3fcfb66.PNG)

#### del 3
T tests
![T test results](https://user-images.githubusercontent.com/100965117/176709643-ca8b4720-f4a4-4030-9747-8c89de60e298.PNG)


#### Del 4 (create a test for variable quality) 
you could use a multiple regression to test every single value to determine if they are all valid. 
Safety Feature Rating Independent Variable
Current Price (Selling) Dependent Variable
Drive Package  Independent Variable
Engine (Electric, Hybrid, Gasoline  Conventional) Independent Variable
Resale Value Independent Variable
Average Annual Cost of ownership (Maintenance) Independent Variable
MPG (Gasoline Efficiency) Independent Variable

Mecha cars Analaysis -David John Brunik
