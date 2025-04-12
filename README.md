This code runs a Discounted Free Cash Model for any listed equity to calculate its Intrinsic Value. This project make use of Yahoo Finance API to pull financial information of the ticker provide by the user. User has to input only the following information:
  1. Ticker (eg. AAPL)
  2. Expected free cash flow growth rate for next 10 years(eg. 5%)
  3. Expected free cash flow growth rate from 11th year and thereafter(eg. 2%)
  4. Discount Rate(eg. 9%)

The code pulls the annual free cash flow from the most recent financial statement and then uses the DFCF Model and Gordon's formula to calculate the instrinsic value of the business.
