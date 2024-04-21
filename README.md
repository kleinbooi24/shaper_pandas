# PANDAS

## LIBRARIES

import pandas as pd
import matplotlib as plt
import numpy as np

#Dataframe source

money_df = pd.read_csv("Money.csv")

### This is a repo of Exploratory Data Analysis using PANDAS LIBRARY in Python, to answer the following questions fom the exploratory data:

Who has made highest purchases using MPESA between the male and the Female users?
How many transections originates from MPESA for each merchant?
What is the spending relationship of a USER_HOUSEHOLD to Rent and Mortgage? Are people coming from larger family households likely to take a mortgage compared to those coming from less families or no families?
On which merchant category do youth (Age 18 -35) spent much on?
Which Gender Male or Female are the most spenders?
Who has the Highest Income between the Males and Females?
Which year was the mortgage the Highest?
Which age group spend more on Data & Wifi?
What is the trend in income levels over the years, and in which year was the income at its highest?
Which age group tends to spend the most?
Which age group has highest usage of MPESA payment method? Who’s adopting this payment method more, young or old?
Which gender, Male or Female, spends the most on shopping?
Which year did people spend the most on transportation and fuel?
Are high income earners spending more on Loan repayment vs low income earners?
Which category has the highest purchase value per month?

PROBLEM 1: Compare the average money spend (PURCHASE_VALUE) between male and female (USER_GENDER) per MPESA Payment system usage (IS_PURCHASE_PAID_VIA_MPESA_SEND_MONEY)

PROBLEM 2: Count the number of transections from MPESA per merchant (MERCHANT_NAME)

PROBLEM3: Compare the user household (USER_HOUSEHOLD) spending habit (PURCHASE_VALUE) on rent and mortgage (MERCHANT_CATEGORIZED_AS - filter rent and mortgage)

PROBLEM 4: Compare the spending habit of youth (USER_AGE - filter 18 to 35) for each category (MERCHANT_CATEGORIZED_AS)

PROBLEM 5: Compare the spending habit (PURCHASE_VALUE) of males and females (USER_GENDER)

PROBLEM 6: Compare the income (USER_INCOME) of males and females (USER_GENDER)

PROBLEM 7: Compare the spending (PURCHASE_VALUE) on mortgage (MERCHANT_CATEGORIZED_AS - filter rent and mortgage) across the years (YEAR)

PROBLEM 8: Compare the spending habit (PURCHASE_VALUE) across age groups (USER_AGE) on Data & Wifi (MERCHANT_CATEGORIZED_AS - filter Data&wifi)

PROBLEM 9: Compare the Income levels (USER_INCOME) across the years (YEAR)

PROBLEM 10: Compare the spending habit (PURCHASE_VALUE) across age groups (USER_AGE)

PROBLEM 11: Compare the MPESA usage (IS_PURCHASE_PAID_VIA_MPESA_SEND_MONEY) across different age groups (USER_AGE)

PROBLEM 12: Compare the spending (PURCHASE_VALUE) between male and female (USER_GENDER) on shopping (MERCHANT_CATEGORIZED_AS - filter shopping)

PROBLEM 13: Compare the spending (PURCHASE_VALUE) on transport and fuel (MERCHANT_CATEGORIZED_AS - filter transport and fuel) across the years (YEAR)

PROBLEM 14: Compare the spending habit (PURCHASE_VALUE) between low income and high income earners (USER_INCOME) on loan repayments (MERCHANT_CATEGORIZED_AS - filter loan repayments)

PROBLEM 15: Compare the purchase value (PURCHASE_VALUE) across merchants (MERCHANT_CATEGORIZED_AS) per month (MONTH)
