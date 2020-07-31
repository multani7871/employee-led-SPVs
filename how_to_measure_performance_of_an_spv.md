# How to Measure the Performance of an SPV

An SPV is a fund that invests in a single asset. It's financially equivalent to buying that asset, minus the setup fee paid to the fund administrator and the performance fee paid to the SPV leader. The vast majority of employee led SPVs that invest in VC backed startups accept capital once and then distribute any returns when the company exits.

 We use four metrics to measure the performance of an SPV. Each metric tells us something different and we need all four to get the full picture.


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
		- In most SPVs, Distributions are usually 0 until the SPV is dissolved. A single distribution then happens and then Residual Value becomes zero. 
    -  TVPI can be either gross or net of fees. TVPI is usually calculated net of fees. 
-   IRR (Internal Rate of Return)
	-   Realized
		- Realized IRR is DPI but accounting for the Time Value of Money. For example, a DPI of 2 is great for a 2 year investment (~41%) but not so great for a 10 year investment (~7%). 
    -   Unrealized
	    - Unrealized IRR is TVPI but accounting for the Time Value of Money. SPVs usually only have one cash inflow at formation and then one cash outflow at dissolution. Sometimes an SPV may sell shares in between formation and dissolution. This would affect IRR but is rare enough that I won't cover that case here.

[This guide](http://www.allenlatta.com/allens-blog/lp-corner-private-equity-fund-performance-an-overview) is a excellent deep dive into these metrics with example calculations. I have very little to add to it. 


# Examples
- [https://twitter.com/HarveyMultani/status/1278715380500963330](https://twitter.com/HarveyMultani/status/1278715380500963330)
- [How much did Slack's investors make?](https://equityzen.com/knowledge-center/newsletter/now-that-slack-is-public-how-much-did-investors-make/)
- [Investment metrics from AngelList's Access funds](https://angel.co/blog/angellist-access-fund)
- 
<!--stackedit_data:
eyJoaXN0b3J5IjpbNjExMzAxODkwLDExOTEyNDM4MjcsLTQ1NT
MyNTQzMCwtMTIzODUzMDc2LC01MDUzNjk2NTMsNzQyMTY0Mzks
ODk2Mjk2MjkzLC0xNjM5NjY0OTEzLDMwNDczMjE0MSwxNjE3ND
k1NzY4LC0xMjU1MTMwMTgsLTIwNzQ4NzAzODcsLTIwOTk3MDgy
MjMsMjAzMjA1ODA5NSwtMzMwNDE5NTE4LDEyMzk3NTMxODQsLT
EzMzUwMDQwODBdfQ==
-->