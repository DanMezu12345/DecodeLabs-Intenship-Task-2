# Zone X Stores — Exploratory Data Analysis

## Overview
Exploratory analysis of 1,200 cleaned Zone X Stores orders, examining revenue trends, order fulfillment, payment behavior, and product performance to surface what's actually driving (or dragging) the business — including one finding that overturns the obvious first read of the data.

## Headline KPIs

| Metric | Value |
|---|---|
| Total Orders | 1,200 |
| Total Revenue | $1,264,761.96 |
| Total Quantity Sold | 3,535 units |
| Average Order Value | $1,053.97 |
| Unique Customers | 1,189 |

## Key Finding: The Partial-Year Trap
At face value, revenue by year looks like a collapse:
- 2023: $552,643.24
- 2024: $480,235.87 (-13.1%)
- 2025: $231,882.85 (appears to be -51.7%)

But 2025 only has 6 months of data. On a **monthly-average basis**:
- 2023 ≈ $46,053/month
- 2024 ≈ $40,020/month (-13.1%, a real decline)
- 2025 ≈ $38,647/month so far (only ~3.4% below 2024's run rate)

**Conclusion:** the 2023→2024 decline is real; the apparent 2024→2025 "collapse" is mostly a partial-year artifact, not a genuine acceleration in decline.

## Order Fulfillment
Fairly evenly distributed — not dominated by one status:
Cancelled 250, Returned 247, Pending 237, Shipped 235, Delivered 231 (roughly 19–21% each). The 20.8% cancellation rate is worth monitoring but isn't the majority-of-orders problem it might first appear to be.

## Payment Methods
Credit Card ($263,847.63) and Online ($262,442.94) lead, followed by Cash ($259,786.29) and Gift Card ($246,323.92); Debit Card is lowest ($232,361.18) — a mild skew (~12% spread), not dramatic.

## Product Performance
No single product dominates: Chair ($195,620.11) and Printer ($195,612.61) are essentially tied for the lead, followed by Laptop ($192,126.56) and Tablet ($186,568.95); Phone is lowest ($151,722.39).

## Tools Used
Excel — Pivot Tables, summary formulas
