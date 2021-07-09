---
title: "IRR Explained"
date: 2021-07-08T11:57:37-05:00
draft: true
---

---
title: IRR
created: '2020-05-13T05:50:18.839Z'
modified: '2020-05-13T05:51:37.053Z'
---

## What is IRR and How Does it Work?
The internal rate of return (IRR) is a widely used investment performance measure in commercial real estate, yet it’s also widely misunderstood. What is IRR exactly? How is it used and what are its limitations? 

### What is IRR?
First of all, what is IRR? Simply stated, the Internal rate of return (IRR) for an investment is the percentage rate earned on each dollar invested for each period it is invested. IRR is also another term people use for interest. Ultimately, IRR gives an investor the means to compare alternative investments based on their yield.

Mathematically, the IRR can be found by setting the Net Present Value (NPV) equation equal to zero (0) and solving for the rate of return (IRR).

![irr_formula](https://ckx564arsfh1icytr1p1ix7z-wpengine.netdna-ssl.com/wp-content/uploads/2013/06/irr.png)


### Step-by-Step Example and Proof of IRR
Memorizing equations is one thing, but truly understanding what’s actually happening with IRR will give you a big advantage. Let’s walk through a detailed example of IRR and show you exactly what it does, step-by-step.

Suppose we are faced with the following series of cash flows:

| Year    |  Cash Flow  |
|--------:|-------------|
|   1	  |  -$100,000  |
|	2     |   $0        |
|	3     |   $0        | 
|	4     |   $0        |
|	5     |   $0        |
| IRR     | 10.00%



This is pretty straightforward. An investment of $100,000 made today will be worth $161,051 in 5 years. As shown the IRR calculated is 10%. Now let’s take a look under the hood to see exactly what’s happening to our investment in each of the 5 years:

|Outstanding "Internal Investment"|    |   |  | ROI         |     | Return OF Investment|    |Total Cash Flow|
|-------------------------------- |----|---|---|------------|-----|---------------------|---- |--------------|
|$100,000                         |  X |10%| = |   $10,000  |+      |-$10,000           | =   | $0.00        |
|$110,000                         |  X |10%| = |   $11,000 | +     | -$11,00            | =   | $0.00        |
|$121,000                         |  X |10%| = |   $12,100  |+      |-$12,100           | =   | $0.00        |
|$133,100                         |  X |10%| = |   $13,310  |+      |-$13,310           | =   | $0.00        |
|$146,410                         |  X |10%| = |   $14,641  |+      |$146,410           | =   | $161,051     |
 |                               |     |    |  |  **$61,051**|+      |  **$100,000**        |  =  |  **$161,051** |


As shown above in year 1 the total amount we have invested is $100,000 and there is no cash flow received. Since the 10% IRR in year 1 we receive is not paid out to us as an interim cash flow, it is instead added to our outstanding investment amount for year 2. That means in year 2 we no longer have $100,000 invested, but rather we have $100,000 + 10,000, or $110,000 invested.

Now in year 2 this $110,000 earns 10%, which equals $11,000. Again, nothing is paid out in interim cash flows so our $11,000 return is added to our outstanding internal investment amount for year 3. This process of increasing the outstanding “internal” investment amount continues all the way through the end of year 5 when we receive our lump sum return of $161,051. Notice how this lump sum payment includes both the return of our original $100,000 investment, plus the 10% return “on” our investment.

This is much more intuitive than the mathematical (and typical) explanation of IRR as “the discount rate that makes the net present value equal to zero.” While technically correct, that doesn’t exactly help us all that much in understanding what IRR actually means. As shown above, the IRR is clearly the percentage rate earned on each dollar invested for each period it is invested. Once you break it out into its individual components and step through it period by period, this becomes easy to see.

### What IRR is Not
IRR can be a very helpful decision indicator for selecting an investment. However, there is one very important point that must be made about IRR: **it doesn’t always equal the annual compound rate of return on an initial investment.**

Let’s take an example to illustrate. Suppose we have the following series of cash flows that also generates a 10% IRR:

![example 2](https://ckx564arsfh1icytr1p1ix7z-wpengine.netdna-ssl.com/wp-content/uploads/2014/06/what_is_irr_example_2.png)

In this example an investment of $100,000 is made today and in exchange we receive $15,000 every year for 5 years, plus we also sell the asset at the end of year 5 for $69,475. The calculated IRR of 10% is exactly the same as our first example above. But let’s examine what’s happening under the hood in order to see why these are two very different investments:

 

![IRR](https://ckx564arsfh1icytr1p1ix7z-wpengine.netdna-ssl.com/wp-content/uploads/2014/06/what_is_irr_2.png)

As shown above in year 1 our outstanding investment amount is $100,000, which earns a return on investment of 10% or $10,000. However, our total interim cash flow in year 1 is $15,000, which is $5,000 greater than our $10,000 return “on” investment. That means in year 1 we get our $10,000 return on investment, plus we also get $5,000 of our original initial investment back.

Now, notice what happens to our outstanding internal investment in year 2. It decreases by $5,000 since that is the amount of capital we recovered with the year 1 cash flow (the amount in excess of the return on portion). This process of decreasing the outstanding “internal” investment amount continues all the way through the end of year 5. Again, the reason why our outstanding initial investment decreases is because we are receiving more cash flow each year than is needed to earn the IRR for that year. This extra cash flow results in capital recovery, thus reducing the outstanding amount of capital we have remaining in the investment.

Why does this matter? Let’s take another look at the total cash flow columns in each of the above two charts. Notice that in our first example the total $161,051 while in the second chart the total cash flow was only $144,475. But wait a minute, I thought both of these investments had a 10% IRR?! Well, indeed they did both earn a 10% IRR, as we can see by revisiting the definition or IRR:

The Internal rate of return (IRR) for an investment is the percentage rate earned on each dollar invested for each period it is invested.

The internal rate of return measures the return on the outstanding “internal” investment amount remaining in an investment for each period it is invested. The outstanding internal investment, as demonstrated above, can increase or decrease over the holding period. It says nothing about what happens to capital taken out of the investment. And contrary to popular belief, the IRR does not always measure the return on your initial investment.

### The Myth of The Reinvestment Rate Assumption
One of the most commonly cited limitations of the IRR is the so called “reinvestment rate assumption.” In short, the reinvestment rate assumption says that the IRR assumes interim cash flows are reinvested at the IRR, which of course isn’t always feasible. The idea that the IRR assumes interim cash flows are reinvested is a major misconception that’s unfortunately still taught by many business school professors today.

As shown in the step-by-step approach above, the IRR makes no such assumption. The internal rate of return is a discounting calculation and makes no assumptions about what to do with periodic cash flows received along the way. It can’t because it’s a DISCOUNTING function, which moves money back in time, not forward.

This is not to say the the IRR doesn’t have some limitations, as shown in the examples above. It’s just to say that the “reinvestment rate assumption” is not among them. Should you take into account the yield you can earn on interim cash flows that you reinvest? Absolutely, and there have been various measures introduced over the years to turn the IRR into a measure of return on the initial investment. Some of the more popular approaches include the modified internal rate of return (MIRR), the capital accumulation method, and the external rate of return (ERR). These approaches are beyond the scope of this article, but will be explored in the near future.

### Conclusion
The Internal Rate of Return (IRR) is a popular measure of investment performance. While it’s normally explained using its mathematical definition (the discount rate that causes the net present value to equal zero), this article showed step-by-step what the IRR actually does. What is IRR? Once you walk through the examples above this question becomes much easier to answer. It also becomes clear that the IRR isn’t always what people think it is. That is, it isn’t always the compound annual return on the initial investment amount. Understanding what IRR is at an intuitive level will go a long ways towards improving your ability to analyze potential investments.
