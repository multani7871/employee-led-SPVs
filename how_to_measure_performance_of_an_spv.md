# How to Measure the Performance of an SPV

An SPV is a fund that invests in a single asset. It's financially equivalent to buying that asset, minus the setup fee paid to the fund administrator and the performance fee paid to the SPV leader. The vast majority of employee led SPVs that invest in VC backed startups accept capital once and then distribute any returns when the company exits.

How do we measure the performance of the SPV? We use four metrics to measure the performance of an SPV. Each metric tells us something different and we need all four to get the full picture of the SPV. 

The SPV generally exists in two states: 
- Active
	- An active SPV has accepted capital and purchased the underlying asset.
- Dissolved
	- A dissolved SPV has exited the asset. The SPV can exit the asset by either selling its shares or by distributing those shares at a terminal value. 


|   |  Leading |  Lagging |   
|-|-|-|
| **Ignores TVM**  | TVPI  | DPI  |   
| **Accounts for TVM**  | Unrealized IRR | Realized IRR  |   

***TVM** = Time Value of Money
- PI
	- Paid-in capital. The total amount of money investors have sent to the SPV (including admin fees).   
- DPI
    -   Distributions to Paid-In Capital. The total amount of money the SPV has returned to investors (Distributions) divided by Paid in Capital.
-   TVPI
	- Total Value (Residual Value + Distributions) divided by Paid-In Capital
		- in most SPVs, Distributions are usually 0 until all the distributions happen at once and then Residual Value becomes zero. 
    -  TVPI can be either gross or net of fees. TVPI is usually calculated net of fees. 
-   IRR (Internal Rate of Return)
	-   Realized
		- Realized IRR is DPI but accounting for the Time Value of Money. For example, a DPI of 2 is great for a 2 year investment but not so great for a 20 year investment. 
    -   Unrealized
-   Example calculations.
-   Show how secondaries can affect different metrics.
-   Link to example Google Sheet

Reasonable performance expectations based on company's stage
Examples from founder run public former VC backed companies with 10 years of data
-Tesla
--[https://twitter.com/HarveyMultani/status/1278715380500963330](https://twitter.com/HarveyMultani/status/1278715380500963330)
-[https://equityzen.com/knowledge-center/newsletter/now-that-slack-is-public-how-much-did-investors-make/](https://equityzen.com/knowledge-center/newsletter/now-that-slack-is-public-how-much-did-investors-make/)
-[https://angel.co/blog/angellist-access-fund](https://angel.co/blog/angellist-access-fund)
-[http://www.allenlatta.com/allens-blog/lp-corner-fund-performance-metrics-internal-rate-of-return-irr-part-one](http://www.allenlatta.com/allens-blog/lp-corner-fund-performance-metrics-internal-rate-of-return-irr-part-one)
-Amazon
-Facebook
Private stock trajectory examples from private companies that recently exited
-Slack
-Zoom
-Lyft
-

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTg1NjY3MTE2NiwtMTYzOTY2NDkxMywzMD
Q3MzIxNDEsMTYxNzQ5NTc2OCwtMTI1NTEzMDE4LC0yMDc0ODcw
Mzg3LC0yMDk5NzA4MjIzLDIwMzIwNTgwOTUsLTMzMDQxOTUxOC
wxMjM5NzUzMTg0LC0xMzM1MDA0MDgwXX0=
-->