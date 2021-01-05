# Python
In this project, we analyze the data from 2000 customers to prepare two predictive models to determine wheter a cutomer will buy or not an insurance.

The main libraries used in this project are: pandas, numpy, sklearn, keras:

The columns are:
id_new: (str type) 9-letter unique customer ID
buy: (num type; target) cross-selling outcome by 30 days post-contact, 1 = “purchased, vehicle insurance”, 0 = “no purchase”
age: (num type) customer’s age at the time of contact
gender: (str type) “male” or “female”
tenure: (num type) number of days since policyholder’s current medical insurance has started
region: (num type) unique code-number assigned to the region in which customer lives
dl: (num type) 1 = “has valid driver license”, 0 = “no driver license”
has_v_insurance: (num type) 1 = “already has valid car insurance”, 0 = “no valid car insurance”
v_age: (str type) vehicle age, three possible labels: “1-2 year”, “< 1 year”, “> 2 years”
v_accident: (str type) “yes” or “no”, vehicle had accident(s) before
v_prem_quote: (num type) annual premium quote for the cross-sold car insurance (local dollar, possibly different for each policyholder)
cs_rep: (num type) unique code-number assigned to the customer-service representative who attempted to cross-sell the car insurance
