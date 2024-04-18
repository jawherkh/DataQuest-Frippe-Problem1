# DataQuest-Frippe-Problem1

## _**Overview**_ :

DataQuest is a hackathon that occurs on the 24th and 25th of February where every time unit, new machine learning problems show up. It is a 24 hours straight hackathon in which a developer environment with all the needs provided to chill the game is provided. DataQuest has remarkable prizes (5000 Dinars) and takes into consideration the beginner and intermediate levels.

In this specific problem we will focus on regression with a fairly simple dataset where the scoring is going to involve the r2-score. So, the heigher the r2-score the higher the rank you get. 

## _**Description**_ :
Abdou's Frippe Fashion Assistant!
Abdou, an IEEE INSAT CS member, is embarking on a treasure hunt at Frippe, a thrift store bursting with unique finds to sell. Our job is to make the best price estimation for Abdou to make him a better trader.

Our Mission: Analyze each garment based on key criteria to determine the price estimation for Abdou:

+ Marka: Brand
+ Naw3: Price
+ Modhkhom: Formality (formal, casual, etc.)
+ 9at3a: Type of clothing (shirt, pants, etc.)
+ Khochn: Fabric thickness
+ Toul: Garment length
+ 3ordh: Garment width
+ R: Red color value
+ G: Green color value
+ B: Blue color value
+ soum: The estimated price


Remember, these criteria correspond to the columns in our dataset! Let's help Abdou discover hidden gems and build his own clothes store that reflects his style and budget.

Good luck!

## Evaluation : 
R2-Score is the classifier in this problem. Score will be between -1 and 1. The score that will add to the final formula is (R2+1)/2

Submissions are evaluated on area under the ROC curve between the predicted probability and the observed target

## Submission File: 

For each ID in the test set, you must predict a probability for the TARGET variable. The file should contain a header and have the following format:


```
ID,TARGET
2,0
5,0
6,0
etc.

```

