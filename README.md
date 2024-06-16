# Part 1 - Breakdown the Business Obstacle & Goal:
I would approach the optimisation of Company-X by first breaking down the relevant information into steps.


### Problem Statement:
#### 1. How many people will work on acquiring new business, account management, and Support each month from month 1 to month 24?
#### 2. Why are they working there? The “Why” behind the calculation.
#### 3. What is the one variable to improve going into year 3?
* **How might we approach moving that variable?** 
    * **“Variable:"** one metric that would improve revenue by moving (more than other variables).

### CONTEXT 
* As part of the acquisition, I inherited 20 full-time Employees (FTE), each qualified to be a sales, account manager or customer support specialist.
* Starting month one of 24, each FTE will perform one core role at a time. 
* Each FTE can switch to another role at the start of any given month without losing productivity.
*  Company-X doesn’t offer any discounts.
* **Possibly erroneous details:** *"There has been a standalone support org in addition to Company-X  Team and support’s CSAT ([Customer Satisfaction](https://en.wikipedia.org/wiki/Customer_satisfaction))."*

### COMPANY-X CORE METRICS:

#### Company-X key metrics that won’t change with the acquisition: 
* Company-X customers pay a monthly baseline fee of $100 for the core product.
* The business currently has 1,000 customers. 
* Company-X acquires 25 customers a month organically 
* Company-X has great branding 
* Company-X has great customer referrals. 
* Customer Attrition Rate: -10% per month. Some customers turn to other, more specialised solutions.
* CSAT (Customer Satisfaction) has remained at 70% for several years.  

#### Company-X Roles & Responsibilities:
**Three Roles:**
1. **New Business Acquisition:** These people are responsible for selling and getting new customers in the door 
2. **Account Management:** These people help existing customers; they drive revenue growth from the customers they work with and improve retention
3. **Support:** These people solve customer problems; they improve retention for any active customer 

#### Company-X FTE Metrics:

* **Variable & Metric:** 
1. Customer Acquisition Numbers. 
2. CSAT (Customer Satisfaction) Scores.
3. Upselling: Revenue increases through account management, matching product benefits to existing customers' needs.
4. Relative Churn Decrease (customer attrition rate).

#### Agents:
**1. (C) Customer**
**2. (BA) Business Acquisition:** People working on New Business Acquisitions acquire 5 new customers monthly. (5 x 100 fee per month = $500 X Num of BAs)
**3. (SA) Support Agent:** Each support agent increases CSAT by 1 percentage point. Each point of CSAT leads to a 15% relative decrease in churn.
**4. (AM) Account Manager:** Account Managers increase revenue by 20% month-over-month for accounts they manage up to a cap of 6 months. 
   * **20% increase:** To be clear, this revenue increase compounds by 20% each month up to the 6th month, 
   * **MAX 6 Month:** at which point it maxes out and remains flat for the remaining duration of time that the customer has an account manager (for example, if a customer has an account manager in month 1, they’ll pay 120, in month 2 they’ll pay 144, etc.). If a customer has an account manager and then loses the account manager, their metrics (revenue per month) return to the baseline, but there isn’t a negative consequence.
   * **Assumption: MAX 1 6 Month MAX per C:** The assumption is that there is one 6-month period per customer and no repeats within the 24-month period.
   * **MAX 25 C per AM:** Each Account Manager can cover 25 customers at any given time. (Num Customers /25 * Num AC =  20% growth for a duration of less than or equal to six months)

# Summary
**Business Optimisation Problem:** The goal is to maximise Company-X cumulative revenue over the next 24 months. The revenue generated over a 24-month period, with the help of 20 Employees who will work each month for the next 24 months and can change roles once per month. 
**Strategy:** The goal will be reached by designing a strategy based on the weighting or the number of staff working a particular role at different periods of time during the exercise, the revenue generated, or the leakage stopped.
The constraints are a number of Agents/Roles, customer SaaS appetite saturation after 6 months, duration of the exercise, and the weighting can only be varied once per month.

## Optimise Company-X:
* Over the next 24 months, optimise Company-X. 
* Measure of Success Metric = Revenue: the sum of all revenue generated over 24 months, given there are 20 Employees who will work each month for the next 24 months. 
* Goal: Maximise the cumulative revenue generated over the entire period.
* Identify the next steps for year 3.



# Part 2 - Define Input Parameters:
Here is the strategy for how many people will do which roles and “The Why" behind the strategy for each role. Furthermore, the strategy for year three. 
By focusing on improving LTV, Company-X can ensure sustainable revenue growth and long-term success.

### 1. How many people will work on acquiring new business, account management, and support each month from month 1 to month 24?

The next step is to determine the number of people working in each role and to balance the goal:

1. **Customer Acquisition**: To bring in new customers.
2. **Revenue Growth**: To maximise revenue from existing customers.
3. **Customer Support and Satisfaction**: To improve customer satisfaction and reduce churn.

#### Assumptions:
- Each person can only perform one role per month.
- The roles can be switched at the start of any month.

**Initial Calculation Parameters**:
1. **Customer Acquisition**:
    - Each Business Acquisition (BA) person acquires 5 new customers per month.
2. **Account Management**:
    - Each Account Manager (AM) increases revenue by 20% month-over-month for accounts they manage for up to 6 months and can manage 25 customers.
3. **Support**:
    - Each Support Agent (SA) increases CSAT by 1 percentage point, leading to a 15% relative decrease in churn.

**Initial Conditions**:
- 1,000 customers at the start.
- 20 employees available.

**Month 1 to Month 24 Distribution**:

To maximise revenue over 24 months, we need to focus on acquiring new customers, increasing the revenue from existing customers, and reducing churn by improving customer satisfaction. Here's a balanced approach:

#### Month 1 to Month 6:
1. **BA**: 10 employees (acquiring 50 new customers/month)
2. **AM**: 5 employees (managing 125 customers)
3. **SA**: 5 employees (increasing CSAT by 5%)

#### Month 7 to Month 12:
1. **BA**: 7 employees (acquiring 35 new customers/month)
2. **AM**: 8 employees (managing 200 customers)
3. **SA**: 5 employees (maintaining a 5% CSAT increase)

#### Month 13 to Month 18:
1. **BA**: 5 employees (acquiring 25 new customers/month)
2. **AM**: 10 employees (managing 250 customers)
3. **SA**: 5 employees (maintaining a 5% CSAT increase)

#### Month 19 to Month 24:
1. **BA**: 3 employees (acquiring 15 new customers/month)
2. **AM**: 12 employees (managing 300 customers)
3. **SA**: 5 employees (maintaining a 5% CSAT increase)

### 2. Why are they working there?

**Customer Acquisition (BA)**:
- Initially, a higher number of BAs ensures a rapid increase in the customer base, providing a larger pool for revenue growth and support efforts.
- As the customer base grows, the focus can shift slightly towards managing and supporting these customers to maximise their revenue potential and retention.

**Account Management (AM)**:
- Increasing the number of AMs over time ensures that a growing proportion of the customer base benefits from revenue growth strategies, maximising the compound effect of monthly revenue increases.
- Account Managers are critical in sustaining the increased revenue from acquired customers and preventing churn.

**Support (SA)**:
- Consistent support ensures customer satisfaction (CSAT) is improved and maintained, which is directly linked to reduced churn.
- Maintaining a steady number of SAs helps to balance the need for new customer acquisition with the requirement to retain existing customers through high satisfaction levels.

### 3. What is the one variable to improve going into year 3?

**Variable: Customer Lifetime Value (LTV)**

**Approach to Improve LTV**:
- **Increase ARPU (Average Revenue Per User)**: Focus on upselling and cross-selling additional services or premium features to existing customers to increase their monthly spending.
- **Reduce Churn**: Continue to enhance customer satisfaction through proactive support and engagement strategies, reducing the number of customers who leave.
- **Extend Customer Lifetime**: Implement loyalty programs, regular check-ins, and value-added services to keep customers longer.

**Strategies**:
1. **Enhance Customer Success Initiatives**: Invest in customer success teams to provide personalised onboarding, training, and ongoing support.
2. **Product Development**: Continuously improve the core product and introduce new features based on customer feedback.
3. **Marketing and Engagement**: Use data analytics to identify at-risk customers and engage them with targeted campaigns and offers to retain them longer.
4. **Feedback Loops**: Regularly gather and act on customer feedback to improve products and services, ensuring they meet customer needs and preferences.




# Part 3 - Python code is broken down into steps to create the answer. 
I would write a Python program to automate the process of optimising the business outcomes I want to achieve. So that I can re-use modules of the code in other programs, I would break the code into steps.
This code calculates and displays the top 3 employee allocations that maximise revenue over 24 months.


### Step 1: Import necessary libraries and define functions
First, the necessary libraries are imported, and a function calculates the revenue based on the role allocations.

```python
# If you want access then just ask. LinkedIn.com/in/kiwi

# Function to calculate revenue based on role allocations

    
    return total_revenue
```

### Step 2: Define input parameters
Define the input parameters such as initial number of customers, duration in months, base fee, churn rate, etc.

```python
# Input Parameters

```

### Step 3: Generate all possible allocations of 20 employees
Generate all possible combinations of 20 employees allocated to the three roles (BA, AM, SA).

```python
# Generate all possible allocations of 20 employees

```

### Step 4: Calculate revenue for each allocation
Calculate the revenue for each allocation and store the results in a list.

```python
# Calculate revenue for each allocation

```

### Step 5: Sort results by revenue and display the top 3 allocations
Sort the results by revenue in descending order and display the top 3 allocations.

```python
# Sort results by revenue


# Print top 3 allocations

```

### Full Code
This code calculates and displays the top 3 employee allocations that maximise revenue over 24 months.

```python

    return total_revenue

# Input Parameters

# Generate all possible allocations of 20 employees


# Calculate revenue for each allocation


# Sort results by revenue


# Print top 3 allocations

```

END. 

Now, we can use this business optimisation tool for future Business Acquisition processes. 
Yours Faithfully, 
Amy Newkirk | Founder of APAC Gold Ltd. 

![Newkirk's Oath for Business   Organisational Mana QR CODE](https://github.com/APAC-GOLD/BusinessAquisitions/assets/84517825/8b115510-70e1-4ef3-9b8a-168c2c83297e)

