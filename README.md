# Exercise Description

## Overview

Please find attached a CSV file containing user spend, negative amounts, and income, positive amounts, across various categories.

In the Data Scientist job description, one of the areas you'll be working in is as follows:

    The development of targeted nudges based on current and historical data to ensure financial wellness.  As an example, a well known principle is that users should spend 50% of their net income on essential expenses, 30% on wants and 20% on savings & investments; you could be developing techniques to measure how well someone aligns with this viewpoint and helping the user achieve a state of financial zen.
    
The task is to use the provided data to show some interesting insight that relates to the above.  The dataset suffers from a number of problems:

* It is incomplete, part of the task is determining what you can show reliably.
* No transaction categorisation engine is perfect, some of the calculated category spends may be incorrect.  You may want to use a strategy, ideally a simple one, that minimises this issue and explain how what you've done mitigates it.
* This is a small sample of users, how valid are any conclusions for the population at large?

A Jupyter notebook with Python code, graph(s) and surrounding narrative is the expected form of submission.  It's OK to use Pandas and a graphing library of your choice.  No more than 1-2 hours is the expected time to complete the exercise, with prior knowledge of any libraries and functions required, so feel free to limit your analysis to what is sensible to complete in this timeframe.  If that is only a couple of graphs and narrative then that's fine.

Once complete, please share privately your analysis via email to daniel.cook@moneyhub.com and john.dyer@moneyhub.com.

## CSV File Description

The CSV file has 4 columns:

* User identifier.
* Category of income/expenditure.
* The total in a given month.  Negative values are spending, positive values are income.
* The month the total relates to.

The categories present are as follows, there is often an overlap between categories (e.g. child and education):

* paychecks - Salary received.
* retirement - Pension income received.
* investment - Income from investments received.
* other-income - Other income received, e.g. government benefits.
* groceries - Supermarket food shopping.
* restaurants - Non essential eating out and drinks.
* child - Child related expenses.
* education - Education related expenses, could be school fees.
* service - Bank fees.
* utilities - Utility bills.
* telephone - Mobile phone and home telephone bills.
* cable - Broadband.
* insurance - Insurance policies.
* automotive - Car running costs.
* healthcare - Medical and healthcare costs.
* loans - Loan repayments.
* mortgages - Mortgage repayments.
* taxes - Taxes such as council tax.
* rent - Rent payments.

If a user doesn't receive income or spend in a particular category, it doesn't appear in the file.
