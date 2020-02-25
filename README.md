On Canvas (or in this notebook's files) you’ll find a new file, lendingclub.csv. Each row of this file represents a single user account on LendingClub.com. The site consists of two types of users, borrowers who are applying for a new loan, and investors who lend money for fixed periods of time. Each row in our dataset represents a single borrower at the time they apply for their first peer-to-peer loan, and each row contains nine columns:
Amount requested for their first loan
Year the loan was requested (this dataset covers only a five-year period, 2008-2012)
Title of the loan application (written by the borrower)
FICO score (credit rating) of the borrower
“Debt-to-Income”: A ratio of the borrower’s total monthly debt payments, excluding home mortgage and the requested loan, to the borrower’s self-reported monthly income.
ZIP code of the borrower (the last two digits of each ZIP are masked for anonymity)
U.S. state that the borrower resides in.
Length of time that the borrower has been employed at their current job, from 0 to 10+ years.
A binary outcome variable for whether the user’s loan application was accepted by investors.
Our goal with this project will be to automatically predict whether a borrower will be approved for a loan from the investor members of the website, based only on the data provided above. For each of the following questions, add a series of code and markdown cells to develop an easily readable report responding to the question.
