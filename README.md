# Multi-Platform Quick-Commerce Ad Campaign Simulation 

A more comprehensive, end-to-end practice project simulating full campaign ownership across **Blinkit, Amazon, and Flipkart** — built to prepare for a Business Analyst Intern interview (quick-commerce performance marketing role).

|---|---|---|---|
| Scope | One platform, one snapshot | One platform, trend over time | **Three platforms, full decision cycle** |
| Skill mirrored | Keyword harvesting | Report tracking | **Full ownership of campaign execution** |
| Output | A metric table | A flagged trend report | **A tested, data-backed budget plan with projected impact** |

This project simulates the entire loop a campaign owner would run: **measure → test → decide → project impact** — not just one step of it.

## What this project does

1. Compares current performance across **3 ad platforms** sharing one ₹3,00,000 monthly budget
2. Identifies the weakest platform (Flipkart) and runs an **A/B creative test** to find out *why* it's underperforming
3. Uses both findings to build a **proposed budget reallocation** for the next month
4. Projects the expected ROAS improvement from that reallocation — same total spend, better return

## File structure

**`Multi_Platform_Campaign_Simulation.xlsx`** — 5 sheets:

1. **Executive Summary** — Dashboard with 4 key numbers (budget, conversions, current ROAS, projected ROAS) and a guide to the rest of the workbook
2. **Platform_Summary** — Current Month 1 performance for Blinkit, Amazon, and Flipkart, with a bar chart comparing budget vs. ROAS
3. **AB_Test_Results** — Two ad creatives tested on Flipkart (discount-led vs. speed-led messaging), with an automatic formula declaring the winner
4. **Reallocation_Plan** — Proposed new budget split (pie chart included) plus projected conversions and ROAS per platform
5. **Insights_Report** — The written manager-facing recommendation

## Key findings

1. **Blinkit** has the strongest ROAS of the three platforms — under-funded relative to its performance
2. **Flipkart** is the weakest performer — low conversions despite a meaningful budget
3. **A/B test result:** a speed-led creative ("Delivered in 10 min") beat a discount-led creative on Flipkart, at equal impression volume — messaging about speed resonates more than a generic discount here
4. **Decision:** shift ₹30,000 from Flipkart to Blinkit, while keeping a smaller, more efficient Flipkart budget running the winning creative (rather than cutting it entirely)
5. **Projected outcome:** blended ROAS improves from ~0.29x to ~0.33x on the same total spend

## Why I built this

The JD specifically mentions "full ownership of execution of campaigns" — not just analyzing data someone else collects, but running the whole loop: spot a problem, test a fix, make a budget decision, and project the outcome. I wanted one project that demonstrates that full cycle, since my first two projects each covered only one piece of it (analysis, then reporting).

## Tools used

Microsoft Excel / Google Sheets (formulas: SUMPRODUCT for blended ROAS, IF logic for A/B test winner, conditional formatting, bar chart, pie chart, cross-sheet references for a linked dashboard)

## How I'd explain it in 30 seconds if asked

"This one's a bit more end-to-end — I simulated managing a shared budget across three quick-commerce platforms, found the weakest one, ran an A/B test to figure out why, and used that result to build a new budget plan with a projected ROAS improvement. It's meant to mirror actually owning a campaign, not just analyzing one piece of it."
