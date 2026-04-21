# Project Viewing Options
  1. The best and easiest way to view this project is by viewing the HTML file. If the HTML file isn't rendering in browser, download it and open it.
  2. The 2nd option is to press the '.' key when the repository is open in the browser. This will open the github.dev editor in read-only mode which allows you to view the .ipynb notebook.
  3. The last, more complicated, way of viewing this project is by running the .ipynb notebook yourself. I do not recommend this option if you do not have experience with Jupyter notebooks. First, download the .ipynb file and it's required data file(s) then upload them to Google Colab, and run the notebook. Check to make sure the data file(s) are uploaded into the correct directory on Google Colab or it will not run correctly. Depending on the project, the runtime type might have to be changed.

# FoodHub

### Problem Statement

Build a model for AllLife Bank to predict which liability customers are likely to purchase personal loans. The goal is to improve targeted marketing, boost conversion rates, and identify key customer attributes and segments that drive loan adoption.

### Context

AllLife Bank is a US bank that has a growing customer base. The majority of these customers are liability customers (depositors) with varying sizes of deposits. The number of customers who are also borrowers (asset customers) is quite small, and the bank is interested in expanding this base rapidly to bring in more loan business and in the process, earn more through the interest on loans. In particular, the management wants to explore ways of converting its liability customers to personal loan customers (while retaining them as depositors).

A campaign that the bank ran last year for liability customers showed a healthy conversion rate of over 9% success. This has encouraged the retail marketing department to devise campaigns with better target marketing to increase the success ratio.

You as a Data scientist at AllLife bank have to build a model that will help the marketing department to identify the potential customers who have a higher probability of purchasing the loan.

### Objective

To predict whether a liability customer will buy personal loans, to understand which customer attributes are most significant in driving purchases, and identify which segment of customers to target more.

### Data Dictionary
* `ID`: Customer ID
* `Age`: Customer’s age in completed years
* `Experience`: #years of professional experience
* `Income`: Annual income of the customer (in thousand dollars)
* `ZIP Code`: Home Address ZIP code.
* `Family`: the Family size of the customer
* `CCAvg`: Average spending on credit cards per month (in thousand dollars)
* `Education`: Education Level. 1: Undergrad; 2: Graduate;3: Advanced/Professional
* `Mortgage`: Value of house mortgage if any. (in thousand dollars)
* `Personal_Loan`: Did this customer accept the personal loan offered in the last campaign? (0: No, 1: Yes)
* `Securities_Account`: Does the customer have securities account with the bank? (0: No, 1: Yes)
* `CD_Account`: Does the customer have a certificate of deposit (CD) account with the bank? (0: No, 1: Yes)
* `Online`: Do customers use internet banking facilities? (0: No, 1: Yes)
* `CreditCard`: Does the customer use a credit card issued by any other Bank (excluding All life Bank)? (0: No, 1: Yes)
