# Monte Carlo Simulation (Excel)

> Class Project · CIS 211, University of Rochester

Two Monte Carlo simulations built in Excel to model systems where outcomes are uncertain.

## What It Does

**Problem 1 — Cocktail bar queue**: simulates 500 customers at a bar, with exponential interarrival times (`=-mean*LN(RAND())`) and random service times, tracking queue time, start/end times, and the average time a customer waits.

**Problem 2 — Bank cash demand**: simulates daily cash withdrawals over 1,000 trials using `NORM.INV(RAND(), mean, sd)` with weekday-specific means and standard deviations, tracking beginning/ending balances and flagging days the branch runs out of money.

## Tech Stack

Excel · Monte Carlo simulation · RAND / NORM.INV / LN

## How to Run

Download `Monte-Carlo-Simulation.xlsx` and open it in Excel. Press F9 to re-run the simulations with new random draws. (GitHub cannot preview Excel files — download the file to view it.)

## Files

| File | What it is |
| --- | --- |
| `Monte-Carlo-Simulation.xlsx` | Both simulations, one workbook |
