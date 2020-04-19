This blog belongs to Mathematics for Finance Section, Black-Scholes model is used to solve Option Pricing problems.

## Mathematics Prerequisite
* Standard Normal Cumulative Distribution Function
* Probability Density Function
* Partial Differential Equation


## Financial Concepts
* European Options, European Call Option, European Put Option
* Option Pricing
* Volatility
* Exercise(Strike) Price

## Black-Scholes Formula for European Option Price

The Black-Scholes formula is used to calculate the price of European call and put options.

$$C(S,t)=N(d_1)S - N(d_2)Ke^{-rt} \quad(1)$$

$$d_1= \frac{1}{\sigma \sqrt{t}} \left[\ln{\left(\frac{S}{K}\right)} + t\left(r + \frac{\sigma^2}{2} \right) \right] \quad(2)$$

$$d_2= \frac{1}{\sigma \sqrt{t}} \left[\ln{\left(\frac{S}{K}\right)} + t\left(r - \frac{\sigma^2}{2} \right) \right] \quad(3)$$

$$N(x)=\frac{1}{\sqrt{2\pi}} \int_{-\infty}^{x} e^{-\frac{1}{2}z^2} dz \quad(4)$$
