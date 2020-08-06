# How to Measure an SPV's Performance

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

|   |  TVPI |  IRR |   
|-|-|-|
| **Seed** | 0.00x  | 100%  |   
| **Series A**  | 0.00x  | 70%  | 
| **Series B**  | 0.00x  | 60%  |
| **Series C**  | 0.00x  | 50%  |
| **Series D**  | 0.00x  | 40%  |
| **Series E**  | 0.00x  | 30%  |
| **Series F**  | 0.00x  | 20%  |

# Examples
- [Tesla's TVPI and IRR since going public](https://twitter.com/HarveyMultani/status/1278715380500963330)
- [How much did Slack's investors make?](https://equityzen.com/knowledge-center/newsletter/now-that-slack-is-public-how-much-did-investors-make/)
- [Investment metrics from AngelList's Access funds](https://angel.co/blog/angellist-access-fund)
- [a16z's IRRs](https://www.theinformation.com/articles/andreessen-horowitz-returns-slip-according-to-internal-data)
- [Quixotic Ventures](https://quixotic.ventures/2020/08/03/quixotic-portfolio-returns/)
- [Alumni Ventures Group Returns](https://cdn2.hubspot.net/hubfs/3925488/_Source%20of%20Truth%20Mirrored%20Folder/01%20Policies%20and%20Products/Performance_19-12-31.pdf)
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE1NTU5MTAwOCw5MzQ4NTc3MDYsMTMwND
Q1ODY4MywxMTkxMjQzODI3LC00NTUzMjU0MzAsLTEyMzg1MzA3
NiwtNTA1MzY5NjUzLDc0MjE2NDM5LDg5NjI5NjI5MywtMTYzOT
Y2NDkxMywzMDQ3MzIxNDEsMTYxNzQ5NTc2OCwtMTI1NTEzMDE4
LC0yMDc0ODcwMzg3LC0yMDk5NzA4MjIzLDIwMzIwNTgwOTUsLT
MzMDQxOTUxOCwxMjM5NzUzMTg0LC0xMzM1MDA0MDgwXX0=
-->