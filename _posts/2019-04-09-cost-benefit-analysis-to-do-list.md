## Prioritize Your To-Do List By Converting To Present Value

There is an infinite number of ways you can spend your most valuable resource, time. How can you decide what the most cost-effective way to spend your time is? By converting the returns of each activity to its present value and picking the activity with the highest present value.

I live in a house that's bigger than I need and farther away from my job than I'd like. So I'd like to sell it and get a smaller apartment closer to work. However, this comes with a great cost. Assuming a sale price of $200,000, here are the typical costs of selling a house.

<iframe class="airtable-embed" src="https://airtable.com/embed/shrKWs8DhDmaQi6zn?backgroundColor=yellow&viewControls=on" frameborder="0" onmousewheel="" width="100%" height="533" style="background: transparent; border: 1px solid #ccc;"></iframe>

### Time Savings

It's also going to take a lot of time. In order to do apples to apples comparisons, we need to convert this time to a monetary value. According to the Bureau of Labor Statistics, the average American worker makes [$27/hour](https://www.bls.gov/news.release/empsit.t19.htm).

Moving closer to my job will save me 2 hours per week (an equivalent of $54 in weekly earnings). I assume I'll be working there for 4 more years, so let's calculate the equivalent present value of this expense. You can do this in Google Sheets with the following formula.

` Present Value = future_value/(1 + rate)^number_of_periods `

or in Google Sheets, you can use the formula:

` PV(rate, number_of_periods, future_value) `

- rate - This is the rate that you could get by investing this money.  [10%](https://www.nerdwallet.com/blog/investing/average-stock-market-return/) is the average annual rate of return for the stock market, so let's use that.
- number_of_periods - We're using the annual return and I'll be saving this drive for 4 years. So the number of periods is 4.
- future_value - We'll save $11,232 (52 weeks * $54/week * 4 years).

### Rent Savings

Say my monthly mortgage payment is $1400/month.  I can get a smaller apartment for $900/month.



https://github.com/mikepsinn/think-by-numbers-jekyll/blob/master/wp-content/uploads/present-value-formula.gif?raw=true

