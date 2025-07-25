# Supermarket Checkout Simulation - STA3113 Mini Project

## Project Overview

This project presents a discrete-event simulation of a supermarket checkout system with four counters and Poisson customer arrivals. The model estimates key performance metrics such as average customer waiting times, cashier utilization, and system throughput based on multiple simulation runs. It identifies operational bottlenecks and applies queueing theory principles to suggest improvements for efficient resource allocation and customer service.

## Features

- Customer arrivals modeled as a Poisson process.
- Shopping times follow a log-normal distribution.
- Dynamic assignment of customers to the shortest checkout queue.
- Service times modeled as exponential distributions with distinct rates per counter.
- Calculation of key performance indicators including waiting times, utilization rates, total throughput.
- Conducts multiple independent simulation replications for statistical robustness.
- Includes visualization of results and analysis of variability.

## Included Files

- `supermarket_simulation.Rmd` — Main R Markdown file with simulation code, analysis, and report.
- `header_footer.tex`  — LaTeX file for custom PDF footer formatting if used.
- Output files (`.pdf`) as generated .
- `README.md` — This document.





