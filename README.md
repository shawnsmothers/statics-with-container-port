
#  Container Yard Statistics Analysis

## Project Overview
This project analyzes the number of shipping containers in a port yard, providing statistical insights to aid in decision-making regarding yard capacity and cost management.

## Key Statistics
- **Mean Number of Containers:** 122.12
- **Median Number of Containers:** 120.0
- **Mode:** 120 (appears 4 times)
- **Standard Deviation:** 40.24
- **Range:** 208
- **Variance:** 1686.36
- **Percentiles:**
  - 10th: 81
  - 25th: 110
  - 50th: 120
  - 75th: 140
  - 90th: 166

## Cost Analysis
- **Average Daily Cost:** 2076.04 USD (based on 17 USD per container)
- **Median Daily Cost:** 2040 USD

## Recommendations
- **Challenged Demurrage Cost:** The shipping line's proposed 1870 USD/day is only valid 25% of the time. It is not recommended for the port to accept this rate due to potential losses 75% of the time.
- **Capacity Reduction to 150 Containers:** This reduction is feasible as the number of containers is below 150 containers 75% of the time but may lead to operational challenges during peak periods.
- **Capacity Between 69 and 180 Containers:** Using Chebyshev's inequality, only about 50% of the data falls within this range, which does not meet the 60% requirement. Capacity planning should be reconsidered.

## Conclusion
This analysis provides a statistical foundation for making informed decisions regarding port yard capacity and cost management, ensuring operational efficiency and financial stability.
