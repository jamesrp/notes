# Hal Varian - Intermediate Microeconomics
search for e.g. "varian intermediate microeconomics filetype:pdf" on google.

there is a workbook: "varian bergstrom workouts filetype:pdf"

## ch1 - the market
* supply and demand curves, derivation from reservation prices;
* price maximization via profit(q) := price * q(price)
* pareto efficiency

## ch2 - budget constraint
* budget set {x: cx <= m}. assuming prices are positive, this is a simplex.
* describing change of budget set under changes in m or in c.
* government interventions: tax, subsidy, etc just change the apparent price of goods. rationing imposes another linear constraint on budget set.

## ch3 - preferences
* preferences and indifference curves
* marginal rate of substitution is slope of indifference curve: MRS = -d_x1/d_x2
* useful to use dollars as one of the goods [but how does this look in n dimensions? a tangent plane giving all i-j exchange rates?]

## ch4 - utility
* derive utility from preferences
* ordinal utility, essentially just labeling the nested indifference curves with arbitrary increasing numbers. preserved under [order-preserving transformations](https://en.wikipedia.org/wiki/Monotonic_function)
* cardinal utility would be an ordinal utility that also supported e.g. addition, multiplication. but it doesn't have any justification.
* Cobb-Douglas utility function: product of x_i ^ c_i (can assume c_i sum to 1). Alternatively, sum of c_i log(x_i).
* marginal utility := dU/dx_i. can calculate MRS (see ch3) with this, via dx_i  dx_j = (dU/dx_i) / (dU / dx_j).
* example: for w = walking time to bus or car in minutes, t = trip time in minutes, c = trip cost in dollars. U(w,t,c) = -.147w - .0411t - 2.24c predicts 93% of bus vs car choices! this is amazing. from the [lecture](http://www.nobelprize.org/nobel_prizes/economic-sciences/laureates/2000/mcfadden-lecture.pdf) it looks like this may be a simplification of the actual work.

## ch5 - choice
* Given budget constraint and utility function (or indifference curves) we can find the utility-maximizing bundle of goods
* Conversely, given observed behavior at different income levels and prices, we can estimate utility function.
  * I wonder if we can do this at all in software products, e.g. trading off page load time (or data use) and page functionality. Seems tough since we don't have prices, but may be able to do something here.
* At a fixed market price, the price ratio between two goods will be equal to the marginal rate of substitution: for everyone! Because if it weren't for someone, they should alter their purchases until it is. This is an optimality condition assuming everyone pays the same prices for goods.
* For a given consumer, an income tax is always higher utility (for a given revenue extracted) than a consumption tax on a good. But, different consumers might have different utility functions, so a given income tax might not leave everyone better off uniformly. Haven't worked through this but it seems it might be interesting in the case of multiple utility functions.
