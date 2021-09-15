# Option-pricing
Pricing vanilla call/put options using three different methods. We have explored three different methods in Matlab to compute the prices of vanilla options:
- Analytical Black Scholes Formula
- Option pricing using Monte Carlo Simulations 
- Pricing with Fourier transform.

We conclude that **Fourier transform is the preferred method compared to Monte Carlo** as it generates closer results to analytical Black-Scholes formula, in a computationally efficient way.
See table below for result summary:

| Method | Call price | Put price | CPU_time/seconds|
| :---         |     :---:      |          ---: |          ---: |
| Analytical Black-Scholes   | 0.1296540132   | 0.1958077069   | 0.1316101000 |
| Fourier transform    | 0.1296540132    | 0.1958077069   |0.2165400000    |
| Monte-Carlo     | 0.1296117247       | 0.1958316644       |6.1996122000      |
