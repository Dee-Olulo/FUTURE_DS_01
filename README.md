#**Titanic Survival Analysis: An Exploratory Data Analysis (EDA) Journey**

## Description:
In this notebook, we delve into the Titanic dataset to uncover insights about the factors influencing passenger survival rates. Through a series of visualizations and statistical analyses, we explore the impact of socio-economic status, gender, and age on survival outcomes. Key findings include the higher survival rates of first-class passengers, the prioritization of women and children during evacuation, and the age distribution's role in survival likelihood. This comprehensive EDA provides a clear understanding of the historical data and highlights significant patterns that shaped the tragic event.

## **Data Understanding**
**Dataset Overview**
- Rows: 891 (representing passengers)
- Columns: 12 (representing variables that may contribute to survival prediction)

**Dataset Variables**

- *Survival:* Target variable, indicating whether a passenger survived or not (0 = No, 1 = Yes).
- *Pclass:* Socio-economic status of the passenger. It's a proxy for wealth and class division.
1 = Upper class
2 = Middle class
3 = Lower class
- *Sex:* Gender of the passenger (male/female).
- *Age*: Age of the passenger
- *SibSp:* Number of siblings or spouses aboard with the passenger. This gives insights into family structure and travel companions.
- *Parch:* Number of parents or children aboard with the passenger.
- *Ticket:* Passenger's ticket number. This is a unique identifier but may have limited relevance for survival prediction unless linked to ticket prices or groups.
- *Fare:* The fare paid by the passenger. This could relate to the passenger's
class or socio-economic status.
- *Cabin:* Cabin number of the passenger. Not all passengers have a recorded cabin, leading to missing data.
- *Embarked:* Port where the passenger boarded the Titanic.
C = Cherbourg
Q = Queenstown
S = Southampton

##EDA

![image](https://github.com/user-attachments/assets/037ba258-7201-4294-889b-e2878af1f4d1)

- Observations
- It shows that young adultsaged between 20 and 30 were the most represented age group on board

![image](https://github.com/user-attachments/assets/6f843156-e4be-4a02-9e3d-10917b223e56)
- Observations
- 0=no, 1= yes
- Females had a higher survival rate compared to males across all passenger classes. This suggests that women were given priority during the evacuation process, aligning with the “women and children first” protocol.

![image](https://github.com/user-attachments/assets/5878bba4-1411-4c89-933c-8202930be20d)
- Observations
- Younger passengers, particularly children, had higher survival rates compared to older passengers. This trend was more pronounced in first and second classes, where younger passengers were more likely to survive.

## Conclusion
### **Conclusion**
1. Survival Rates by Passenger Class (Pclass):
- First-class passengers had the highest survival rates, while third-class passengers had the lowest. This indicates a significant socio-economic factor influencing survival, with wealthier passengers having better access to lifeboats and safety measures.
2. Impact of Sex on Survival:
- Females had a higher survival rate compared to males across all passenger classes. This suggests that women were given priority during the evacuation process, aligning with the “women and children first” protocol.
3. Age Distribution and Survival:
- Younger passengers, particularly children, had higher survival rates compared to older passengers. This trend was more pronounced in first and second classes, where younger passengers were more likely to survive.
4. Family Size
- People travelling with smaller(medium) families had a higher chances of surviving in comparission to people with large families and the one travelling alone.



