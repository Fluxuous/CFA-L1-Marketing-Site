---
layout: post
category : tips
title : "What you need to know from the DCF Reading in L1 Quant Methods"
excerpt : <p>The 5 most important things you need to know in order to answer L1 Exam questions based on the CFA Discounted cash flow reading (That's study session 2, reading #6).</p>
--- 
# Here are the 5 most-likely things to be tested from L1's Discounted cash flow readings
Without further delay let's break down the key themes from the discounted cash flow reading and how to apply them to answer likely exam questions.


## Solving NPV & IRR Problems Using your Financial Calculator **

__The basic framework to solving NPV problems, aka "what questions to ask"__

	1. ID all the benefits (inflows) and costs (outflows)
	2. Determine the right discount rate to use
	3. Discount each cash flow using the discount rate. When inputting the cash flows, inflows are positive and outflows            are negative.
	4. The NPV is the sum of each discounted cash flow (DCF)
	5. Make a decision on the capital budget project (i.e. is NPV > 0?)


__Solving NPV on your financial calculator__

To calculate NPV on your financial calculator you need to use the cash flow (CF) function.  Every time you do this on the exam make sure to clear all previous cash flows work by pressing ([CF][2nd][CLR WORK]. **One big key to passing is not to lose points on problems you know the answer to!!**

Now that you're ready, start by enterubg all of the sequential cash flows.

	* CF0 is in the initial outlay and will be a negative number for a corporate finance project
	* CF1 is the first period’s cash flow and so on and so forth. Remember to use net cash flows.
	* When you are done entering the cash flows, hit NPV and enter the interest rate for I=?
	* Key down and CPT the NPV

*Solve for IRR using your financial calculator*

The steps for entering cash flows are identical to NPV problems. The only difference is that we now hit [IRR][CPT] to calculate the IRR (and of course we are not asked to input an external interest rate).

## Be able to compare/contrast the use of NPV and IRR, especially when dealing with mutually exclusive projects

For a single project NPV and IRR will result in the same decision. Any project with a positive NPV will have an IRR > required rate of return and vice versa *(when NPV = 0, the IRR = the required rate of return).*

But when facing mutually exclusive projects, or projects with non-conventional cash flow patterns, NPV and IRR can give conflicting answers. This is a result of either different initial costs and the timing of cash flows. In general, the __sooner__ cash flows occur, the __higher__ an IRR will be __even if the ultimate NPV of that project ends up being lower.__

|       Summarizing NPV   and IRR      |                                                                                                                                                                                              |                                                                                                                                          |
|:------------------------------------:|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------|
|                                      |    Net Present Value                                                                                                                                                                         |    Internal Rate of Return                                                                                                               |
|    Advantages                        |    -Directly   measures increase in value of firm.    -Assumes CF   reinvested at opportunity cost of capital                                                                                |    -Considers   TVM  and all CF   -Is less   subjective since doesn’t depend on external r   -Easy to   understand   -Widely accepted    |
|    Limitations                       |    -Based on   external market-determined discount rate (r)   -Assumes r   stable over time                                                                                                  |    -Assumes that   cash flows reinvested at IRR                                                                                          |
|    Decision Rule                     |    NPV > IRR for   mutually exclusive projects. For independent projects will give same answer   (IRR > opportunity cost of capital then NPV > 0 and vice versa.                             |                                                                                                                                          |
|    Reasons for different rankings    |    -Different cash   flow reinvestment rates and cash flow patterns   -Size (IRR Works   better with smaller opportunities)   -Timing of Cash   Flows – more CF in early years favors IRR    |                                                                                                                                          |

## Calculating TWRR, and comparing it against MWRR 
When the timing the timing of cash flows is different, MWRR and TWRR can give different returns.

Summarizing TWRR and MWRR    |                                                                                                                                                                        |                                                                                        |
|---------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------|
|                                 |    TWRR                                                                                                                                                                |    MWRR                                                                                |
|    Calculation                  |           Each CF-free sub-period   is chained together                                                                                                                |           Solve using your financial calculator                                        |
|    Advantages                   |    Measures actual rate of return earned by manager   Not sensitive to external CFs                                                                                    |    Only requires an account to be valued at beginning   and end                        |
|    Disadvantages                |    Requires an account/portfolio value at time of each   cash flow   Can be expensive and time consuming to compute                                                    |    MWRR hugely impacted by external cash flows                                         |
|    Appropriate When             |    Portfolio manager does NOT have discretion over   deposits and withdrawals made by clients                                                                          |    Portfolio manager has discretion over deposits and   withdrawals made by clients    |
|    Performance differences      |    ·           If   large CFs come in before strong   performance MWRR > TWRR   ·           If   those CFs come in before poor performance,   however, MWRR < TWRR.    |                                                                                        |

## Navigate between Holding Period Return, Bank Discount Yield, Effective Annual Yield / Money Market Yield, and the bond equivalent yield

Be able to convert from one to the other and also know which yields the highest value. 

* The HPY is the total return if the investor holds the note until maturity (coupon pmts, reinvestment return, final value)
* The EAY is the annualized HPY which uses a 365 day/year (sometimes 360) and accounts for compounding. To get EAY from the total holding perior return: EAY = (HPY)^(1/n)
* The BEY determines annualizes the yield of an investment that does not make annual payments. This allows investors to compare fixed-income securities whose payments are not annual or are selling at a discount to those with annual yields.
* The BDY is the annualized yield based on simple interest and 360 days/year.


__Now Go Practice!__
