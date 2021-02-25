# Terrorist-Activity-Prediction

## Terrorist Activity Case
In thes case we have the terrorist.csv and these file consisit of different columns. From that we have to predict the future attack of terrorist.

## Columns Name
These are some of the main columns in that file. If you look at the CSV file it consist of many columns out of that I'm seleted some of them.

1. **iyear -** This field contains the year in which the incident occurred.
2. **imonth -** This field contains the number of the month in which the incident occurred
3. **iday -** This field contains the numeric day of the month on which the incident occurred
4. **Extended -** “Yes,” the duration of an incident extended more than 24 hours “No,” the duration of an incident extended less than 24 hours
5. **Provstate -** Name (at the time of event) of the 1st order subnational administrative region
6. **Latitude -** The latitude of the city in which the event occurred
7. **Longitude -** The longitude of the city in which the event occurred
8. **Vicinity -** The region in nearby location
9. **Natlty1 -** The nationality of the target that was attacked
10. **Ishostkid -** The hostage of kids
11. **Country -** This field identifies the country or location where the incident occurred
12. **City -** Name of the city, village, or town in which the incident occurred
13. **Gname -** The name of the group that carried out the attack
14. **Nkillus -** The number of U.S. citizens who died as a result of the incident
15. **Nwound -** Number of confirmed nonfatal injuries to both perpetrators and victims
16. **Nwoundus -** The number of confirmed nonfatal injuries to U.S. citizens, both perpetrators and victims
17. **Property -** The damage to property
18. **Targtype1 -** The general type of target/victim
19. **Suicide -** 1 = “Yes,” the incident was a suicide attack; 0 = “No,” there is no indication that the incident was a suicide attack
20. **Success -** Success of a terrorist strike
21. **Weaptype1 -** General type of weapon used in the incident
22. **Region -** This field identifies the region code based on 12 regions
23. **Attacktype1 -** The general method of attack and broad class of tactics used

## Task

1. **Data Analysis :** In thes file we just analize data, so that we can know more about the data. In thse data analysis file we get some sort of information, such as
   
      * Number of Terrorist Activities Each Year
      * Terrorist Activities by Region in Each Year 
      * Casualitie Happen In Every Year
      * Top 40 Worst Terror Attacks
      * Top Countries affected by Terrorist Attacks
                       
2. **Data Preprocessing :** In these file we are dealing with data so that we can fill up all NaN value. In below the column contain NaN value are showing

      * provstate   0.232 %Missing Value
      * city        0.239 %Missing Value
      * latitude    2.508 %Missing Value
      * longitude   2.508 %Missing Value
      * specificity 0.003 %Missing Value
      * natlty1     0.858 %Missing Value
      * nkill       5.676 %Missing Value
      * nkillus     35.47 %Missing Value
      * nkillter    36.853 %Missing Value
      * nwound      8.977 %Missing Value
      * nwoundus    35.611 %Missing Value
      * nwoundte    38.055 %Missing Value
      * propextent  64.74 %Missing Value
      * ishostkid   0.098 %Missing Value
      * ransom      57.411 %Missing Value
      
3. **Model Buliding :** In thse file we had apply different machine learning algorithem. Such as

      1. **Random Forest Classfier :**
      
      ![RFC](https://user-images.githubusercontent.com/62636740/109165037-1aeb4b80-77a1-11eb-9bbc-8ce05caa9580.PNG)

      2. **Decision Tree Classfier :**

      ![DTC](https://user-images.githubusercontent.com/62636740/109165216-4ff79e00-77a1-11eb-9242-f94ef300e30f.PNG)

      3. **XG Boost Classfier :**
      
      ![XGB](https://user-images.githubusercontent.com/62636740/109165343-73224d80-77a1-11eb-8ad7-4b38494e2ac4.PNG)

## Observation :

1.Terrorist acts in the Middle East and northern Africa have been seen to have fatal consequences.

2.The Middle East and North Africa are seen to be the places of serious terrorist attacks.

3.In addition, even though there is a perception that Muslims are supporters of terrorism, Muslims are the people who are most damaged by terrorist attacks.

4.If you look at the graphics, it appears that Iraq, Afghanistan and Pakistan are the most damaged countries. All of these countries are Muslim countries.

## Technologies Used:

![1](https://user-images.githubusercontent.com/62636740/109166221-77029f80-77a2-11eb-8020-2db88b4e94e0.png)

![XGB logo](https://user-images.githubusercontent.com/62636740/109166285-8d106000-77a2-11eb-8d28-2e798ebb43ff.png)


                       
                       
