# Assignment 6 Part 2 - Writeup

---

## Question 1: Feature Importance

Based on your house price model, rank the four features from most important to least important. Explain how you determined this ranking.

**YOUR ANSWER:**
1. Most Important: SquareFeet
2. Bathrooms 
3. Bedrooms
4. Least Important: Age

**Explanation:**
I looked at the numbers the odel gave me(the coeffiecients). The bigger the number, the more important the feature. SquareFeet had the biggest one, and Age had the smallest.


---

## Question 2: Interpreting Coefficients

Choose TWO features from your model and explain what their coefficients mean in plain English. For example: "Each additional bedroom increases the price by $___"

**Feature 1:**
SquareFeet:
The model says that every extra square foot makes the house cost a lot more, like around $150-$200 more per square foot.

**Feature 2:**
Age:
The model shows that the older the house is, the cheaper it gets by a few thousand dollars every year.

---

## Question 3: Model Performance

What was your model's R² score? What does this tell you about how well your model predicts house prices? Is there room for improvement?

**YOUR ANSWER:**
My model's R2 score was around .85-.92. This means the model is "pretty good" at guessing house prices.
It's not perfect, because houses depend on more things than just the four features used, like the neighbood the house is in & the overall condition/quality of the house.



---

## Question 4: Adding Features

If you could add TWO more features to improve your house price predictions, what would they be and why?

**Feature 1:**
Location

**Why it would help:**
Where the house is matters a lot. Nie neighborhoods usually mean higher prices.

**Feature 2:**
Garage Size

**Why it would help:**
Houses with bigger garages or more parking spots are usually worth more, so adding this would help. 

---

## Question 5: Model Trust

Would you trust this model to predict the price of a house with 6 bedrooms, 4 bathrooms, 3000 sq ft, and 5 years old? Why or why not? (Hint: Think about the range of your training data)

**YOUR ANSWER:**
I wouldn't fully trust the model to predict a house with 6 bedrooms, 4 bathrooms, 3000 sq ft, and 5 years old unless our training data had houses like that. If the numbers are bigger than anyhting the model saw before, the prediction might not be accurate. 