## Prioritize Your To-Do List By Converting To Present Value

There is an infinite number of ways you can spend your most valuable resource, time. How can you decide what the most cost-effective way to spend your time is? By converting the returns of each activity to its present value and picking the activity with the highest present value.

I live in a house that's bigger than I need and farther away from my job than I'd like. So I'd like to sell it and get a smaller apartment closer to work. However, this comes with a great cost. Assuming a sale price of $200,000, here are the typical costs of selling a house.

<iframe class="airtable-embed" src="https://airtable.com/embed/shrKWs8DhDmaQi6zn?backgroundColor=yellow&viewControls=on" frameborder="0" onmousewheel="" width="100%" height="533" style="background: transparent; border: 1px solid #ccc;"></iframe>

It's also going to take a lot of time. In order to do apples to apples comparisons, we need to convert this time to a monetary value. According to the Bureau of Labor Statistics, the average American worker makes [$27/hour](https://www.bls.gov/news.release/empsit.t19.htm).

Moving closer to my job will save me 2 hours per week (an equivalent of $54 in weekly earnings). I assume I'll be working there for 4 more years, so let's calculate the equivalent present value of this expense. You can do this in Google Sheets with the following formula.

> PV(rate, number_of_periods, payment_amount, [future_value], [end_or_beginning])

- rate - The interest rate.
- number_of_periods - The number of payments to be made.
- payment_amount - The amount per period to be paid.
- future_value - [ OPTIONAL ] - The future value remaining after the final payment has been made
- end_or_beginning - [ OPTIONAL - 0 by default ] - Whether payments are due at the end (0) or beginning (1) of each period.




