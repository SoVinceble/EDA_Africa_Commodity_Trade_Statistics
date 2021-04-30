# Exploratory Data Analysis on Commodity Trade Statistics from 1988 to 2016

Introduction
The main objective was to carry out preliminary exploration of the automobile dataset. The goal was to select the right attributes for use in the computation of “How African countries perform compared to the rest of the world”, “Which year had the highest import and export”, “How do categories and commodities rank in price, on the continent”, “How do African countries rank by trade”, “Africa has more Imports or Exports” and others.

DATA CLEANING
1.	Removing unused columns
2.	Removing duplicated rows if any
3.	Used a heatmap to visualise the missing values
 
![image](https://user-images.githubusercontent.com/9653652/116586784-1f0b2500-a91a-11eb-9603-103f31ae2e76.png)
![image](https://user-images.githubusercontent.com/9653652/116586795-229eac00-a91a-11eb-83d8-752cb481ad2d.png)

MISSING DATA

1.	I realized that there was missing data on the ‘weight’ and ‘quantity’ entries.
2.	Steps taken in order to handle the missing data was to remove the entries with empty or null values in their respective columns.

DATA STORIES AND VISUALIZATIONS


1)	 How African countries perform compared to the rest of the world?

![image](https://user-images.githubusercontent.com/9653652/116586835-2cc0aa80-a91a-11eb-9f19-197bd7ef3fab.png)
![image](https://user-images.githubusercontent.com/9653652/116586854-2f230480-a91a-11eb-8ff0-a090014f32d0.png)
![image](https://user-images.githubusercontent.com/9653652/116586915-3cd88a00-a91a-11eb-879a-a02bbb8b4648.png)
![image](https://user-images.githubusercontent.com/9653652/116586933-4235d480-a91a-11eb-8dd9-b0c71fe66550.png)
 
It's unfortunate to see that the continent performs quote poorly in relation to the rest of the world.

From the above representations it only amounts to about 5% of the worlds trade. 
2)	 When did the largest and heaviest trades take place?

![image](https://user-images.githubusercontent.com/9653652/116586965-4a8e0f80-a91a-11eb-9c78-295ee282a86b.png)
 
I can observe an upsurge during the years of 2012 to 2014

3)	 How does Africa compare to the world in terms of Surplus and Deficit?

![image](https://user-images.githubusercontent.com/9653652/116587061-64c7ed80-a91a-11eb-8b34-cb703cf78806.png)
![image](https://user-images.githubusercontent.com/9653652/116587085-698ca180-a91a-11eb-8953-c1e8292cbdec.png)

It's impressive to see that in that area Africa performs better than the rest of the world.

From the findings above we realise that while the world started running on deficit from 1997 to 2016, which stands for 19 years. African nations were not that much affected. 


4)	 Africa has more Imports or Exports?

![image](https://user-images.githubusercontent.com/9653652/116587140-78735400-a91a-11eb-86ab-f667eeb9c965.png)
 
There is 3x more imports, and a high margin at it.


5)	 Which country has the most Exports overall?

![image](https://user-images.githubusercontent.com/9653652/116587178-83c67f80-a91a-11eb-863c-8a98175ffb49.png)

Algeria followed by South Africa.

 
6)	 Which country has the most Imports overall?
 
![image](https://user-images.githubusercontent.com/9653652/116587253-99d44000-a91a-11eb-904d-0ba10661e142.png)

Egypt is on top and Algeria is the next up, followed by Botswana which is interesting to see it showing up here, because of their relatively small population. 


7)	 Which year had the highest import and export?

![image](https://user-images.githubusercontent.com/9653652/116587311-a6589880-a91a-11eb-9e23-9b2d9400fea0.png)

From the graph we can see that 2011 had the highest Export and 2014 had the highest Import.


 
8)	 How do African countries rank by trade?

![image](https://user-images.githubusercontent.com/9653652/116587361-ac4e7980-a91a-11eb-99fd-0e1772554ae1.png)
![image](https://user-images.githubusercontent.com/9653652/116587380-afe20080-a91a-11eb-82a8-b679569b3a98.png)
![image](https://user-images.githubusercontent.com/9653652/116587390-b2dcf100-a91a-11eb-92c1-7978de7cb453.png)
![image](https://user-images.githubusercontent.com/9653652/116587403-b53f4b00-a91a-11eb-8b44-1ff837530a75.png)

Angola is the dominating country when it comes to weight and quantity.

When it comes to amount of trades Algeria takes the top spot as well as quantity of goods traded/

Egypt competes with Angola on volume of trade but Egypt has the upper hand
 
9)	 Which is the top Import/Export of Commodities and Categories in Africa?

![image](https://user-images.githubusercontent.com/9653652/116587463-c4be9400-a91a-11eb-8b85-0e856b88aba1.png)
![image](https://user-images.githubusercontent.com/9653652/116587476-c8521b00-a91a-11eb-82be-c6f901f18692.png)
![image](https://user-images.githubusercontent.com/9653652/116587492-cbe5a200-a91a-11eb-8a90-94e8fa95da44.png)
![image](https://user-images.githubusercontent.com/9653652/116587502-cee09280-a91a-11eb-8980-3e432d5296d5.png)
 
Petroleum Oils is the biggest commodity getting imported and export on the continent. 

Mineral fuels oil is the biggest category getting imported and export on the continent.


10)	 How do categories and commodities rank in price in the continent?

![image](https://user-images.githubusercontent.com/9653652/116587524-d6a03700-a91a-11eb-9256-4409be7e349a.png)
![image](https://user-images.githubusercontent.com/9653652/116587566-def87200-a91a-11eb-8c43-1c4a8eaec65c.png)
![image](https://user-images.githubusercontent.com/9653652/116587576-e28bf900-a91a-11eb-867e-a56ceba5aa2c.png)

 Petroleum Oils generate the highest amounts

Egypt, Angola and Libya are the top trades in the continent. Libya seems to have a sharp drop in trades in the later years, I take it that those are results caused by the wars taking place in the county.


11)	 Which is the most exported commodity of each country?

![image](https://user-images.githubusercontent.com/9653652/116587606-e881da00-a91a-11eb-87f6-5cb797f15d85.png)
 
Petroleum Oils are the commodities most exported by Algeria and Angola, which also stand out as the highest commodities in the continent.

 
12)	 Which is the most imported commodity of each country?

![image](https://user-images.githubusercontent.com/9653652/116587631-eddf2480-a91a-11eb-973a-a91ae3ffc787.png)
 
Petroleum Oils, out of all the countries Egypt imports the most as we seen previously as well

Final Observations:

Although the continent amounts to about 5% of the world's trades, overall, it has potential to grow, while still being one of the biggest Petroleum Oils traders.

From my observation 3 countries dominate the trades in the continent:

    - Algeria
    - Angola
    - Egypt

THIS REPORT WAS WRITTEN BY:  TCHISSEKE VICENTE
