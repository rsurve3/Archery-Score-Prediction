# Archery-Score-Prediction


**Executive Summary:**

**Motivation for the project:**
Aristotle said, “It concerns us to know the purposes we seek in life, for then, like archers aiming at a definite mark, we shall be more likely to attain what we want”. As students, we are just beginning our careers, so we have a lot to concentrate on. However, with so many different things, we occasionally become overwhelmed with work. Like Aristotle said, we can accomplish our goals if we set them and work towards them. This is why, we as a group took archery score as our project topic.

**Abstract:**
Our objective is to identify factors which would give higher Archery Score. We chose factors such as Arrow Length, Target Face Size, Distance to Target, etc. for our experiment. In total, we have eight factors in our experiment. We used Fractional Factorial Design with 2 replications to save time and resources. In our experiment, the individual talent of the archer is not being considered as a factor to maintain consistency. Our data analysis showed that the archer should shoot their arrow on a compound target face size, the arrow of the wobble should be low and there should be high wind speed. We are using JMP software for our project.

**Description of the Experiment:**

**Factors and Levels:**
In our experiment, we included eight factors which we thought are important to maximize the archery score. 
1.	Arrow Length – The archer can choose between two arrows.
a)	Short Arrow (27 inches)
b)	Standard Arrow (31 inches)

2.	Target Face Size – The archer can choose between two target sizes.
a)	Compound Size (80 cm)
b)	Recurve (122 cm)

3.	Distance to Target – The archer can choose between two distances between them and the target.
a.	Low Distance (<40 yards)
b.	High Distance (>60 yards)
4.	Arrow Diameter – The archer can choose between two sizes in arrows.
a.	Ultra-Micro (4 mm)
b.	Standard (6.5mm)

5.	Wobble – The wobble of an arrow has two levels.
a.	Low Wobble (<5 mm)
b.	High Wobble (>5 mm)

6.	Wind Speed – The wind speed at the time of shooting has two levels.
a.	Low Wind Speed (<5 mph)
b.	High Wind Speed (>5 mph)

7.	Type of Bow – The archer can choose between two types of bows.
a.	Long Bow
b.	Cross Bow

8.	Type of Arrow – The archer can choose between two types of arrows.
a.	Aluminum Arrow
b.	Carbon Arrow

Selection of Response Variable:
Our response variable is “points scored after 1 run of archery”. It ranges from 0 to 10. Our objective is to maximize it.

Number of Replications:
We took 2 replications and later took its average as our final score.

Block Variable:
To maintain consistency and to avoid noise, we chose the archer as our blocking variable. There are two archers as a part of our experiment.



**Design of Experiment:**

As we have a total of 8 factors, total runs would be 28 = 256 for conducting a full factorial design experiment. Now, conducting this experiment would take a lot of time and resources. So, we chose to do “Fractional Factorial Design” with 32 randomized runs. 
2iv8-3 = 25 = 32 runs. We tried with two players, so blocking variable has two level. Since we wanted to eliminate noise of players, we took 16 runs with one block and other 16 runs with another block.

Number of blocks = 2 so block size is 16.

![image](https://user-images.githubusercontent.com/122759737/214105961-59894f6c-7c52-4167-b52c-2ee3e5eaca39.png)

**Design Table:**

Below is a snapshot of our Design Table. We took randomized order of all 32 runs. We took 2 replications, and our response variable is the average of those two replications.

 
![image](https://user-images.githubusercontent.com/122759737/214105993-cbdeec89-74b0-49c3-8fb3-f5e3d92d768a.png)


**Analysis of Data:**
Verification of Normality:
To check the normality of our data (response variable), we chose the Shapiro-wilk Test. 
 
![image](https://user-images.githubusercontent.com/122759737/214106020-a55a859f-7ee0-45d1-9d08-f7fa2603a5db.png)


**The Half Normal Plot Analysis:**
From the Half Normal Plot, we see that factors “Target Face Size”, “Wind Speed” and “Wobble” are away from straight line when compared with all factors. This means that they are not normally distributed with a mean of zero and constant variance. This concludes that they are significant. 
The remaining five factors are near to line so we can say that they are normally distributed with a mean of zero and a constant variance which means do not have a significant effect.
 
![image](https://user-images.githubusercontent.com/122759737/214106055-7985fabe-8895-4003-a180-3f775f5b9fb2.png)


**Model Summary:**

After Half-Normal Plot Analysis, we worked on Model Summary for further insights on factors. We found out that three factors are significant in our experiment. They are Target Face Size, Wobble and Wind Speed. For the remaining 5 factors, the p-value is not significant.

 
![image](https://user-images.githubusercontent.com/122759737/214106090-a9459d33-5d5b-4f55-bcac-2edd0527ab1e.png)



**Analysis of Variance (ANOVA) and Regression Model:**
After working on verification of normality, half normal plot analysis and model summary, we finally worked on analysis of variance. The model had 8 degrees of freedom. The overall p-value is 0.0116, which means that the model is significant.
From Regression Table, we can see that, the p-value of following factors – Target Face Size, Wobble and Wind Speed is less than 0.05. This proves that all three factors are significant. 

Our Regression Equation is:
Score = 6.408 – 0.853 Target Face Size (Recurve) + 1.044 Wobble (Low) –1.088 Wind Speed (Low)


**Analysis of Variance:**

 ![image](https://user-images.githubusercontent.com/122759737/214106144-6d4dc446-1137-4118-bd86-39c79dc91288.png)


**Parameter Estimates:**

![image](https://user-images.githubusercontent.com/122759737/214106181-a9ff4763-e3f0-40cd-bd40-a5799f887725.png)


**Conclusions and Recommendations:**
After conducting our experiment, we can obtain Maximum Archery Score if keep the following factors consistent:
1.	Compound Target Face Size
2.	Low Wobble
3.	High Wind Speed

Since other factors were proved to be insignificant, we can choose any of their two levels:
1.	Arrow Length can be Short or Standard
2.	Distance to Target can be High or Low
3.	Arrow diameter can be Standard or Ultra-Micro
4.	Bow can be Cross Bow or Long Bow
5.	Arrow can be made of Aluminum or Carbon

For further analysis, we can try with more players, include factors which resemble their talents and run more replications.

 
