Lab 7 - Akshat Nambiar - 181CO204

KNN on Credit Defaulters Dataset

Dataset: Defualt of Credit Card Clients


Attribute Information:

X1) Amount of the given credit (NT dollar): it includes both the individual consumer credit and his/her family (supplementary) credit
X2) Gender (1 = male; 2 = female)
X3) Education (1 = graduate school; 2 = university; 3 = high school; 4 = others)
X4) Marital status (1 = married; 2 = single; 3 = others)
X5) Age (year)
X6-X11) History of past payment(past monthly payment records from April to September 2005):
	X6 = the repayment status in September 2005; 
	X7 = the repayment status in August 2005
	X8 = the repayment status in July 2005;
	X9 = the repayment status in June 2005;
	X10 = the repayment status in May 2005;
	X11 = the repayment status in April 2005.
(Repayment status is: -1 = pay duly; 1 = payment delay for one month; 2 = payment delay for two months; . . .  8 = payment delay for eight months; 9 = payment delay for nine months and above)

X12-X17) Amount of bill statement (NT dollar):
	X12 = amount of bill statement in September 2005
	X13 = amount of bill statement in August 2005
	X14 = amount of bill statement in July 2005
	X15 = amount of bill statement in June 2005
	X16 = amount of bill statement in May 2005
	X17 = amount of bill statement in April 2005

X18-X23) Amount of previous payment (NT dollar): 
	X18 = amount paid in September 2005
	X19 = amount paid in August 2005
	X20 = amount paid in July 2005
	X21 = amount paid in June 2005
	X22 = amount paid in May 2005
	X23 = amount paid in April 2005


Metrics:

n = 5 neighbours
Accuracy = 76.23%

Accuracy when n = 1 : 69.56 %
Accuracy when n = 2 : 76.566 %
Accuracy when n = 3 : 73.633 %
Accuracy when n = 4 : 77.4166 %
Accuracy when n = 5 : 76.233 %
Accuracy when n = 6 : 77.33 %
Accuracy when n = 7 : 76.7 %
Accuracy when n = 8 : 77.85 %
Accuracy when n = 9 : 77.166 %
Accuracy when n = 10 : 77.8166 %
