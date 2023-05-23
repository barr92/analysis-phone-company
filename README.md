# Megaline Telecom Revenue Analysis

## Project Description

As analysts at Megaline, our primary task is to conduct a preliminary analysis of the Surf and Ultimate plans using a subset of 500 Megaline clients. These clients provide us with valuable data, including their personal information, plan type, and usage details such as the number of calls made, text messages sent, and data consumed in the year 2018.

## Plan Descriptions

Before we dive into the data analysis, let's familiarize ourselves with the Surf and Ultimate plans:

### Surf Plan
- Monthly Charge: £20
- 500 monthly minutes
- 50 text messages
- 15 GB of data
- Additional Charges:
  - 1 minute: £0.03
  - 1 text message: £0.03
  - 1 GB of data: £10

### Ultimate Plan
- Monthly Charge: £70
- 3000 monthly minutes
- 1000 text messages
- 30 GB of data
- Additional Charges:
  - 1 minute: £0.01
  - 1 text message: £0.01
  - 1 GB of data: £7

## Instructions on Completing the Project

To successfully complete this project, follow these steps:

### Step 1: Open the data file and study the general information

Download the following datasets:
- `megaline_calls.csv`: Contains data on calls made by Megaline users
- `megaline_internet.csv`: Contains data on internet sessions
- `megaline_messages.csv`: Contains data on text messages sent
- `megaline_plans.csv`: Contains information about the calling plans
- `megaline_users.csv`: Contains data on Megaline users

### Step 2: Prepare the data

- Convert the data to the appropriate types
- Identify and eliminate any errors in the data
- Document the errors found and describe how you resolved them
- For each user, determine:
  - The number of calls made and minutes used per month
  - The number of text messages sent per month
  - The volume of data consumed per month
  - The monthly revenue from each user (subtract the free package limits from the total number of calls, text messages, and data; multiply the result by the respective calling plan charges; and add the monthly charge depending on the calling plan)

### Step 3: Analyze the data

- Describe the behavior of Megaline customers
- Determine the minutes, text messages, and data volume required by users of each plan per month
- Calculate the mean, variance, and standard deviation for each plan
- Visualize the distributions using histograms
- Provide insightful descriptions of the distributions observed

### Step 4: Test the hypotheses

- Formulate the null and alternative hypotheses for two tests:
  - Test 1: The average revenue from users of the Ultimate and Surf calling plans differs
  - Test 2: The average revenue from users in the NY-NJ area is different from users in other regions
- Select an appropriate alpha value for the tests
- Explain the criteria used to test the hypotheses and justify your choices

### Step 5: Produce conclusion and business recommendations
